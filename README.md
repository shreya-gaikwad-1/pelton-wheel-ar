# Pelton Wheel in 3D and AR

Static website using Google's `<model-viewer>`. No server, no build step.

```
pelton-wheel-ar/
├── index.html            web page (3D viewer, animation buttons, facts)
├── ar/index.html         AR page ("View in your room")
├── models/pelton_wheel.glb
└── qr/qr-ar.png, qr-web.png
```

## Publish free on GitHub Pages

1. On github.com (logged in as `shreya-gaikwad-1`), click **New repository**.
2. Name it exactly `pelton-wheel-ar`, set it to **Public**, and create it.
3. Click **uploading an existing file**, drag in everything from this folder (keep the `ar`, `models` and `qr` folders), and commit.
4. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, and save.
5. After 1 to 2 minutes the site is live at:
   - Web: https://shreya-gaikwad-1.github.io/pelton-wheel-ar/
   - AR: https://shreya-gaikwad-1.github.io/pelton-wheel-ar/ar/
6. Scan `qr/qr-ar.png` and `qr/qr-web.png` with your phone camera to test.

If you use a different repository name, the QR codes must be regenerated with the new URLs.

## Before submitting

- Add the 3D model's author and licence in the footer of `index.html` if it came from Sketchfab or another source.
- AR needs HTTPS (GitHub Pages provides it) and a supported phone.
