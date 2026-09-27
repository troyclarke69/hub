# Hub

A single landing page for all of Troy Clarke's projects.

- **Edit content:** everything (profile, projects, links) lives in `projects.js`. Add a project by copying an entry.
- **Categories:** `AI`, `Data`, `.NET`, `Full-stack`, `Games`. `featured: true` highlights a card, `archive: true` moves it to "Earlier work", `live:` adds a demo link.
- **Thumbnails:** featured cards show a screenshot. Drop a 16:9 image in `screenshots/` and set `image: "screenshots/<name>.png"`; otherwise the card uses the repo's GitHub social preview, falling back to the project's initials.
- **Theme:** follows the system light/dark setting; the header toggle overrides it and is remembered per browser.
- **No build step:** plain HTML + JS. Open `index.html` via any static server, or view it on GitHub Pages.
