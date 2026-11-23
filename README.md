# Student Laptop Finder

Responsive laptop catalogue built with vanilla JavaScript (ES modules) and Tailwind CSS 4.

## Install and build
```bash
npm install
npm run build     # creates dist/output.css
npm run watch     # rebuilds while you edit
```
Then open the project with a local server (VS Code Live Server) and start from `index.html`.
`fetch()` does not work when pages are opened directly as files.

## Structure
- `src/input.css` - Tailwind 4 setup, `@theme` colors, plugins, component classes
- `src/js/` - `api.js`, `storage.js`, `ui.js`, `compare.js` + one file per page
- `data/laptops.json` - 22 laptops
- `assets/` - laptop images

GitHub repo: https://github.com/YOUR-USERNAME/YOUR-REPO
