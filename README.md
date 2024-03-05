# frame-by-frame-svg

## What is this?

A web component to animate SVG sprites in steps. If defined and included in the document.

```html
<frame-by-frame-svg></frame-by-frame-svg>
```

You'll be able to see a few sparkles as you tap the page.

## Attributes

- `speed`: number of milliseconds you'll see a single frame

- `delay`: number of milliseconds before the animation starts

```html
<frame-by-frame-svg speed="40" delay="0"></frame-by-frame-svg>
```

## Sprites

Bring your own SVG spritesheet in the form of an `svg` element.

```html
<frame-by-frame-svg>
  <svg viewBox="0 0 100 100"></svg>
</frame-by-frame-svg>
```

Add the `width` and `height` attribute to set the size of the element on the page.

```html
<frame-by-frame-svg>
  <svg width="40" height="40" viewBox="0 0 100 100"></svg>
</frame-by-frame-svg>
```

Add the individual frames as direct children, one after the other in the same exact canvas.

<!-- prettier-ignore -->
```html
<svg width="40" height="40" viewBox="0 0 100 100">
  <path d="M 43 49 Q 45 40 49 48 58 47 52 53 56 61 48 57 42 64 42 56 35 50 43 49" />
  <path d="M 38 45 Q 39 32 45 32 Q 51 33 52 43 64 41 64 46 64 50 58 54 64 61 59 66 52 69 48 63 45 72 37 70 33 68 36 57 28 56 28 49 30 44 38 45 M 46 48 47 50 50 50 49 52 50 55 46 54 44 56 44 53 42 52 45 50 46 48" />
  <!-- ... -->
</svg>
```
