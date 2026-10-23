# Spark Grid — Public Support & Privacy Site

Static HTML/CSS site for Spark Grid **Support** and **Privacy Policy** pages (Apple App Store and Google Play).

**Status:** Published on GitHub Pages from this repository.

## Live URLs

- Home: https://emrahcaliskann.github.io/spark-grid-pages/
- Support: https://emrahcaliskann.github.io/spark-grid-pages/support/
- Privacy Policy: https://emrahcaliskann.github.io/spark-grid-pages/privacy/

## Contents

| Path | Purpose |
| --- | --- |
| `index.html` | Landing page |
| `support/index.html` | Support |
| `privacy/index.html` | Privacy Policy |
| `styles.css` | Shared responsive styles |
| `assets/icon.png` | Official Spark Grid icon (copied from the game branding asset; design unchanged) |
| `.nojekyll` | Ensures GitHub Pages serves files without Jekyll processing |

No external libraries, analytics, cookies, Google Fonts, scripts, trackers, or backend.

## Publisher and contact

- Publisher: Emrah Caliskan
- Public support / privacy email: `caliskanemrah@gmail.com`

## Local preview

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080/`.

Relative links are written for a GitHub Pages **project site** subpath (`/spark-grid-pages/`).

## GitHub Pages

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Store listing fields

- Support URL: `https://emrahcaliskann.github.io/spark-grid-pages/support/`
- Privacy Policy URL: `https://emrahcaliskann.github.io/spark-grid-pages/privacy/`

## Relationship to the game repository

This site lives **outside** the `spark-grid` application repository. Do not merge these files into the game app source tree unless a separate, approved issue says so.
