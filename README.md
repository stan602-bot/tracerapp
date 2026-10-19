# Wee Ghost Tracer 👻

A standalone camera-overlay tracing app for iPhone, iPad and Android, completely independent of Studio 2 and StudioSuitePro.

## Launch the app

After GitHub Pages is enabled, open **https://stan602-bot.github.io/tracerapp/** in Safari (iPhone/iPad) or Chrome (Android). Allow camera access, select Back or Front, drag/pinch/rotate the pattern to align it over the real ornament, change its transparency and lock the overlay.

To add to the iPhone/iPad Home Screen, open in Safari → Share → **Add to Home Screen**. On Android, use Chrome's menu → **Install app** / **Add to Home Screen**.

## Publishing with GitHub Pages

In this repository choose **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**. On GitHub Free the repository needs to be **Public**; change it under **Settings → General → Danger Zone → Change repository visibility** first. Changes can take several minutes to appear. This page is available over HTTPS, required for browser camera access.

## What it does

- Original, individually spaced front/back ghost artwork is bundled in `index.html` and also provided as separate transparent PNGs.
- Live camera, front/back camera switch, freeze, and optional uploaded-photo mode.
- Drag/pinch/rotate, outline/filled mode, transparency and colour controls, lock/reset.
- Save an overlaid snapshot and download the original pattern.
- Runs in Safari or Chrome as a static progressive web app; no paid developer account or server-side processing needed.

**Limitations:** This is a manual camera overlay, not automatic 3D tracked AR. Keep the phone and ornament still while tracing. Camera permission is requested locally by your browser; the app has no remote camera upload. GitHub Pages is static hosting and cannot itself operate the phone camera; the browser supplies it via HTTPS.
