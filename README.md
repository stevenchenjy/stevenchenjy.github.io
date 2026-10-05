# Steven Chen — a personal notebook

[Visit the website](https://stevenchenjy.github.io/)

A place for my research, essays, poetry, personal prose, and projects. Research entries identify publication venues, conference presentations and a policy-paper submission. The writing collection includes an essay on politeness toward conversational AI, a poem and two short prose pieces from the Kenyon Review Young Writers Workshop, a creative writing program. Each piece has a short introduction to its form and subject, and the projects section links to my project repositories.

## Run locally

This is a static website built with HTML and CSS. It has no build step, visitor accounts, or analytics.

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. Edit `index.html` for the home page, `writing/` for the reading pages, and `style.css` for the layout. Fonts are self-hosted under `assets/fonts/` with their license files.

## Publishing

GitHub Pages serves the root of the `main` branch at `https://stevenchenjy.github.io/`. The `.nojekyll` file keeps the site as plain static files. Update canonical URLs, `robots.txt`, and `sitemap.xml` together if the domain changes. After changing `style.css`, refresh its `v` query value in all five HTML stylesheet links so returning visitors receive the updated layout.

## Content notes

Original literary prose is preserved. The two untitled workshop sketches have editorial titles and are identified as working drafts. The ASME paper identifies the 2026 Design of Medical Devices Conference proceedings and links to its DOI and public author manuscript. The Duke Medical Robotics Symposium and Cornell Northeast Robotics Colloquium papers appear in the main research list with their presentation venues and author roles. The climate manuscript identifies its submission to the NYC Mayor’s Office of Climate and Environmental Justice. The essay includes its 2026 John Locke Institute Global Essay Prize commendation. Private application documents and personal source notebooks are excluded from this repository.
