# ANCF Digital Projects v2026 - static website 2026

> **ANCF Digital Projects is a browser-based static site for exploring antinatalism and childfree ideas, with version 2026 delivering client-side tools, guides, games, and calculators for reading, browsing, and reflection.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/olivermzgking5763/ancf-digital-projects-2026?style=flat-square)](https://github.com/olivermzgking5763/ancf-digital-projects-2026)

---

<p align="center">
  <a href="https://olivermzgking5763.github.io/ancf-digital-projects-2026/">
    <img src="https://img.shields.io/badge/Download-ANCF%20Digital%20Projects%20Latest-brightgreen?style=for-the-badge" alt="Download ANCF Digital Projects">
  </a>
</p>

> **[Direct Download - ANCF Digital Projects v2026](https://olivermzgking5763.github.io/ancf-digital-projects-2026/)**

---

[Download Latest Build](https://olivermzgking5763.github.io/ancf-digital-projects-2026/)

---

## Overview

ANCF Digital Projects is a static web collection centered on antinatalism and childfree subject matter. It combines lightweight content with interactive browser tools, all running entirely on the client side. The result is a straightforward, self-contained experience that does not require an account or backend service.

The site brings together mini-projects, guides, games, calculators, and reflection-oriented pages in a single mobile-friendly package. Since everything is client-side, the project is simple to host and share, and any preferences or progress are stored locally on the device.

---

## What You Get

- 100 client-side mini-projects in one browser-based collection
- Searchable and filterable gallery for faster browsing
- Dark mode toggle for comfortable viewing
- Mobile-first responsive layout for phones and desktop screens
- LocalStorage-based settings and progress persistence
- No backend dependency for core site behavior
- No ads or tracking elements in the site design
- Tools, guides, games, and calculators grouped in a single static experience

---

## Installation

1. Clone or download the repository:
   `git clone https://github.com/olivermzgking5763/ancf-digital-projects-2026.git
2. Open the project folder:
   `cd ancf-digital-projects`
3. Serve the files with any static web server, or open the site entry file in a browser.

For local testing, a simple server is enough:

`python -m http.server`

Then open the shown local address in your browser.

---

## How to Use It

Start by browsing the gallery to pick a project, then use search to narrow the list and filters to focus on a specific content type. The interface is meant to make switching between tools, games, and guides quick and intuitive, without navigating away from the site.

Common workflow:
- Open the homepage
- Search by topic or keyword
- Switch themes with the dark mode control
- Launch a mini-project
- Return later and continue with saved local progress where supported

---

## Configuration

Most preferences are managed in the browser and written to localStorage. This covers theme selection along with any available progress or interface settings.

Example of the stored preference pattern:

    localStorage:
      theme: dark | light
      progress: saved per supported activity
      gallery_filters: user-selected options

If you want to reset the site state, clear the browser storage for the domain and reload the page.

---

## Requirements

- A modern web browser with HTML, CSS, and JavaScript support
- Static hosting or local file access for the site files
- Enough browser storage for local settings and progress data
- No server runtime is required for the core site

---

## FAQ

**How are updates applied?**  
The site changes when the static files are replaced or a new build is published.

**Where are settings kept?**  
They are stored in the browser through localStorage, so they remain tied to the same device and browser profile.

**What should I check if search or filters fail?**  
Make sure JavaScript is enabled and that the browser is loading the complete site files. A refresh or clearing outdated storage may also resolve it.

**Does it need a backend?**  
No. The project is built as a client-side static site and works normally without a server-side application.

**How can I remove saved progress?**  
Clear the site data in the browser or delete the relevant localStorage entries, then reload the page.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
