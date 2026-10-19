# Trace Studio

A general-purpose tracing camera app for iPhone, iPad and Android. This repository is independent of Studio 2 and StudioSuitePro.

## Features

- **Blank workspace by default** – the camera works without selecting any design.
- **My picture** – upload an image to overlay, resize, rotate and adjust transparency.
- **Trace lines** – create a simple line-style overlay from an uploaded drawing or photo. Or show the original image.
- **Templates** – choose from the optional Wee Ghost back/front templates included as examples. The app is not restricted to ghosts.
- **My saved templates** – save uploaded pictures to the browser's local IndexedDB for reuse on this device. They are not uploaded to GitHub or synced between devices. Clearing site data or private browsing may remove saved templates.
- **Camera tools** – live camera, front/back camera, freeze view, overlay lock, photo-background mode, screenshots and downloadable patterns.
- **Home Screen install** – GitHub Pages serves a Progressive Web App (PWA), with a separate generic icon and offline assets.

## GitHub Pages setup

GitHub repository owner: `stan602-bot`. Public URL (once GitHub Pages has been enabled): **https://stan602-bot.github.io/tracerapp/**

For GitHub Free, change repository visibility to **Public** in **Settings → General → Danger Zone**. In **Settings → Pages**, configure **Deploy from a branch**, choose **main** and **/(root)**, then Save. Wait for the Pages deployment to finish.

On iPhone/iPad open the published HTTPS URL in Safari, grant camera access, then tap **Share → Add to Home Screen**. On Android open the URL in Chrome and select **Install app** or **Add to Home Screen**.

## Privacy and practical limitations

The camera stream stays on the phone; it is processed inside the browser. Saved custom templates are stored locally in that device's browser, not in GitHub. The default front/back demo ghost patterns are published as repository assets. This is a manually aligned 2D camera overlay, **not** tracked 3D augmented reality. Keep the phone stationary while painting or tracing; the device screen does not physically project artwork onto an object.
