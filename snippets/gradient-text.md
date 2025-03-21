---
title: Gradient text
tags: visual
expertise: intermediate
cover: blog_images/red-berries.jpg
firstSeen: 2018-02-25T15:14:39+02:00
lastUpdated: 2020-12-30T15:37:37+02:00
---

Gives text a gradient color.

- Use `background` with a `linear-gradient()` value to give the text element a gradient background.
- Use `webkit-text-fill-color: transparent` to fill the text with a transparent color.
- Use `webkit-background-clip: text` to clip the background with the text, filling the text with the gradient background as the color.

```html
<p class="gradient-text">Gradient text</p>
```

```css
.gradient-text {
  background: linear-gradient(#70D6FF, #00072D);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  font-size: 32px;
}
```
