# Hytale Prefab Viewer

A browser-based viewer for Hytale `.prefab.json` files.

## Use

Open the website, choose a local Hytale `Assets.zip` (or an extracted assets folder) under **Resources**, then open or drop a `.prefab.json` file.

The interface uses Russian when the browser's preferred language is Russian and English otherwise.

## Notes

- The app is static; no build step or backend is required.
- Three.js, OrbitControls, and zip.js are included in the repository. The viewer does not need an external CDN.
- Prefab files and game assets are read locally in the browser and are not uploaded by the app.
- If the client assets archive lacks server-side block definitions, use a server assets archive or an extracted resource folder.
- Entities and fluids are not rendered; custom block models are shown in their rest pose.

## Deployment

GitHub Actions deploys the contents of the `main` branch to GitHub Pages on every push.
