# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

TurismoIca is a static multi-page website for tourism in Ica, Peru. It has no build system, package manager, or framework — all pages are plain HTML with a single shared CSS file.

## Development

Open any `.html` file directly in a browser to preview it. No server or build step is required. For live reload during development, use a tool like VS Code's Live Server extension.

## Architecture

The site is structured as independent HTML pages sharing one stylesheet:

- `index.html` — home/landing page
- `nosotros.html` — about us
- `servicios.html` — services offered
- `galeria.html` — photo gallery
- `contacto.html` — contact form
- `css/estilos.css` — all styles for the entire site

Navigation between pages uses plain `<a href>` links. There is no JavaScript framework or templating — shared elements (header, nav, footer) must be duplicated across each HTML file.
