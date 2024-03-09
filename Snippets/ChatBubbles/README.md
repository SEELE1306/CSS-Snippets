# Chat bubbles

## Description

Adds a chat bubble around messages. Different colours are available for normal, replying, mentioned and automod messages.

## How to change bubble colors

After importing the snippet, copy and paste this snippet. Afterwards, change the colors to those you prefer.

- For `import.css`:

```css
:root {
  --chat-bubble-default: grey;
  --chat-bubble-replying: cyan;
  --chat-bubble-mentioned: orange;
  --chat-bubble-automod: red;
  --enable-chat-bubble-border: 1; /* 0 to turn off, default is on or 1 */
}
```

- For `import-legacy.css` (Note that these colors follow the HSL scheme):

```css
:root {
  --chat-bubble-default: 0 0% 50%;
  --chat-bubble-replying: 180 100% 50%;
  --chat-bubble-mentioned: 39 100% 50%;
  --chat-bubble-automod: 0 100% 50%;
  --enable-chat-bubble-border: 1; /* 0 to turn off, default is on or 1 */
}
```
