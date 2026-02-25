# AGENTS.md

## Overview

This is a static personal academic portfolio website for Jayten (Juntao) Wang. It consists of a single HTML page (`index.html`), one CSS file (`css/main.css`), and one JS file (`js/main.js`). All third-party libraries (jQuery, Bootstrap 4, Font Awesome, Fancybox) are loaded from CDNs at runtime — there are no local dependencies to install.

## Cursor Cloud specific instructions

### Running the site

Serve the site with any static file server from the repository root:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in a browser.

### No build step / no package manager

There is no `package.json`, no build tool, no linting configuration, and no automated tests. The codebase is pure static HTML/CSS/JS.

### CDN dependency

The page requires internet access to load jQuery, Bootstrap, Font Awesome, Fancybox, and Google Fonts from CDNs. Without internet, the page will render without styling or interactivity.

### Hidden sections

Some sections (Activity, Portfolio, Google Map) have `class="hide"` (`display: none`) and are intentionally hidden. Do not treat this as a bug.
