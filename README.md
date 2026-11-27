# Tabletop Trainer

Blackjack and poker trainer that installs as a home-screen app. Progress saves on each person's own device; nothing is sent anywhere.

## Put it on GitHub Pages

1. Create a new public repository on GitHub (for example `tabletop-trainer`).
2. Upload every file in this folder to the repository's main branch.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-NAME.github.io/tabletop-trainer/`.

## Install on iPhone

Open the link in **Safari**, tap **Share**, then **Add to Home Screen**. Train from the home-screen icon from then on: its progress is separate from Safari's, and it keeps working offline.

## Updating

Replace `index.html` with the new version, and change `VERSION` in `sw.js` (for example to `tt-v2`) so phones pick up the change. The app updates the next time it's opened with a connection.
