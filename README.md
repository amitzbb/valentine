# Valentine

A small Valentine's Day landing page with a photo CAPTCHA: **4 out of 6** images are "correct" (you + your girlfriend). She has to select those 4 to pass and see your message.

## Setup

1. Open `index.html` in a browser (or use a local server if you prefer).
2. Add your photos in the `images/` folder — see `images/README.md` for the exact filenames.
3. Edit the message in `index.html` (the `.message-view` section) if you want to change the text she sees after passing.

## How it works

- **6 images** in a grid: 4 of you/her (or you together), 2 decoys.
- She taps 4 images and clicks "Prove it's you 💕".
- If she picked the 4 correct ones, the page reveals your Valentine's message.
- Wrong selection shows "Not quite — try again."

## Put it on GitHub Pages

1. **Push the repo to GitHub** (if you haven't already):
   ```bash
   git add .
   git commit -m "Valentine page"
   git push origin main
   ```

2. **Turn on GitHub Pages** in the repo:
   - Open the repo on GitHub → **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment**, set **Source** to **Deploy from a branch**.
   - **Branch**: `main` (or `master`) · **Folder**: `/ (root)`.
   - Click **Save**.

3. **Wait a minute or two.** The site will be at:
   ```
   https://<your-username>.github.io/valentine/
   ```
   Replace `<your-username>` with your GitHub username. Share that link with Moran.
