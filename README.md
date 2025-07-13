# ExpertTech Consulting Website

This repository contains the static website for **ExpertTech Consulting LLC**. The site presents our AI consulting services and case studies for small and mid‑sized organizations.

Open `index.html` in a browser to view the site. Separate HTML files provide detailed case studies for each technology in our stack.

## Prerequisites

The project is entirely static. A modern web browser is sufficient to view the
pages. If you wish to install the optional JavaScript dependencies or run a
local development server, ensure [Node.js](https://nodejs.org/) (version 16 or
newer) and npm are available.

## Build steps

No build step is required. The HTML, CSS and JavaScript files under this
repository can be served directly. To install the optional dependencies run:

```bash
npm install
```

To preview the site with a local static server you can use one of the following
commands:

```bash
npx serve
# or
npx http-server
```

Then open the printed `http://localhost:` URL in your browser. You may also
simply open `index.html` directly from the filesystem.

## Images and logo

All image files reside in the `images` folder and are described in
`IMAGE_SHOPPING_LIST.md`. These are concept graphics created specifically for
this demo. The `logo.svg` file is a custom vector logo included in the
repository.

## External dependencies

The pages reference the following external resources:

- **Google Fonts** for the Montserrat and Roboto font families.
- **Font Awesome** (via the CDNJS link in `index.html`) for icon fonts.
