# CAISE-style site scaffold

This repository contains a minimal scaffold for a conference website inspired by https://caise26.polimi.it/ and styled using the provided EPS artwork.

Quick start

1. Place the EPS file you provided into `assets/` (create the folder) as `caise-style.eps`.
2. Convert the EPS to SVG or PNG for web use. Example with Inkscape:

```bash
inkscape assets/caise-style.eps --export-type=svg --export-filename=assets/caise-style.svg
```

3. Serve the site locally (Python):

```bash
python -m http.server 8000
# then open http://localhost:8000/
```

Notes

- The `css/styles.css` file is an approximation of the EPS visual style. For pixel-accurate results, convert the EPS to SVG and extract colors/typography from the artwork.
- If you want, I can convert the EPS to SVG here (requires the EPS file in the workspace). Tell me if you want me to proceed.
