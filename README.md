# Chuantai Yuan — Personal Website

Personal academic website: a static `index.html` + `home.css`, no build
step, no framework — deployed as-is via GitHub Pages.

The HTML/CSS structure is adapted from Haotian Zheng's personal website
template (used under the MIT License — see [`LICENSE`](LICENSE)). The
content, photo, and all biographical/CV data belong to Chuantai Yuan.

## Editing content

- **Name / affiliation / contact**: `<header class="profile" id="top">` in
  [`index.html`](index.html)
- **Photo**: `assets/img/headshot.svg` — replace with a real photo (update
  the `<img src>`/`width`/`height` in `index.html` to match)
- **Research introduction / biography**: the empty `<div class="intro">`
  inside the profile header — currently reserved but intentionally blank
  (see the `<!-- Future Research Introduction -->` comment); adding text
  there picks up the matching layout/typography automatically, no CSS
  changes needed
- **Research / Publications / Working Papers / Work in Progress**:
  `<section id="research">`
- **Teaching**: `<section id="teaching">`
- **Styling**: all in [`home.css`](home.css)

No `_config.yml`, no data files, no build — just edit the files directly
and push. GitHub Pages serves the repo as static files with no processing.

## Publishing changes

```
git add -A
git commit -m "Update site"
git push
```

The site updates at https://yctyctpop.github.io/ within a minute or two of
pushing to `main` — no CI build required.
