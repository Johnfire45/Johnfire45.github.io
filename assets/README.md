# Assets

Place files here when ready. The folders are organized by type.

---

## images/

| File | Purpose |
|------|---------|
| `og-card.png` | Open Graph image for link previews (1200 × 630px recommended) |
| `profile.jpg` | Profile photo — if added to hero or about section |
| `unireq-screenshot.png` | UniReq extension screenshot — for the Work section |
| `unireq-demo.gif` | UniReq demo recording — optional |

Link images in `index.html` using relative paths, e.g.:
```html
<img src="assets/images/profile.jpg" alt="Harshit Shah" width="80" height="80">
```

---

## icons/

| File | Purpose |
|------|---------|
| `favicon.ico` | Browser tab icon |
| `apple-touch-icon.png` | iOS home screen icon (180 × 180px) |
| `favicon-32x32.png` | Standard favicon PNG (32 × 32px) |
| `favicon-16x16.png` | Small favicon PNG (16 × 16px) |

Add to `<head>` in `index.html`:
```html
<link rel="icon" href="assets/icons/favicon.ico">
<link rel="apple-touch-icon" href="assets/icons/apple-touch-icon.png">
```

---

All assets in this directory are ignored from the live site unless explicitly linked from `index.html`.
