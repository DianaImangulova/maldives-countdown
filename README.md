# Maldives Countdown 🏝️

A phone-friendly, installable countdown web app — a day-by-day plan (29 June → 14 July) combining gym, Pilates, yoga, sauna, skincare and self-tan, with tappable checkboxes that save in your browser and a progress bar.

This repo is ready to host **free** on GitHub Pages, which gives you a real public link you can add to your phone's home screen so it opens like a native app.

---

## Files

- `index.html` — the app (open this / it's the homepage)
- `manifest.webmanifest` — makes it installable as a home-screen app
- `icon-192.png`, `icon-512.png`, `icon-180.png` — app icons

---

## Put it online with GitHub Pages

You can do all of this from your phone's browser.

### 1. Create the repository
1. Go to **github.com** and sign in (make a free account if needed).
2. Tap **+** (top right) → **New repository**.
3. Name it e.g. `maldives-countdown`.
4. Set it to **Public**.
5. Tap **Create repository**.

### 2. Upload these files
1. On the new repo page, tap **uploading an existing file** (or **Add file → Upload files**).
2. Upload **all** the files from this folder: `index.html`, `manifest.webmanifest`, and the three `icon-*.png` files.
3. Tap **Commit changes**.

### 3. Turn on GitHub Pages
1. In the repo, go to **Settings** → **Pages** (left menu).
2. Under **Branch**, choose **main** and **/ (root)**, then **Save**.
3. Wait ~1 minute. The page will show your live link, like:
   `https://YOUR-USERNAME.github.io/maldives-countdown/`

### 4. Add it to your home screen
1. Open that link in **Safari** (iPhone) or **Chrome** (Android).
2. **iPhone:** Share button → **Add to Home Screen** → Add.
3. **Android:** ⋮ menu → **Add to Home screen** / **Install app**.

Done — tap the icon any time to open your plan. It auto-scrolls to today and your ticks are saved on the device.

---

## Notes
- Checkboxes are saved with your browser's local storage on **that device**. They won't sync across phones, and clearing browser data will reset them.
- To edit the plan later, edit `index.html` in GitHub (the `days` array near the bottom of the file holds every day) and commit — your live link updates automatically.
