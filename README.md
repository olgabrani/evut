# Evia Ultra Trail 2026

Personal race page for the **Evia Ultra Trail** — 108.5 km · +5478 m · 26h limit.

## Deploy to GitHub Pages

1. Push this repo to GitHub (if not already done).
2. Go to **Settings → Pages**.
3. Under *Source*, select **Deploy from a branch**.
4. Choose branch `main` (or `master`) and folder `/ (root)`.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within ~60 seconds.

## After the race

Update the Results card in `index.html`:

1. Find the `div` with class `card disabled` (the Results card).
2. Change `<div class="card disabled">` → `<a class="card" href="YOUR_RESULTS_URL" target="_blank" rel="noopener noreferrer">`.
3. Remove the `<span class="coming-soon-badge">Σύντομα</span>` line.
4. Close with `</a>` instead of `</div>`.
