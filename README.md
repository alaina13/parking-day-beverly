# Parking Day Beverly

Static site for Parking Day Beverly, MA. Plain HTML/CSS, no build step.

## Stack

- HTML/CSS only, no framework, no build
- `styles.css` holds the full design system (orange/green palette, distinct from other Beverly civic sites)

## Local preview

```
python3 -m http.server 8765
```

Then open http://localhost:8765

## Deploy

GitHub Pages, served from the `main` branch root. Enable it under
Settings -> Pages -> Source: Deploy from a branch -> `main` / `/ (root)`.

## Status

Scaffold only. Copy in `index.html` is placeholder and needs real event
details (date, location, sponsors, FAQ).
