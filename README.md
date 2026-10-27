# Tyler Galarneau portfolio

Plain HTML/CSS portfolio for GitHub Pages. No build step.

## Structure
- `index.html`: home page (hero and project cards)
- `projects/project-1.html` to `project-3.html`: project pages
- `artifacts/`: the work samples each project page links to
- `assets/style.css`: all styling
- `.nojekyll`: tells GitHub Pages to serve files as-is

## Preview locally
Run `python -m http.server 8099` in this folder and open http://localhost:8099/.

## Deploy to GitHub Pages
1. Upload the contents of this folder (not the folder itself) to the repo's `main` branch.
2. Make the repo public: Settings, Danger Zone, Change visibility, Public.
3. Settings, Pages, Source "Deploy from a branch", branch `main`, folder `/ (root)`, Save.
4. After a minute or two the site is live at `https://<username>.github.io/<repo-name>/`.
