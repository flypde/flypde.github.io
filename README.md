# GitHub Pages Personal Homepage

This is a simple English one-page personal homepage designed for GitHub Pages.
It is fully static: no backend, no build step, no database, and no paid service.

## Files

- `index.html` - page content and structure
- `styles.css` - responsive layout, visual style, and light/dark theme
- `script.js` - theme toggle and copy-email interaction
- `assets/profile.svg` - replaceable profile placeholder image
- `.nojekyll` - tells GitHub Pages to serve the files directly

## Customize

Search and replace these placeholders:

- `Your Name`
- `your.email@example.com`
- `Your City`
- `Project One`, `Project Two`, `Project Three`
- Footer links for GitHub, LinkedIn, Blog, and Resume/CV

If you have a personal photo, place it in `assets/` and replace
`assets/profile.svg` in `index.html` with your image path.

## Deploy to GitHub Pages

1. Create a public GitHub repository named `<github-username>.github.io`.
2. Upload or push all files in this folder to the `main` branch.
3. Open the repository on GitHub and go to `Settings > Pages`.
4. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
5. Choose branch `main` and folder `/root`.
6. Wait a few minutes, then open `https://<github-username>.github.io`.

This v1 assumes no custom domain. You can add one later from the same
`Settings > Pages` screen.
