# Personal Portfolio

This repository contains a responsive portfolio site using Tailwind CSS. It uses the image at `assets/chitthetwai.jpg` and links to your CV PDF.

Quick start

1. Install dependencies:

```bash
npm install
```

2. Build production CSS:

```bash
npm run build:css
```

3. Open `index.html` in a browser or serve with a static server.

Deploy to GitHub Pages

- Option A: Use the included GitHub Actions workflow (it runs on push to `main` and deploys to `gh-pages`). Make sure the repository has the `GH_TOKEN` secret or use the default `GITHUB_TOKEN`.

- Option B: Manually enable Pages in repository settings and select `main` branch and root `/` folder.

Notes

- The Tailwind source is in `src/styles.css` and compiles to `assets/styles.css`.
- Projects are loaded dynamically from `assets/projects.json`.
# chitthetwai.github.io