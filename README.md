# LARC

The LARC website is a dependency-free static site for GitHub Pages.

## Local preview

Open `index.html` directly in a browser, or serve the repository with any static file server:

```bash
python -m http.server 8000
```

The published site is available at [larc-uwindsor.github.io/larc](https://larc-uwindsor.github.io/larc/).

## Publishing

Every push to `main` runs the workflow in `.github/workflows/pages.yml`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions** once, then future pushes deploy automatically.
