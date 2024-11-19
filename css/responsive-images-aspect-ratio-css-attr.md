# Responsive Images with Aspect Ratio Using CSS attr()

```css
img {
  max-width: 100%;
  height: auto;
  aspect-ratio: attr(width) / attr(height);
}
```

```html
<img
  src="example.jpg"
  width="1920"
  height="1080"
  alt="A responsive example image"
/>
```
