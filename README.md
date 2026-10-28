#Card Studio Pro

A zero-build, single-file web editor and compiler for personal micro-sites and digital business cards.

Project Purpose: This repository was created for testing and experimental purposes to explore AI-driven web development capabilities. The application was generated almost entirely using Gemini 3.6 Thinking, with only very limited manual code adjustments.

Features

Zero-Build Architecture: Runs directly in any modern browser via CDNs without requiring npm or build tools.

WYSIWYG Live Editor: Real-time side-by-side editing with desktop and mobile viewport controls.

Standalone HTML Export: Compiles a single portable index.html file containing all logic and styling.

vCard (.vcf) Export: Generates RFC 6350-compliant contact files with strict character escaping.

PWA & Offline Support: Includes an inline Service Worker to cache cards for offline use.

OpenGraph Social Preview: Configurable metadata for link previews on iMessage, WhatsApp, LinkedIn, and X.

QR Code Sharing: Built-in QR generator pointing directly to the card URL.

Themes & Visual Banners: Presets, Google Fonts typography, animated CSS banners, and Base64 photo uploads.

Data Portability: LocalStorage draft persistence along with JSON config import and export.

Quick Start

Open index.html directly in any web browser.

Edit your profile, sections, links, and styling using the editor panel.

Click Export index.html to generate a standalone web page.

Live Hosting (GitHub Pages)

To publish your exported card online for free:

Upload index.html to the root of a public GitHub repository.

Go to Settings > Pages in your repository.

Under Branch, select main and click Save.

Your page will be accessible at https://<username>.github.io/<repo-name>/.

Tech Stack

Styling: Tailwind CSS (CDN) + CSS Variables

Icons: FontAwesome 6.5

Fonts: Google Fonts

QR Engine: qrcode.js

Logic: Vanilla JavaScript (ES6+)

License

MIT License
