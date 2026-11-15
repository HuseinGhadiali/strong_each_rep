# Husein Ghadiali - coaching site

Static site: `index.html` plus the `assets/` folder. No build step.

## Publish on GitHub Pages
1. Create a public repository (name it `<your-username>.github.io` to serve from the root URL).
2. Upload `index.html` and the `assets` folder to the repository root.
3. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site is live at the URL GitHub shows after a minute or two.

## Things to edit later
- K11 certificate: in the Credentials section, replace the `<div class="cert">` course card with a `<button class="doc">` like the three above it, pointing at your certificate image, and change "In progress" in the list.
- Hero animation: the movements are defined in the `MOVES` list in `index.html` (name, reps, plates per side). Change a `plates` list to change the weights shown.
- Photos: swap any file in `assets/` for a new one with the same name.
- Contact: search `index.html` for `917887884566` and `husein2709@gmail.com`.
