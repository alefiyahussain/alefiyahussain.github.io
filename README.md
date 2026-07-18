# alefiyahussain.github.io

Personal research website for Alefiya Hussain, built with [Quarto](https://quarto.org).

## Site Structure

| File / Directory | Description |
|---|---|
| `index.qmd` | Homepage / About |
| `research.qmd` | Research interests |
| `publications.qmd` | Publications list |
| `cv.qmd` | Curriculum Vitae |
| `posts/` | Blog posts |
| `styles/` | Custom CSS / SCSS |
| `images/` | Site images |
| `.github/workflows/` | GitHub Actions CI/CD |

## Local Development

1. [Install Quarto](https://quarto.org/docs/get-started/)
2. Clone this repo and run:

```bash
quarto preview
```

The site will open at `http://localhost:4200` with live reload.

## Deployment

Pushes to `main` automatically trigger the GitHub Actions workflow (`.github/workflows/publish.yml`), which renders the site and deploys it to GitHub Pages.

Make sure GitHub Pages is configured to use **GitHub Actions** as the source in your repository settings.
