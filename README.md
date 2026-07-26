# Portfolio site — setup

A small, dependency-free site (`index.html`, `style.css`, `script.js`). No build step.

## 1. Customize
Open `index.html` and replace every `[bracketed placeholder]` — name, role, bio,
projects, experience, contact links. Colors and fonts live at the top of
`style.css` under `:root` if you want to change the palette.

## 2. Preview locally
Just open `index.html` in a browser, or run a quick local server:
```
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## 3. Deploy with GitHub Pages
1. Create a new GitHub repo (e.g. `portfolio`) and push these three files
   (`index.html`, `style.css`, `script.js`) to the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and `/ (root)` folder → **Save**.
4. Your site will be live in a minute or two at:
   `https://YOUR_USERNAME.github.io/portfolio/`

To use a custom domain, add a `CNAME` file with your domain name to the repo,
and point your DNS to GitHub Pages per
[GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Files
- `index.html` — structure and content
- `style.css` — design tokens (`:root` variables) + layout
- `script.js` — scroll-reveal animation + date stamp in the footer
- `profile-README.md` — a separate template for your GitHub *profile* README
  (the one that shows on `github.com/YOUR_USERNAME`). See the comment at the
  top of that file for setup steps.
