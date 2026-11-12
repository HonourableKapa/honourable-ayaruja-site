# Honourable Ayaruja personal site

A single-page site in plain HTML and CSS. No framework, no build step, no JavaScript, no third-party requests.

## Files

- `index.html`: all page copy and markup.
- `style.css`: all styling. Colours are CSS custom properties at the top of the file.

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Any static host works with zero config: no build command, and the publish directory is the repository root. For GitHub Pages, set the source to the `main` branch and the `/ (root)` folder. For Netlify, Vercel or Cloudflare Pages, leave the build command empty and set the output directory to `.`.

## Update copy and colours

- Edit the text directly in `index.html`. External links keep `target="_blank"` and `rel="noopener noreferrer"`.
- Change the palette in the `:root` block of `style.css` (`--bg`, `--text`, `--muted`, `--accent`, `--border`). Re-check WCAG AA contrast after any change.
