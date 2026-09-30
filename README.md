# ivan-instagram-media

Video files for published Reels, served over GitHub Pages so Instagram can fetch them.
One folder per post. Every file here was approved before it was pushed.

## What's here

- `20260916-the-film/` — the intro film, published 2026-09-14.
- `e1-the-bills/` — Episode 1, published 2026-09-30.
- `privacy/` — the Meta app's privacy policy page.
- `jarvis/` — the first reply page: `index.html`, its one image `hero.jpg`, and the free PDF `what-i-learned-building-with-ai.pdf`. Kept up for links already sent in DMs.
- `brain/` — the page a "comment BRAIN" or "comment JARVIS" reply links to: five questions, what a brain would build first, and a message to send in DM. `index.html` and its one image `hero.jpg`. No price, ever.

## Naming going forward

The intro is named by its publish date because that was before this
convention existed; kept as-is because
`ivan-instagram/posted/20260916-the-film/PUBLISHED.json` records this exact
path as what Instagram fetched, and renaming it would break that record.
Every episode from here on gets its own folder named by its id in
`ivan-instagram`, the name the publish script uses: `e1-the-bills/` is
Episode 1, published 2026-09-30.
