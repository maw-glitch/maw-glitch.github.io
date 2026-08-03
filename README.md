# maw-glitch.github.io

Personal resume / portfolio site — plain HTML + CSS, no build step.

## Preview locally
Open `index.html` in a browser, or serve it:
```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy (GitHub Pages)
1. Create a repo on GitHub named **`maw-glitch.github.io`**.
2. Push these files to the `main` branch.
3. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. Site goes live at **https://maw-glitch.github.io** (first build takes ~1 min).

## Editing
All content lives in `index.html`, marked with `<!-- TODO -->` comments.
Styling is in `style.css` (colors/fonts are CSS variables at the top).
