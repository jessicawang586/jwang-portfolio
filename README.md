# Jessica Wang — Portfolio

A single-page portfolio site (HTML/CSS/JS, no build step) showcasing my mechanical
engineering experience at Blue Origin, Tesla, Aerojet Rocketdyne, and Formula SAE
Electric at Berkeley.

## Files

- `index.html` — page content
- `styles.css` — styling
- `script.js` — nav + scroll interactions

## Publish it on GitHub Pages

1. Create a new repo on GitHub (e.g. `jessica-portfolio`) — don't initialize it with a README.
2. In this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Your site goes live at `https://<your-username>.github.io/<repo-name>/` (usually within a minute).

To use a custom domain later, add a `CNAME` file with the domain and configure DNS per
GitHub's docs.

## Local preview

Just open `index.html` in a browser, or serve it locally:
```bash
python3 -m http.server 8000
```
then visit `http://localhost:8000`.

## Updating content

Edit the relevant section in `index.html` (experience entries, skills, education),
commit, and push — GitHub Pages redeploys automatically.
