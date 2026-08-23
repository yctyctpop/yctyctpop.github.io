# Chuantai Yuan — Personal Website

Personal academic website. A single static HTML page, no build step, no
framework — deployed as-is via GitHub Pages.

## Editing content

Everything is in [`index.html`](index.html):

- **Intro / bio / contact**: top of `<body>`, inside `.intro`
- **Photo**: `assets/img/headshot.svg` — replace with a real photo (e.g.
  `assets/img/headshot.jpg`) and update the `<img src>` in `index.html`
- **CV**: `assets/pdf/cv.pdf` — replace with your real CV PDF (same filename,
  or update the link in the nav)
- **Research / Publications / Working Papers**: `<section id="research">`
- **Teaching**: `<section id="teaching">`

No `_config.yml`, no data files, no build — just edit the HTML directly and
push. GitHub Pages serves the repo as static files with no processing.

## Publishing changes

```
git add -A
git commit -m "Update site"
git push
```

The site updates at https://yctyctpop.github.io/ within a minute or two of
pushing to `main` — no CI build required.
