# ivan-instagram-media

Video files for published Reels, served over GitHub Pages so Instagram can fetch them.
One folder per post. Every file here was approved before it was pushed.

## What's here

- `20260916-the-film/` — the intro film, published 2026-09-14.
- `privacy/` — the Meta app's privacy policy page.
- `jarvis/` — the page a "comment JARVIS" reply links to: `index.html`, its one image `hero.jpg`, and the free PDF `what-i-learned-building-with-ai.pdf`.

## Naming going forward

The intro is named by its publish date because that was before this
convention existed; kept as-is because
`ivan-instagram/posted/20260916-the-film/PUBLISHED.json` records this exact
path as what Instagram fetched, and renaming it would break that record.
Every episode from here on gets its own folder named `episode-1`,
`episode-2`, ... in publish order, matching its id in `ivan-instagram`.
