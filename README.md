# Neil Magambo: personal portfolio

My personal portfolio website. I first built it in PHP as coursework for CSC 310 Web Development at Concordia College (Fall 2025). This repository holds a static HTML version of that site so it can be hosted for free on GitHub Pages.

## How this version was made

- Each PHP page became a plain HTML page with the same structure, text and stylesheet. The shared header and footer and the project data file became repeated HTML, and the project detail page (project.php?id=N) became project-1.html to project-3.html.
- Nothing runs on a server. The original contact form is replaced with a link to my LinkedIn profile.
- Differences from the PHP version: education shows my May 2026 graduation; team project descriptions say exactly what my part was; the résumé PDF is not included.
- No scripts, no external fonts, no analytics and no third-party requests. Every page sets a Content Security Policy that only allows local files.

## View it

Open index.html in a browser. No build step or server is needed.

## License

The site code (HTML structure and CSS) is under the MIT License; see LICENSE. The written content and the photo are © Neil Magambo, all rights reserved.
