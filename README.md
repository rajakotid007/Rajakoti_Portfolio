# Premium Personal Portfolio

A polished, editorial-style personal portfolio built with simple HTML, CSS, and JavaScript.
This repository is prepared for GitHub Pages deployment from the repository root.

## Project Structure

- `index.html` — homepage (entry file for GitHub Pages)
- `style.css` — styling, layout, and animations
- `script.js` — navigation interactivity, reveal behavior, and footer year
- `.nojekyll` — disables Jekyll processing so static assets are served as-is

## GitHub Pages Readiness Checklist

- `index.html` is in the repository root.
- All local asset paths are relative (`style.css`, `script.js`) and work on GitHub Pages.
- No build step is required.
- Site is publishable directly from `/ (root)`.

## Exact GitHub Pages Deployment Steps (Repository Root)

1. Push this repository to GitHub.
2. Open **Repository Settings** → **Pages**.
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: your default branch (for example, `main`)
   - **Folder**: `/ (root)`
4. Click **Save**.
5. Wait for deployment to complete.
6. Open the published URL shown in Pages settings.
