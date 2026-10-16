# Mwila Hilton Mwaba: personal writing site

Built with [Quarto](https://quarto.org) and published to GitHub Pages.

## First-time publishing

1. Create a new GitHub repository (for example `writing`) and push this folder to its `main` branch.
2. In the repository, open Settings, then Pages, and set the source to **GitHub Actions**.
3. Push any change to `main`. The workflow in `.github/workflows/publish.yml` renders and deploys the site.
4. The site address is already set in `site-url` in `_quarto.yml`. Change it if you rename the repository.

## Everyday use

- Preview locally with `quarto preview`.
- Add an essay by creating a new `.qmd` file in `writing/` with `title`, `description`, `date` and `categories` in its header. It appears on the Writing page automatically.
- Keep a file private while drafting by adding `draft: true` to its header.
