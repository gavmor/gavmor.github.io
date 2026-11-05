# gavmor.com

The homepage is built with mdsite and deployed to GitHub Pages from `main`. Edit `src/index.md` for the page, `src/style.css` for styling, and `template.html` for the shared shell. The blog is deployed separately at `/blog/`.

Run `npm ci && npm run build` to generate `dist/`, then `npm run serve` to preview at http://localhost:18766/. Keep `src/CNAME` in the build to preserve the custom domain.

The background simulation is adapted from [political-circus](https://github.com/benchristel/political-circus) and is disabled when reduced motion is requested.
