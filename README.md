# richyo-codes.github.io

A small landing page for Richard Young's browser apps. Plain HTML and CSS, with no build step, dependencies, or tracking scripts.

## Preview locally

Run `python3 -m http.server 4588 --bind 127.0.0.1` from this directory and open http://localhost:4588.

## Publish

Create the public GitHub repository `richyo-codes/richyo-codes.github.io`, push this repository's `main` branch, then choose **Settings → Pages → Deploy from a branch → main → / (root)**.

The site will live at https://richyo-codes.github.io/. This is separate from the `richyo-codes/richyo-codes` profile README repository. Each linked app keeps its existing project repository and Pages deployment.

## Edit

Update app links and descriptions in `index.html`; change presentation in `styles.css`. The page follows the visitor's light or dark system preference. No custom domain is configured.
