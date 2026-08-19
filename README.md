# watchfaces-pages

GitHub Pages site hosting the privacy policy for Jeremy Lee's Wear OS watch face apps (Trek Console, Simplicity).

Live at: https://jeremywenkailee.github.io/watchfaces-pages/privacy/

## Setup (one-time)

1. Create a new **public** GitHub repo named `watchfaces-pages` under `jeremywenkailee`.
2. Push this folder to it:
   ```bash
   git init
   git add .
   git commit -m "Add privacy policy site"
   git branch -M main
   git remote add origin https://github.com/jeremywenkailee/watchfaces-pages.git
   git push -u origin main
   ```
3. In the repo's Settings → Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Wait a minute or two, then the privacy policy is live at the URL above.
5. Paste that URL into Play Console → each app → App content → Privacy policy.
