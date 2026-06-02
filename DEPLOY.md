# Deploy to GitHub Pages (5 minutes)

## 1. Create a GitHub repo

- Go to https://github.com/new
- Name it something like `flashcards` (or anything you like)
- Set it to **Public**
- Click **Create repository**

## 2. Upload the files

- On the repo page, click **"uploading an existing file"**
- Drag and drop ALL files from the `flashcards-pwa` folder:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Click **Commit changes**

## 3. Enable GitHub Pages

- Go to **Settings** > **Pages** (left sidebar)
- Under "Source", select **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click **Save**
- Wait 1-2 minutes, then your site will be live at:
  `https://YOUR-USERNAME.github.io/flashcards/`

## 4. Install on your iPhone

- Open the URL above in **Safari** (must be Safari, not Chrome)
- Tap the **Share** button (square with arrow)
- Scroll down and tap **"Add to Home Screen"**
- Tap **Add**

Done! The app now works offline and looks like a native app.

## Updating cards later

Edit `index.html` on GitHub, or use the app's Export/Import to manage your data.
Your progress (known/review status) is saved in the browser and persists across sessions.
