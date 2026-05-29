# Drone Explorers Website

Professional drone photography, videography, and mapping services for Metro Atlanta.

**Live site:** https://dronexplorers.com

## Stack
- Plain HTML, CSS, JavaScript — no framework, no build step
- Hosted on GitHub Pages
- Forms via Formspree
- Fonts via Google Fonts (Bebas Neue + DM Sans)

## Structure
```
/
├── index.html          # Homepage
├── contact.html        # Contact / quote request form
├── packages.html       # Full packages page (coming soon)
├── about.html          # About page (coming soon)
├── privacy.html        # Privacy policy (coming soon)
├── css/
│   ├── style.css       # Main stylesheet
│   └── contact.css     # Contact page styles
├── js/
│   └── main.js         # Nav scroll, mobile menu, smooth scroll
└── images/
    ├── logo-white.png  # White logo (for dark backgrounds)
    └── logo-black.png  # Black logo (for light backgrounds)
```

## Local Development
No build tools needed. Just open `index.html` in a browser or use Live Server in VS Code.

## Deploying
```bash
git add .
git commit -m "your message"
git push
```
GitHub Pages auto-deploys from the main branch.

## To Do
- [ ] Add logo images to /images folder
- [ ] Set up Formspree account and replace YOUR_FORM_ID in contact.html
- [ ] Point dronexplorers.com domain to GitHub Pages
- [ ] Build out packages.html
- [ ] Build out about.html
- [ ] Add real aerial photo gallery once shooting begins
