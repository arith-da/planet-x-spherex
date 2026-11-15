# Planet X and SPHEREx — A Public Blink Tool to Search for Planet X

**Team THE SCARERS — NASA Space Apps Challenge 2026**

Could a giant planet still hide beyond Neptune? This free public web tool lets anyone join the search using data from NASA's SPHEREx mission.

**Live demo:** https://arith-da.github.io/planet-x-spherex/
**Presentation (6 slides):** https://github.com/arith-da/planet-x-spherex/blob/main/planet-x-spherex-presentation-5-minutes.pptx

## What it does

- **Blink comparator** — blink between real sky photos from the 1950s (DSS) and the 1980s–90s (DSS2 Red/Blue) from NASA SkyView to spot what moved. Blink, mix, difference and side-by-side modes.
- **Visible-change demo** — Barnard's star, the fastest-moving star in the sky, jumps clearly between epochs.
- **Simple searcher** — pick a region (Cetus, Orion's Belt, Pleiades, Galactic Center, Andromeda, Barnard's star) with no astronomy knowledge needed.
- **Advanced searcher** — enter coordinates (with a guide and an hours/minutes/seconds-to-degrees converter) and build the real SIA2 query against the SPHEREx archive at IRSA.
- **All-sky viewer** — embedded Aladin Lite viewer (CDS) that follows the chosen region.
- **Candidates** — save, share and export candidate lists as CSV or JSON. Preloaded with the published Phan et al. 2025 candidate (unconfirmed).

## The search region

Default region: **Cetus, RA 02h 30m (37.5°), Dec −15°** — in the broad southern ecliptic band left open by current models (Holman & Payne, from Cassini data, crossed with Batygin & Brown dynamics).

## Honest limits

- A cold Planet Nine would peak thermally far outside SPHEREx's range (≤5.0 µm). SPHEREx helps through repeated all-sky coverage: a planet should move 1.5–5 arcminutes between six-month surveys.
- Two epochs do not fix an orbit — a third epoch is needed for any real follow-up.
- SPHEREx images are FITS files at IRSA; the tool links the official IRSA query and cutout service. The IRSA query server is intermittent and may return a proxy error; the page says so and offers working alternatives.
- We do not claim a discovery. This is a tool so anyone can take part in the search.

## Data sources

- NASA SkyView (DSS, DSS2) — real sky photos
- NASA/IPAC IRSA — SPHEREx data archive (DR1, released 12 November 2026)
- CDS Aladin Lite — all-sky viewer (DSS, 2MASS, AllWISE surveys)
- Gaia archive — reference for known stars
- AWS S3 (nasa-irsa-spherex) — public mirror of SPHEREx files

## Team — THE SCARERS

- Erick Arith Dominguez Acosta — team owner, general coordinator and pitch presenter
- Emir Cruz Ramos — GitHub and publication
- Gerardo Cruz Ramos — data and verification
- Andrea Martinez Pineda — user experience and testing
- Aaron Zaid Grajeda Diaz — documentation
- Fernando Martinez Gonzales — demo video and presentation

## Built with AI assistance

Claude (Anthropic) for code, testing and text, and Muse (Meta) as team mentor — coordination, page construction, GitHub upload and delivery preparation. All science claims were checked against the official challenge statement and SPHEREx/IRSA sources, and all images and data are real, from NASA SkyView, IRSA and CDS.

## License

MIT — open source, free for everyone.
