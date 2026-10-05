# Steven Chen — a personal notebook

[Visit the website](https://stevenchenjy.github.io/)

A place for my research, essays, poetry, personal prose, and projects. Research entries distinguish published work from manuscripts and drafts. The writing collection includes an essay on politeness toward conversational AI, a poem and two short prose pieces from the Kenyon Review Young Writers Workshop, a creative writing program. Each piece has a short introduction to its form and subject, and the projects section links to my project repositories.

## Run locally

This is a static website built with HTML and CSS. It has no build step, visitor accounts, or analytics.

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. Edit `index.html` for the home page, `writing/` for the reading pages, and `style.css` for the layout. Fonts are self-hosted under `assets/fonts/` with their license files.

## Publishing

GitHub Pages serves the root of the `main` branch at `https://stevenchenjy.github.io/`. The `.nojekyll` file keeps the site as plain static files. Update canonical URLs, `robots.txt`, and `sitemap.xml` together if the domain changes.

## Content notes

Original literary prose is preserved. The two untitled workshop sketches have editorial titles and are identified as working drafts. The conference paper links to its DOI and public author manuscript. Private application documents and personal source notebooks are excluded from this repository.
