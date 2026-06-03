# MolmoMotion Blog Post

A static blog post for **MolmoMotion: Language-guided 3D motion forecasting**, styled with the AI2 brand palette and the Manrope typeface.

## Structure
- `index.html` — the page content
- `styles.css` — all styling (AI2 colors, Manrope, layout)
- `images/` — figures, demo GIFs, and result graphs

## Graph slots
The three result graphs are marked in `index.html` with `id` anchors so they're easy to find / move:
- `#graph-forecasting` — 3D motion forecasting results (`images/image8.png`)
- `#graph-robotics` — robotics planning results (`images/image15.png`)
- `#graph-videogen` — video generation metrics (`images/image14.png`)

## Local preview
Open `index.html` in a browser, or run a local server:
```
python3 -m http.server 8000
```
then visit http://localhost:8000

## Hosting
Published with GitHub Pages from the `main` branch root.
