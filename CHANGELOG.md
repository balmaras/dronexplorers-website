# Changelog — Drone Explorers Website

All notable changes to the Drone Explorers website will be documented here.

---

## [0.2.0] — 2026-06-13

### Added
- Logo images added to `images/` folder (`dx_white.png`, `dx_black.png`)
- Fixed logo filename references in `index.html` and `contact.html`

### Fixed
- CSS not loading due to incorrect folder structure — resolved by correcting relative paths
- Logo not rendering in nav and footer — updated image src references to match actual filenames

---

## [0.1.0] — 2026-05-29 — Initial Build

### Added
- `index.html` — full homepage including:
  - Fixed nav with mobile hamburger menu
  - Hero section with FAA badge, headline, CTA buttons, stat cards, and service area list
  - Services section (Real Estate Photography, Aerial Video, Construction Progress, 2D Mapping)
  - Packages preview (Starter $149, Standard $249, Premium $399)
  - Why Us section with four value props
  - CTA banner
  - Footer with links and service area
- `contact.html` — quote request form wired for Formspree (YOUR_FORM_ID placeholder)
- `css/style.css` — full design system:
  - Colors: Black #0A0A0A, Charcoal #111827, Orange #FF6B2B accent
  - Fonts: Bebas Neue (headings), DM Sans (body) via Google Fonts
  - Fully responsive with mobile breakpoints at 768px and 480px
  - Animations: fadeUp on hero elements
- `css/contact.css` — contact page specific styles
- `js/main.js` — nav scroll shadow, mobile menu toggle, smooth scroll
- `README.md` — project overview, file structure, deployment instructions, to-do list

### Setup
- Repo created: `balmaras/dronexplorers-website` (public)
- GitHub Pages enabled — live at `balmaras.github.io/dronexplorers-website`
- Git configured on Mac (HTTPS, gh auth login, macOS Keychain)
- Git configured on Windows (credential.helper=manager, user updated to personal identity)
- VS Code installed on Windows with `code .` terminal command working

---

## [Unreleased] — Up Next

- [ ] Set up Formspree — replace `YOUR_FORM_ID` in `contact.html`
- [ ] Build `packages.html` — full detailed packages page
- [ ] Build `about.html` — story, mission, service area
- [ ] Build `privacy.html` — privacy policy
- [ ] Point `dronexplorers.com` domain to GitHub Pages
- [ ] Connect GitHub to Claude.ai (retry on Windows)
- [ ] Add Stripe payment links
- [ ] Add photo gallery once shooting begins
- [ ] Add Google Analytics
