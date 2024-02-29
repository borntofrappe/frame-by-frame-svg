# frame-by-frame-svg

```html
<frame-by-frame-svg></frame-by-frame-svg>
```

Add your SVG spritesheet.

```html
<frame-by-frame-svg>
  <svg width="30" height="30" viewBox="0 0 100 100">
    <!-- ...sprites -->
  </svg>
</frame-by-frame-svg>
```

Style the SVG element directly.

```html
<frame-by-frame-svg>
  <style>
    svg {
      color: gold;
    }
    @media (pointer: coarse) {
      svg {
        inline-size: 40px;
        block-size: 40px;
      }
    }
  </style>
  <svg width="30" height="30" viewBox="0 0 100 100">
    <!-- ...sprites -->
  </svg>
</frame-by-frame-svg>
```
