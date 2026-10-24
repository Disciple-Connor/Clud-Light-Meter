# Clud Light Meter

A light meter for 35mm film cameras that installs on your phone like an app and works offline.

## Put it online (GitHub Pages, free)

1. Sign in at github.com (create a free account if you need one).
2. Click **+** (top right) → **New repository**. Name it `clud-light-meter`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Drag in every file from this folder (`index.html`, `manifest.webmanifest`, `sw.js`, and the four `.png` icons). Click **Commit changes**.
5. Go to **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
6. Wait a minute, then refresh. The page shows your address, like `https://YOUR-NAME.github.io/clud-light-meter/`.

## Install it on your phone

**iPhone:** open the address in Safari → Share → **Add to Home Screen** → **Add**.
**Android:** open the address in Chrome → ⋮ menu → **Install app** (or **Add to Home screen**).

Open it once while online so it saves itself for offline use. After that it works with no connection.

## Updating

Upload a changed `index.html` to the repository. To make sure phones pick up the change, also change `clud-meter-v1` to `clud-meter-v2` (and so on) at the top of `sw.js`.
