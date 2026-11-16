# Atomic Structure Explorer

A single-file teaching app (`index.html`) that helps students learn electron arrangement for elements 1–20.

- **Explorer:** electronic arrangement diagrams (dot or cross), nuclide and periodic table notation, period and group.
- **Build:** drag electrons onto the shells (mouse or touch, works on Chromebooks and phones).
- **Arcade:** Atom Doctor, Mystery Element and Blitz games.
- **Periodic table:** booklet-style table with size slider; elements 21–118 are greyed out as not assessed.
- Layout switches automatically between wide (Chromebook) and tall (phone).

No build step, no dependencies, no API keys. Progress is stored in each student's browser only (`localStorage`).

## Deploy

Drag `index.html` into Netlify, or connect this repository to a Netlify site (publish directory: the repository root; no build command).
