# Dinh Dynamic Portfolio

Static portfolio website for GitHub Pages, modeled after the dynamic welcome-page pattern in the sample portfolio folder. Open `index.html` directly in a browser, or push this folder to a GitHub repo and enable Pages.

## Files

- `index.html` - the portfolio page
- `styles.css` - responsive layout, welcome screen, theme, cards, and section styling
- `script.js` - welcome session state, theme toggle, mobile menu, interactive tabs, project filtering, and reveal motion
- `assets/hero-workspace.png` - generated hero image for the first screen
- `assets/favicon.svg` - browser icon
- `.nojekyll` - tells GitHub Pages to publish files as-is

## Portfolio style

This version follows the sample portfolio's interaction pattern:

- First-visit welcome page
- Dynamic hero focus card
- Fit lens tabs
- Project filters
- Scroll reveal motion
- Light/dark theme toggle

The project section intentionally excludes BI and Python cases. It only uses frontend, UI, website, and landing page examples.

## Current target: Portfolio repo

This folder is ready to push to:

```text
https://github.com/DEANPHAM117/Portfolio
```

After GitHub Pages is enabled from branch `main` and folder `/ (root)`, the site will normally open at:

```text
https://deanpham117.github.io/Portfolio/
```

## About the root GitHub Pages domain

To open the site directly at:

```text
https://deanpham117.github.io/
```

the GitHub repository must be named:

```text
DEANPHAM117.github.io
```

If the repository is named `Portfolio`, GitHub Pages will normally publish it at:

```text
https://deanpham117.github.io/Portfolio/
```

So do not add `deanpham117.github.io` as a custom domain in the `Portfolio` repo. Use the special repo name above instead.

## Enable GitHub Pages for Portfolio

1. Push these files to the `DEANPHAM117/Portfolio` repo on branch `main`.
2. Open `Settings` > `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Choose branch `main` and folder `/ (root)`.
5. Click `Save`.
6. Wait for GitHub to publish the site. The final URL should be `https://deanpham117.github.io/Portfolio/`.

## Push from this folder to Portfolio

Run these commands inside this folder:

```powershell
git add .
git commit -m "Initial portfolio site"
git remote add origin https://github.com/DEANPHAM117/Portfolio.git
git push -u origin main
```

If `origin` already exists, use:

```powershell
git remote set-url origin https://github.com/DEANPHAM117/Portfolio.git
git add .
git commit -m "Initial portfolio site"
git push -u origin main
```

## Optional: root domain setup

1. Create a GitHub repo named `DEANPHAM117.github.io` under the `DEANPHAM117` account.
2. Push these files to that repo.
3. Open the repo `Settings` > `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Choose branch `main` and folder `/ (root)`.
6. Click `Save`.
7. Wait for GitHub to publish the site. The final URL should be `https://deanpham117.github.io/`.

## Push from this folder to the root-domain repo

Run these commands inside this folder after the `DEANPHAM117.github.io` repo exists:

```powershell
git init -b main
git add .
git commit -m "Initial portfolio site"
git remote add origin https://github.com/DEANPHAM117/DEANPHAM117.github.io.git
git push -u origin main
```

If this folder already has Git initialized, use:

```powershell
git add .
git commit -m "Initial portfolio site"
git remote set-url origin https://github.com/DEANPHAM117/DEANPHAM117.github.io.git
git push -u origin main
```

## Custom domain later

If you buy a custom domain later, add it in `Settings` > `Pages` > `Custom domain`. GitHub will create or update a `CNAME` file. You also need to configure DNS at the domain provider.

For now, you do not need a paid domain. The free GitHub Pages URL above is enough.
