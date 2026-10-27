# Steven Chen — a personal notebook

[Visit the website](https://stevenchenjy.github.io/)

A place for my research, essays, poetry, personal prose, projects, community work and interests. The opening portrait introduces me; Community shows meal preparation, food-scrap collection, mindfulness sessions in Newburgh, and online mindfulness and English mentoring for children in China, and Interests brings together volleyball, fencing, hiking, soccer and a small art gallery. Select an artwork to open a larger, complete composition. Research entries identify publication venues, conference presentations and a policy-paper submission. The writing collection includes an essay on politeness toward conversational AI, a poem and two short prose pieces from the Kenyon Review Young Writers Workshop, a creative writing program. Each piece has consistent genre and topic labels, with dates, reading time and draft status shown separately. Section and entry titles follow a shared responsive type scale. Project descriptions explain their functions and link to the repositories.

## Run locally

This is a static website built with HTML and CSS. It has no build step, visitor accounts, or analytics.

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. Edit `index.html` for the home page, `writing/` for the reading pages, and `style.css` for the layout. Fonts are self-hosted under `assets/fonts/` with their license files.

## Publishing

GitHub Pages serves the root of the `main` branch at `https://stevenchenjy.github.io/`. The `.nojekyll` file keeps the site as plain static files. Update canonical URLs, `robots.txt`, and `sitemap.xml` together if the domain changes. After changing `style.css`, refresh its `v` query value in all five HTML stylesheet links so returning visitors receive the updated layout.

## Content notes

Original literary prose is preserved. The two untitled workshop sketches have editorial titles and are identified as working drafts. The ASME paper identifies the 2026 Design of Medical Devices Conference proceedings and links to its DOI as a peer-reviewed publication, a site-hosted author-manuscript PDF and the official 2026 Design of Medical Devices Conference page at the University of Minnesota. The Duke paper has a site-hosted PDF and identifies its in-person presentation. The Duke Medical Robotics Symposium and Cornell Northeast Robotics Colloquium papers appear in the main research list with their presentation venues and author roles. The climate manuscript is submitted to International Review of Public Administration and under review. Its earlier submission to the NYC Mayor’s Office of Climate and Environmental Justice is recorded separately. The essay includes its 2026 John Locke Institute Global Essay Prize commendation and three original survey graphs beside the relevant discussion, with response totals, accessible descriptions and full-size image links. The graph assets are stored in `assets/essay/`; the original essay PDF remains available. The occupancy entry uses a plain-language project title and identifies first-author research. It describes Junyu’s confirmed research role with guidance from Prof. Chong Li, links separately to the project overview, author-manuscript PDF, and code and results, and retains the offline study scope. The project overview preserves the formal manuscript title and citation metadata. Its existing local PDF matches the preserved authored manuscript; the public record date is October 14, 2026, and a prospective evaluation is still required. The matching Projects entry links back to the paper and research record. Private application documents and personal source notebooks are excluded from this repository.

Photographs and artworks are authentic user-supplied images, stored as optimized, metadata-free WebP copies in `assets/photos/`. Original image proportions are preserved in the stored copies; art previews and larger images show the whole composition. The supplied fencing photograph uses a responsive portrait frame that keeps the foil tip, hands and feet visible. No generated portraits or artworks are used on the website.

## Project impact figures

The Projects section combines author-reported outcomes with explicitly labeled calculations.

- **Soup kitchen:** Junyu reported approximately 60% less food waste on October 27, 2026, with a typical service preparing 200 meals for 150 guests and two services per week. The two-year projection is `(200 - 150) × 2 × 104 = 10,400` baseline surplus meal equivalents; applying 60% gives `6,240` fewer surplus meals, displayed as about 6,200. An assumed `0.5 kg` per meal gives `3,120 kg`, or about `3.1 metric tons`. The service counts, reduction, and consistent schedule are author-provided approximations; the food weight is an illustrative assumption. These are projected meal equivalents rather than a weighed two-year disposal total. The repository's separate [retrospective preparation-policy evaluation](https://github.com/stevenchenjy/soup-kitchen-forecast/blob/main/docs/meal_preparation_policy.md) reports model-based potential excess and shortfall, a different evidence source from the author's operational estimate.
- **Occupancy forecasting:** The saved primary hybrid identifies `490.1463795265 kWh` of processed HVAC-plus-lighting load during recommended intervals with empty camera labels. Across the same 43 non-overlapping policy horizons, total processed HVAC-plus-lighting load is `11,947.4138311572 kWh`, giving `4.102531%`, displayed as about 4.1%. The denominator uses the same target times and `max(hvac_S + lig_S, 0) × 0.25 h` convention as [the analysis](https://github.com/stevenchenjy/decision-aware-occupancy-forecasting/blob/main/src/hybrid_analysis.py). This is identified load opportunity, not a measured or validated energy-saving percentage. The underlying data are from LBNL Building 59.
- **NHS portal:** The 50 active users were confirmed by Junyu on October 27, 2026. Two-stage review, final teacher approval, bulk approval, separate approved/pending progress, capacity-limited event sign-ups, deadlines, and waitlists are documented in the [portal repository](https://github.com/stevenchenjy/SKS-NHS-Hours) and [administrator guide](https://github.com/stevenchenjy/SKS-NHS-Hours/blob/main/docs/ADMIN_GUIDE.md).

The Community mindfulness entries use the two activity images supplied October 27, 2026. They are stored as lossless WebP files at their original dimensions with identical RGBA pixels. Descriptions and captions are brief; the separate outreach-summary screenshot is background context and is not published.
