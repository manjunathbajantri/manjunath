# Virtosix — Smart RAM & Storage Organizer

Virtosix is a single-page landing site for **Virtosix**, a smart system that automatically organizes RAM usage, catalogs storage, and improves overall computer speed — designed to work on everything from budget laptops to high-end workstations.

This repo contains the marketing/landing page (`index.html`) built as a self-contained static HTML file with an animated intro sequence, product info, feature highlights, a comparison table, FAQ, and a contact form.

## ✨ Features

- **Animated intro screen** — typewriter-style logo/tagline animation that plays once on load, then fades into the main site
- **Hero section** — product tagline and call-to-action
- **About section** — explains what Virtosix does and who it's for
- **Feature grid** — RAM organization, storage cataloging, speed boosts, Linux/hypervisor support
- **Comparison table** — benefits broken down by high-end vs. low-cost laptops
- **FAQ accordion** — click-to-expand questions and answers
- **About Manjunath** — founder bio section with photo
- **Contact section** — WhatsApp click-to-chat link, email link, and a contact form (via [Formspree](https://formspree.io))
- **Floating WhatsApp button** — persistent quick-contact button
- **Fully responsive** — adapts to mobile and tablet screens
- **Custom favicon support**

## 🗂️ Project Structure

```
.
├── index.html        # Main landing page (all HTML/CSS/JS inline, no build step)
├── favicon.ico        # Site favicon (add to project root)
└── manjunath.jpg       # Founder photo used in the "About Manjunath" section (add to project root)
```

This is a **zero-dependency static site** — no build tools, frameworks, or `node_modules` required. Just HTML, CSS, and vanilla JavaScript in one file.

## 🚀 Getting Started

### Run locally
Simply open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

### Deploy to Vercel
1. Push this repo to GitHub
2. Import the repo into [Vercel](https://vercel.com)
3. No build settings needed — deploy as a static site
4. Make sure `favicon.ico` and `manjunath.jpg` sit in the same root directory as `index.html` so they resolve correctly at `/favicon.ico` and `/manjunath.jpg`

## 📞 Contact

- **WhatsApp:** [+91 7338422946](https://wa.me/917338422946)
- **Email:** manjunathbajantri05@gmail.com

## 📄 License

© 2026 Virtosix. All rights reserved.
