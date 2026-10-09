# Veda Nair — personal site

A single-page static site, hosted free on GitHub Pages. There's no build step: `index.html` is the whole site.

## Files
- `index.html`: the page (content, styles and the dot animation)
- `assets/`: photos and project images (add your own)
- `resume.pdf`: not added yet. Once a version without your phone number is uploaded, add "Resume" links back to the nav and contact section

## Adding images
- **Portrait:** `assets/veda.jpg` (480×480, location data removed). To change it, replace that file.
- **Project images:** in each project, replace `<div class="ph">…</div>` with `<img src="assets/your-image.jpg" alt="what the image shows">`. A 4:3 ratio fits best.

## Publish on GitHub Pages
1. Create a public repository named `<your-username>.github.io`.
2. Upload `index.html`, `resume.pdf` and the `assets/` folder to it.
3. In the repository, go to **Settings → Pages** and set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. The site goes live at `https://<your-username>.github.io` within a few minutes.
