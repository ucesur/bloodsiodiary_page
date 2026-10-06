# Bloodsio Diary — Support & Privacy Site

Static (HTML/CSS) version of the `sites.google.com/view/tensioncare` pages, ready for GitHub Pages.

## Files

- `index.html` — Home / Support (hero, features, contact, FAQ)
- `privacy-policy.html` — Privacy Policy
- `styles.css` — Shared stylesheet
- `images/` — Put your screenshots and logo here
- `.nojekyll` — Makes GitHub Pages serve files as they are
- `.github/workflows/deploy.yml` — Optional GitHub Actions deploy workflow

## Publishing on GitHub Pages

1. Create a new **public** repo named `bloodsiodiary_page`.
2. Upload everything in this folder to the repo root, or:

   ```
   git init
   git add .
   git commit -m "Initial release"
   git branch -M main
   git remote add origin https://github.com/ucesur/bloodsiodiary_page.git
   git push -u origin main
   ```

3. **Settings → Pages → Source:** Deploy from a branch, `main`, `/ (root)` (or choose **GitHub Actions** to use the included workflow).
4. The site will be live at `https://ucesur.github.io/bloodsiodiary_page/`.

## Screenshots and store link

- Put images in `images/` and replace each `.phone .screen` block in `index.html` with
  `<div class="screen"><img src="images/screen-1.png" alt="Bloodsio Diary screen"></div>`.
- Replace the store badge's `href="#"` in `index.html` with your real store link.
- Contact email everywhere: `randommobileapp@gmail.com`.
