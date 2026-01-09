# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal portfolio website for an attorney, hosted on GitHub Pages with a custom domain (pmenair.com).

## Development

**No build system** - this is a purely static site. To develop:
- Edit HTML/CSS/JS files directly
- Preview by opening `index.html` in a browser
- Push to `main` branch to deploy via GitHub Pages

## Architecture

The site consists of a single page with:
- `index.html` - Main page using microformat markup (h-card) for semantic structure
- `paul.css` - Minimal styling (white text, dark background via Backstretch)
- `back.js` - jQuery Backstretch plugin for dynamic background image sizing
- `paul.jpg` - Background image
- `foaf.rdf` - FOAF (Friend of a Friend) RDF metadata for semantic web discovery
- `MenairPaulNTAyMDE4.vcf` - vCard contact file

## Key Technical Details

- Uses jQuery 1.4.2 loaded from Google CDN
- Employs microformat classes (`h-card`, `p-name`, `p-note`, `u-url`, `u-key`) for structured contact data
- Includes cryptographic identity verification links (Keyoxide, OpenPGP keys)
- FOAF RDF contains RSA public key for identity verification
