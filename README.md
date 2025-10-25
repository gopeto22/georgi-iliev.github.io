# gopeto22.github.io (personal site)
A minimal, static page that links to my **CV**, **Thesis Abstract**, and shows a **photo**.

## Files
- `index.html` – single-page site
- `styles.css` – lightweight, responsive styles
- `avatar.jpg` – headshot
- `CV.pdf` – curriculum vitae
- `Abstract.pdf` – thesis abstract

## Deploying with GitHub Pages

### Option A — Root user site (recommended)
### User site (root domain)
1. This repository name already matches the required pattern: `gopeto22.github.io`.
2. Ensure `index.html` stays at the repo root on the default branch (`main`).
3. Push. GitHub Pages will publish to `https://gopeto22.github.io` in a few minutes.

> User/Org sites must be named `<username>.github.io`; project sites live at `/<reponame>/`

### Project site (alternate setup)
1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Branch: `main`** and **Folder: `/ (root)`**, then **Save**.
3. All asset links here are **relative** so they work at either path.

> Pages must be enabled from **Settings → Pages** by selecting a publishing source/branch.

## Local preview
Just open `index.html` in a browser, or run a tiny server:
```bash
python -m http.server 8080
