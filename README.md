# April 25 — Creative Studio Website

A clean, modern static website for **April 25 Studio**, built with plain HTML, CSS and JavaScript — no frameworks, no build tools required.

## Structure

```
index.html   — main page (hero, about, services, portfolio, contact, footer)
styles.css   — responsive dark-mode stylesheet with CSS custom properties
script.js    — sticky nav, mobile menu, scroll-reveal, contact form validation
```

## Features

- 🌗 Dark-mode design with subtle gradients and glassmorphism accents
- 📱 Fully responsive (mobile nav included)
- ♿ Semantic HTML with ARIA attributes
- ✨ Smooth scroll-reveal animations via `IntersectionObserver`
- 📬 Client-side contact form with validation
- 🚀 Zero dependencies — open `index.html` in any browser

## Usage

No build step needed. Simply open `index.html` in a browser, or serve the folder with any static file server:

```bash
# Python (built-in)
python -m http.server 8080

# Node / npx
npx serve .
```