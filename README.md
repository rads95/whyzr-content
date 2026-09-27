# whyzr content

`world-editions.json` is the online feed for **What in the World**. The app downloads it on launch, so a new edition goes live without an app update.

Each entry is one edition: `{id, published: "YYYY-MM-DD", title, games: [5 games]}`, the same shape as `dist/world-editions.js` in the app repo. An entry with the same `published` date as a built-in edition replaces it (use that for corrections).
