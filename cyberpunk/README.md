## Cyberpunk chat

This is a cyberpunk-themed chat, originally made for Kyoslilmonster

https://github.com/Penwy/css-chatboxes/assets/37129613/8d88f54d-a038-4691-8b0a-fd55f73fac64

It also allows showing a custom "Wanted for" message for specific users, the template at the end of the .css allows adding users :
```css
.chat_line[data-nick=""] .message::after{
  content: '';
  background: url(https://raw.githubusercontent.com/Penwy/css-chatboxes/main/cyberpunk/assets/cyberpunk_wanted_for.png) no-repeat !important;
}
```

Add the username (the exact one in the twitch URL, no caps) in the quotes after `data-nick=`, and the desired message in the quotes after `content:`.
Alternatively remove the whole `[data-nick=""]` if you want it to appear for all users.
