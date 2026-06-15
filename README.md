# SettleK GitHub Pages package

Upload this folder as the GitHub Pages site root.

- `index.html` is the page entry point.
- `assets/images/` contains the images that were provided in the ZIP and safely separated from the HTML.
- Tailwind, Lucide, Google Fonts, and images that were not present in the ZIP still use their original remote URLs.

Recommended GitHub Pages setup:
1. Put these files on the branch used for Pages, usually `main`.
2. In GitHub: Settings > Pages > Deploy from a branch.
3. Select the branch and `/root` or `/docs`, depending on where you place this folder.
