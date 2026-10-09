# Cox Rowing Racer

A small, static HTML rowing practice game. No build tools or external libraries are required.

## Run locally
Open `index.html` in a modern browser. The core game works without a server. Service-worker/PWA offline installation requires HTTPS or localhost.

## Publish on GitHub Pages
1. Create a repository.
2. Upload **all four files** from this folder (`index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`) to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Open the published Pages URL. On iPad, use Safari's Share menu → **Add to Home Screen**.

## Controls
- **Space**: stroke / initiate a stroke surge
- **Left arrow / A**: steer toward Bow (rower's left)
- **Right arrow / D**: steer toward Stroke (rower's right)
- **P**: pause/resume
- **R**: reset race
- On touchscreen, press and hold the Bow/Stroke steering buttons; tap STROKE to trigger a manual stroke.
