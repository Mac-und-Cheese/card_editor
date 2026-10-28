# Card Studio Pro

> **Experimental Project:** Built for testing and evaluation purposes using **Gemini 3.6 Think** with minimal manual adjustments.

---
**[Open Live Application](https://mac-und-cheese.github.io/card_editor/index.html)**

## Overview

Card Studio Pro is a single-file web application and WYSIWYG studio for building modular digital business cards and personal micro-sites. It features a real-time preview canvas and exports self-contained `index.html` files with zero external build step dependencies.

---

## Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Framework** | Vanilla HTML5 / JavaScript (ES6+) |
| **Styling** | Tailwind CSS (CDN) |
| **Icons & Fonts** | FontAwesome 6, Google Fonts |
| **QR Engine** | QRCode.js |

---

## Key Features

- **Zero-Build Architecture**: Runs natively in any browser with no Node.js or `npm` requirements.
- **Standalone HTML Export**: Compiles self-contained micro-sites ready for deployment.
- **Modular Layout**: Reorderable content sections, portfolio items, and social media profile links.
- **vCard Generation**: Built-in `.vcf` contact file generator with RFC 6350 strict escaping.
- **PWA & Offline Caching**: Embedded Service Worker and Web App Manifest generation for offline access.
- **OpenGraph SEO**: Custom meta tag generation for social media link sharing previews.

---

## License

Distributed under the MIT License.
