# hsuani.github.io

Personal portfolio site. Static HTML/CSS, no build step. Auto-served by GitHub Pages from the `main` branch.

Live: https://hsuani.github.io

## Local preview

Just open `index.html` in a browser, or run a tiny static server:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Edit

- Content: `index.html`
- Styles: `style.css`
- CV PDF: drop your PDF at `assets/CV.pdf` (the "Download CV" button links here)
- Project screenshots / images: `assets/img/`

## Things to fill in before launch

Search and replace the following placeholders in `index.html`:

- `[Your Name]` — your real name (multiple occurrences)
- `email@example.com` — your real email (multiple occurrences)
- `linkedin.com/in/your-handle` — your real LinkedIn handle (multiple occurrences)
- Verify GitHub link points to `https://github.com/hsuani`
- Drop the actual `CV.pdf` into `assets/CV.pdf`

## Deploy

Repository must be named `hsuani.github.io` for the user-site URL to work.

1. Create the repo on GitHub (public, no README, no .gitignore, no license).
2. Push this directory:

```bash
cd hsuani.github.io
git init -b main
git add .
git commit -m "Initial portfolio site"
git remote add origin https://github.com/hsuani/hsuani.github.io.git
git push -u origin main
```

3. In repo Settings → Pages → Source: select `main` branch, `/ (root)` folder. Save.
4. Wait 1–2 minutes; site is live at https://hsuani.github.io
