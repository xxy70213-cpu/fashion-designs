# Shirt Studio

A simple T-shirt design app. Pick a shirt color, add text, stickers and shapes, drag them into place, then download the design as a PNG.

No build step and no dependencies: it is one `index.html` file.

## Run locally

Open `index.html` in a browser.

## Upload to GitHub

```bash
cd tshirt-designer
git init
git add .
git commit -m "Add Shirt Studio app"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Publish as a website (GitHub Pages)

1. Open the repo on GitHub, then **Settings → Pages**.
2. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
3. After a minute the app is live at `https://<your-username>.github.io/<repo-name>/`.

## Sticker and image library

The app searches free online libraries, with no API key needed (internet required):

- **Stickers**: colorful emoji sets (Fluent, Noto, OpenMoji, Twemoji) via the [Iconify API](https://iconify.design).
- **Icons**: single-color icons you can recolor, also via Iconify.
- **Photos**: Creative Commons photos and illustrations (commercial use allowed) via [Openverse](https://openverse.org). Credits are shown when you select a photo and after download. Credit the authors if you publish or sell a design that uses them.
- **Mine**: upload your own images, drop them on the shirt, or paste them.
