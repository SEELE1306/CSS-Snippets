# Titlebar

## Description

Changes the default Discord titlebar to a more visually appealing one. You can customize the text and background color to your liking.

![Titlebar](/docs/_media/Titlebar_01.png)

![Titlebar](/docs/_media/Titlebar_02.png)

## Requirements

If you are using [Vesktop](https://github.com/Vencord/Vesktop), make sure to head to Settings > Vencord > Vesktop Settings and enable the **Discord Titlebar** checkbox.

## How to apply

After importing the snippet, copy and paste this snippet. Afterwards, change the text and color to those you prefer.

```css
:root {
  --titlebar-name: "Discord Mod";
  --titlebar-background: #0b7e74;
}
```

If you want to use the Discord's accent color for the background color, modify the above snippet to the following. Note that this also works well with the snippet [AccentColor](Snippets/ChangeColor/AccentColor/).

```css
:root {
  --titlebar-name: "Discord Mod";
  --titlebar-background: var(--brand-experiment);
}
```

