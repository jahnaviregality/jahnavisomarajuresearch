# Signals in the System — Research Exhibition

This folder contains a self-contained digital exhibition built from the supplied `published research papers.pdf`.

## View it

Open `index.html` in a modern browser. It links to 15 independent HTML pages; each page contains its own CSS, JavaScript, and inline SVG, so the collection can be copied or presented without a build step or external assets.

For a local presentation server, run `python -m http.server 8000` from this folder and open `http://localhost:8000`.

## Contents

- `index.html` — central portfolio and paper directory.
- One `<slug>.html` file per distinct paper.
- `paper-inventory.md` — source-grounded working inventory.
- `published research papers.pdf` — supplied source retained in its original attachment location; the generated pages do not embed it.

## Evidence and interpretation

The exhibition distinguishes source-stated material from design interpretation. Missing DOI, URL, author, affiliation, or results fields are labeled unavailable. Where a paper itself labels results as illustrative, simulated, planned, or case-study-only, the page preserves that boundary.
