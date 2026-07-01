# Start at the Top — Landing Page

Static landing page for the "Start at the Top: The Revenue Expansion Blueprint" event (Sept 28–30, 2026).

## Files
- `index.html` — the landing page
- `video.mp4` — preview video (compressed for web, ~8MB)
- `poster.jpg` — video poster/thumbnail image

## Hosting on GitHub Pages

1. Create a new repository on GitHub (public, or private if you're on a paid plan).
2. Upload all three files in this folder to the root of the repo (drag-and-drop works on github.com, or `git add . && git commit -m "landing page" && git push`).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Pick the `main` branch and `/ (root)` folder, then **Save**.
6. GitHub will give you a URL like `https://your-username.github.io/your-repo-name/` within a minute or two — that's your live landing page.

## Notes
- The "Send me more information" form currently only shows a confirmation message in the browser — it doesn't send the data anywhere yet. To collect real submissions, connect it to a form service (e.g. Formspree, Basin) or your own backend, and update the `<form>` handler in `index.html`.
- If you want a custom domain instead of the `github.io` URL, add a `CNAME` file with your domain, and configure the DNS records GitHub Pages asks for (also under Settings → Pages).
