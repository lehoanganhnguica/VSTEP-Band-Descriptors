# VSTEP GitHub Pages deploy package

Upload the contents of this folder to the root of your GitHub repository:

- `index.html`
- `.nojekyll`
- `.github/workflows/pages.yml`

After pushing to the `main` branch, GitHub Actions will deploy the static site to GitHub Pages.

If your repository already has an older workflow, delete or replace it so it does not keep running deprecated `actions/checkout@v4` or `actions/upload-artifact@v4`.
