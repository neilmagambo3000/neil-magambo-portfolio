# Neil Magambo: personal site

One static page for SDR and BDR hiring managers at SaaS and AI companies. It is written like a social work progress note: S, what I said; O, what you can check; A, my read; P, the plan. Published with GitHub Pages from the root of this repository.

- No scripts, no analytics and no third-party requests. Each page sets a Content Security Policy that only allows files from this site.
- Fonts are self-hosted: Geist and a subset of Newsreader, both under the SIL Open Font License (see `assets/fonts/OFL.txt`).
- `404.html` sends old links from the earlier coursework version of this site (biography.html, projects.html and the others) to the new page.
- The earlier version, my CSC 310 Web Development coursework from Concordia College, is kept in the history at commit `e753176`.

## View it locally

Fonts do not load from `file://`, so serve the folder over HTTP, for example `python3 -m http.server 8000` in this folder, then open http://localhost:8000/.

## License

The site code (HTML and CSS) is under the MIT License; see `LICENSE`. The written content and the photo are © Neil Magambo, all rights reserved. The fonts keep their own license in `assets/fonts/OFL.txt`.
