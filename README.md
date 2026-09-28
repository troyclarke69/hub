# Hub

A single landing page for all of Troy Clarke's projects.

- **Edit content:** everything (profile, projects, links) lives in `projects.js`. Add a project by copying an entry.
- **Categories:** `AI`, `Data`, `.NET`, `Full-stack`, `Games`. `featured: true` highlights a card, `live:` adds a demo link.
- **Thumbnails:** off until screenshots exist. To add one, drop a 16:9 image in `screenshots/` and set `image: "screenshots/<name>.png"` on a featured project. If the image fails to load, the card shows the project's initials.
- **Résumé:** `Troy_Clarke_Resume.pdf`, linked from the header. Replace the file to update it.
- **Caching:** the page always loads a fresh `projects.js`, so edits show up without waiting on GitHub Pages' cache.
- **Tech tags and Tech stack:** each project's `tech` tags list the languages, frameworks and libraries from its dependency files. The Tech stack section below the grid is built from those tags, with how many projects use each, so editing `tech` updates both.
- **Theme:** follows the system light/dark setting; the header toggle overrides it and is remembered per browser.
- **No build step:** plain HTML + JS. Open `index.html` via any static server, or view it on GitHub Pages.
