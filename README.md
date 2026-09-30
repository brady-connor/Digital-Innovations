# Brady Connor — Portfolio

Files in this repo:

- `index.html` — main portfolio site
- `links.html` — mobile-first Linktree-style page
- `baseline.html` — the original generic AI output (Week 1 comparison artifact, not linked from the live site)

## How to publish this with GitHub Pages

1. **Create the repo**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `portfolio` (repo name doesn't matter for Pages)
   - Set it to **Public**
   - Click **Create repository**

2. **Upload the files**
   - On the new repo page, click **Add file → Upload files**
   - Drag in `index.html`, `links.html`, and `baseline.html`
   - Scroll down, click **Commit changes**

3. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab
   - Click **Pages** in the left sidebar
   - Under "Build and deployment," set **Source** to `Deploy from a branch`
   - Set **Branch** to `main` (or `master`) and folder to `/ (root)`
   - Click **Save**

4. **Get your live link**
   - Wait 1–2 minutes, then refresh the Pages settings page
   - Your site will be live at `https://<your-github-username>.github.io/<repo-name>/`
   - `links.html` will be at `https://<your-github-username>.github.io/<repo-name>/links.html`

5. **Update the cross-links (optional but recommended)**
   - Once you have your real GitHub Pages URL, open `index.html` and `links.html` in GitHub's editor (pencil icon)
   - Find the `claude.ai/artifact/...` links and replace them with your new `.github.io` URLs so everything points to the permanent GitHub-hosted version instead of the Claude-hosted one
   - Commit the change

That's it — this satisfies the assignment's GitHub requirement (repo + version history) and gives you a permanent, real-world-shareable link for your resume, LinkedIn, and NFC chip use case in Week 3.
