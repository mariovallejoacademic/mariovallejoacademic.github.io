# Mario Portfolio (GitHub Pages)

A zero-dependency, single-file portfolio. Category tabs live under **Portfolio** and only show the selected section. Deep links work, e.g. `#portfolio/Coding`.

## Quick deploy (no command line)
1. Create a new repo on GitHub (any name, e.g. `mario-portfolio`).
2. Click **Add file → Upload files** and upload these files: `index.html`, `.nojekyll`, `404.html` (optional).
3. Go to **Settings → Pages**.
   - Build and deployment → **Source: Deploy from a branch**.
   - **Branch: main**, **Folder: / (root)**. Click Save.
4. Your site will be available at: `https://<your-username>.github.io/<repo-name>/`

## Command line (optional)
```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin git@github.com:<your-username>/<repo-name>.git
git push -u origin main
```
Then enable Pages in **Settings → Pages** (source: Deploy from a branch, main / root).

## Notes
- No frameworks. Pure HTML/CSS/JS.
- `.nojekyll` disables Jekyll on GitHub Pages.
- Because the site uses hash routes (`#home`, `#portfolio/Coding`), direct links work without extra configuration.
