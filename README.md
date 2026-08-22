# Toluwalase Writer

![HTML](https://img.shields.io/badge/HTML-Static%20Page-orange)

## Table of Contents
- [About](#about)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Authors and License](#authors-and-license)

## About

A single-page static author website for "Toluwalase Famade", a Christian fiction writer. The page (`index.html`) is a self-contained HTML file with an embedded `<style>` block and inline JavaScript — there is no build step, framework, or backend. It presents a hero section, a "Bibliography" grid of three placeholder book entries (The Redemption of Olasumbo, Shadows of the Altar, Faith in the Valley), an "About/The Journey" testimony section, and a newsletter sign-up form. Styling is done with the Tailwind CDN (`https://cdn.tailwindcss.com`) plus Google Fonts (Cormorant Garamond, Playfair Display, Great Vibes) loaded over the network. The book cover images are text placeholders (no actual cover art files are present), and the newsletter form only fakes a "Thank you" button state client-side — it does not submit anywhere. This is a template/demo site for the author, not a fully populated production site.

## Prerequisites

None beyond a modern web browser. An internet connection is required at view-time because Tailwind CSS and the Google Fonts are pulled from CDNs rather than bundled locally.

## Installation

```bash
git clone https://github.com/successjoseph/Toluwalase-Writer.git
cd Toluwalase-Writer
```

No dependency installation is needed — there is no `package.json` or build tooling in the repository.

## Configuration

There is no external configuration, environment file, or backend to set up. All content (book titles, blurbs, testimony text) is hardcoded directly in `index.html`.

## Usage

Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:
```bash
python -m http.server 8000
```
then visit `http://localhost:8000`.

## Testing

No automated tests are currently included.

## Contributing

This is a personal/client site for one author; it is not set up to accept outside contributions. Notes above are for future-you when revisiting the code.

## Authors and License

- **Author:** successjoseph ([github.com/successjoseph](https://github.com/successjoseph))
- **License:** No license file included in this repository — all rights reserved by default.
