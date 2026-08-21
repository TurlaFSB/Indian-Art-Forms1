# Indian Art Through Time — Final Project

Student: Pranav Verma
Registration Number: RA2411030010008
Department: NWC
Assignment: Interactive Timeline with Artifacts (10 Marks) — CO1

## Files

- `index.html` — semantic page structure
- `style.css` — premium editorial / museum visual system
- `script.js` — unified historical content + rendering + GSAP/ScrollTrigger/Lenis interactions
- `assets/images/` — local archival fallback artwork plates

## Run

Open `index.html` in a modern browser.

For best behavior, use a local server (VS Code Live Server, Python `http.server`, etc.).

The site works without the external animation libraries too: if GSAP/Lenis cannot load,
the page falls back to native scrolling and CSS transitions.

## Images

Primary historical artwork URLs are retained from the supplied research dataset.
Each artwork has a local SVG archival fallback, so the browser will never show a broken-image icon
if an external image cannot be fetched.

## Academic content

The historical dataset is retained from the supplied detailed `script_detailed_high_quality.js`.
The obsolete legacy renderer was removed and replaced with the current cinematic renderer; the
research content itself was not intentionally shortened.
