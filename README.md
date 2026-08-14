# matthew-oj.github.io

Static single-page personal site. No build step, no dependencies.

## Structure

- `index.html` — page content
- `styles.css` — styling
- `pdf/` — resume, dissertation, and geotechnical report PDFs linked from the page

## Local preview

Open `index.html` directly in a browser, or serve the directory:

```
npx serve .
```

## Deploy

Push to `main`; hosting picks up static files directly (no build step required).
