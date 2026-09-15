# DAN 1025 - Dance Appreciation site

Simple Markdown site, ready for GitHub Pages.

## How to publish

1. Create a new repository on GitHub (e.g. `dan1025`).
2. Upload all the files in this folder to the repo (keep the `modules/` folder structure and `_config.yml` at the root).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)`.
5. Save. GitHub will build the site (takes a minute or two) and give you a link like `https://yourusername.github.io/dan1025/`.

That's it — no build step needed, GitHub Pages renders the Markdown automatically using the Jekyll `minimal` theme set in `_config.yml`.

## Structure
- `index.md` — homepage with links to every unit/module
- `syllabus.md` — course syllabus
- `sources.md` — full source list by unit
- `modules/` — one page per Sway module, each with its sources + a summary
