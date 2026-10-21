# Sophanna Sun — Developer Portfolio

A responsive React portfolio built with Vite. Dark editorial styling, an animated wireframe sphere, project filtering, accessible project dialogs, scroll reveals, mobile navigation, and email copy interaction. Respects reduced-motion preferences.

## Development

- `npm ci`
- `npm run dev`
- `npm run build` creates `dist/`
- `npm run preview` previews the production build

## Personalize

Edit `src/main.jsx` for biography, contact information, GitHub links, and the `projects` array. Project examples are clearly labeled concept studies, not client projects. Replace them with real project descriptions and links when available. Styles live in `src/styles.css`.

## Hosting

GitHub Actions builds and deploys `dist/` on pushes to `main`. Vite's base path is `/test-tools/`, matching the repository. Update `vite.config.js` if the repository or hosting path changes.

Live: https://sun-sophanna.github.io/test-tools/

Google Fonts is optional; the page includes system font fallbacks.
