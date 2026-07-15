# Evandro Harrison Hoffmann — Portfolio

A single-page portfolio site. Mobile & product engineer behind the apps at
**AirAsia**, **Mindvalley** and **LottieFiles** — and 50+ apps of my own on the
App Store through **MagicLab Solutions** and **EU App Solutions**.

**Live:** https://eharrison.github.io/portfolio/

## What's here

A hand-built, dependency-free `index.html` — no framework, no build step. It's an
editorial "issue of a magazine" treatment with:

- A dual **midnight / paper** theme that follows the viewer's light/dark preference
- A system-font typographic pairing — Hoefler Text · Helvetica Neue · SF Mono
- A filterable shelf of shipped apps, with live App Store links
- Scroll-reveal motion and hover micro-interactions (all `prefers-reduced-motion`-safe)

## Develop

Open `index.html` directly, or serve the folder:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy

GitHub Pages serves the **`gh-pages`** branch at the root. Push an updated
`index.html` there and Pages rebuilds automatically.
