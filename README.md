# Lot Envelope Studio

Enter a lot (frontage, depth, interior or corner, wide or narrow streets), pick an NYC zoning district and a floor area ratio, and see the allowed 3D envelope with floors stacked up to the FAR after rear yards, lot coverage, setbacks and height limits.

It is a single static page (`index.html`) using Three.js from a CDN, so there is no build step. GitHub Pages serves it straight from the repository root.

**Caveat:** the district values are approximate and simplified. Many changed with the 2024 City of Yes amendments. Every rule is editable in the page; check them against the current NYC Zoning Resolution and ZoLa before relying on the output.

Not modelled: open space ratio, towers, street wall location rules, through lots, special districts, and gross vs. zoning floor area.
