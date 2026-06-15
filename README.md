# Fazil P S — Portfolio

A single-file static portfolio site. Everything (HTML + CSS + JavaScript) lives in **`index.html`** — the only other things are the 5 images.

```
.
├── index.html        ← the whole site (open or edit this)
├── images/           ← your 5 photos (PNG placeholders for now)
│   ├── hero-portrait.png
│   ├── work-mode.png
│   ├── speaking.png
│   ├── casual.png
│   └── environment.png
└── resume.pdf        ← add your own (the buttons link to this)
```

## Swap in your real photos
The site works as-is with placeholders. When ready, **replace the files in `images/` keeping the same filenames** (they are PNGs):

| File | Used for | Best shape |
|------|----------|-----------|
| `hero-portrait.png` | Hero portrait (top right) | Portrait ~3:4 |
| `work-mode.png` | About banner | Wide ~16:7 |
| `speaking.png` | Leadership section | Portrait ~4:5 |
| `casual.png` | spare / LinkedIn-style | Square 1:1 |
| `environment.png` | Contact background | Wide ~16:9 |

## Personalize
Open `index.html` and update: `you@example.com`, the `https://www.linkedin.com/` links, and add `resume.pdf` so the download buttons work. Colors/fonts are in the `:root` block at the top of the `<style>` — the font is a system stack (Calibri / Segoe UI / Arial) and the theme is white + navy (`--navy`, `--steel`).

## Host on GitHub Pages
1. Create a repo and upload `index.html`, the `images/` folder (and `resume.pdf`).
2. Settings → Pages → Deploy from a branch → `main` / root → Save.
3. Live at `https://<username>.github.io/<repo>/` in ~1 minute.
Tip: name the repo `<username>.github.io` for a clean root URL.
