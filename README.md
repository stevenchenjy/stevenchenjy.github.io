# Steven Chen — a personal notebook

[Visit the website](https://stevenchenjy.github.io/)

A place for my research, essays, poetry, personal prose, projects, community work and interests. The opening portrait introduces me; Community shows meal preparation and food-scrap collection, and Interests brings together volleyball, fencing, hiking, soccer and a small art gallery. Select an artwork to open a larger, complete composition. Research entries identify publication venues, conference presentations and a policy-paper submission. The writing collection includes an essay on politeness toward conversational AI, a poem and two short prose pieces from the Kenyon Review Young Writers Workshop, a creative writing program. Each piece has consistent genre and topic labels, with dates, reading time and draft status shown separately. Section and entry titles follow a shared responsive type scale. Project descriptions explain their functions and link to the repositories.

## Run locally

This is a static website built with HTML and CSS. It has no build step, visitor accounts, or analytics.

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. Edit `index.html` for the home page, `writing/` for the reading pages, and `style.css` for the layout. Fonts are self-hosted under `assets/fonts/` with their license files.

## Publishing

GitHub Pages serves the root of the `main` branch at `https://stevenchenjy.github.io/`. The `.nojekyll` file keeps the site as plain static files. Update canonical URLs, `robots.txt`, and `sitemap.xml` together if the domain changes. After changing `style.css`, refresh its `v` query value in all five HTML stylesheet links so returning visitors receive the updated layout.

## Content notes

Original literary prose is preserved. The two untitled workshop sketches have editorial titles and are identified as working drafts. The ASME paper identifies the 2026 Design of Medical Devices Conference proceedings and links to its DOI and public author manuscript. The Duke Medical Robotics Symposium and Cornell Northeast Robotics Colloquium papers appear in the main research list with their presentation venues and author roles. The climate manuscript is submitted to International Review of Public Administration and under review. Its earlier submission to the NYC Mayor’s Office of Climate and Environmental Justice is recorded separately. The essay includes its 2026 John Locke Institute Global Essay Prize commendation and three original survey graphs beside the relevant discussion, with response totals, accessible descriptions and full-size image links. The graph assets are stored in `assets/essay/`; the original essay PDF remains available. Private application documents and personal source notebooks are excluded from this repository.

Photographs and artworks are authentic user-supplied images, stored as optimized, metadata-free WebP copies in `assets/photos/`. Original image proportions are preserved in the stored copies; art previews and larger images show the whole composition. The supplied fencing photograph uses a responsive portrait frame that keeps the foil tip, hands and feet visible. No generated portraits or artworks are used on the website.
