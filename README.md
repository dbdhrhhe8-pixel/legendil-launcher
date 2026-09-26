# LegendIL Launcher website

Static site for GitHub Pages. English by default, Hebrew via the עב button (or `?lang=he`). The choice is remembered.

## Download link settings

Already set for the `dbdhrhhe8-pixel/legendil-launcher` repository. To change it, edit the settings block near the bottom of `index.html`:

```js
const GITHUB_USER = 'dbdhrhhe8-pixel';   // your GitHub username
const GITHUB_REPO = 'legendil-launcher';  // the repository that has the Release
const DOWNLOAD_FILE = 'LegendIL-Launcher-Setup.exe';
```

Every Download button then points to the latest Release, and the version and size are read from GitHub automatically.

## Publish on GitHub Pages

1. Upload all files in this folder (including `assets/` and `.nojekyll`) to the root of the `legendil-launcher` repository.
2. Repository → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
3. After about a minute the site is live at `https://dbdhrhhe8-pixel.github.io/legendil-launcher/`.

## Updating screenshots

Replace the files in `assets/` with the same names (`shot-home.webp`, `shot-instances.webp`, `shot-content.webp`, `shot-skins.webp`).
