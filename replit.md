# Aviator Landing Page

## Overview
A static landing page for "Aviator" - a promotional website in Portuguese (Brazil/Mozambique). The site is a single `index.html` page that references bundled JS, CSS, and image assets.

## Current State
- The HTML page is present but the referenced build assets (JS, CSS, images) are missing from the repository
- The site references: `js/index-BJXQyBA2.js`, `css/index-D1hpTV2m.css`, and image assets in `assets/`
- These files need to be added from the original build output for the site to display properly

## Project Architecture
- **Type**: Static website (no backend, no build system)
- **Server**: Python `http.server` on port 5000 for development
- **Deployment**: Static deployment serving the root directory
- **Entry point**: `index.html`

## How to Run
- The workflow "Start application" runs `python server.py` which serves files on port 5000

## Recent Changes
- 2026-02-24: Initial Replit setup with Python static file server
