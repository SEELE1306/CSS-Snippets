# Spotify Controls

## Description

Redesign for Spotify Controls.

## How to change overlay strength

After importing the snippet, copy and paste this snippet. Afterwards, change the values to those you prefer.

- For `import.css` and `import-legacy.css`:

```css
:root {
  --blur-amount: 2px; /* higher px = stronger blur, 0 = no blur */
  --darken-percent: 0.5; /* 0 = album cover is not darkened, 1 = album cover is darkened fully (black) */
}
```
