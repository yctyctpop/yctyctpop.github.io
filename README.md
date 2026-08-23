# Chuantai Yuan — Personal Website

Personal academic website, built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll) and deployed via GitHub Pages.

## Editing content

- **About / bio**: [`_pages/about.md`](_pages/about.md)
- **CV**: [`_data/cv.yml`](_data/cv.yml) (rendered at `/cv/`) and the PDF at [`assets/pdf/cv.pdf`](assets/pdf/cv.pdf)
- **Publications**: [`_bibliography/papers.bib`](_bibliography/papers.bib) (BibTeX)
- **Projects**: add a new file to [`_projects/`](_projects/)
- **Teaching**: add a new file to [`_teachings/`](_teachings/)
- **Blog posts**: add a new file to [`_posts/`](_posts/)
- **News/announcements** (shown on the about page): add a new file to [`_news/`](_news/)
- **Profile photo**: replace `assets/img/prof_pic.jpg`
- **Site-wide settings** (title, socials, etc.): [`_config.yml`](_config.yml) and [`_data/socials.yml`](_data/socials.yml)

See [`docs/CUSTOMIZE.md`](docs/CUSTOMIZE.md) for full theme documentation.

Pushing to `main` automatically rebuilds and redeploys the site via GitHub Actions (see [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)).
