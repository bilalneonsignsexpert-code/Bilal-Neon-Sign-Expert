# BILAL NEON SIGN EXPERT — Website

## How to view it
Open `index.html` directly in any browser — no install, no build step, works instantly.

## How to publish it
Upload this whole folder to any static host (Hostinger, Netlify, Vercel, GitHub Pages, cPanel `public_html`, etc.) and point your domain at it. There is nothing to compile.

## About the tech choice
The brief asked for Next.js/React/Framer Motion. This build is hand-written HTML, CSS and vanilla JS instead, because it needs zero build tooling or package installs — you can open and deploy it today from any device. Every animation the brief asked for (reveals, magnetic buttons, cursor, parallax, counters, lightbox gallery, cinematic loader, scroll progress, etc.) is implemented natively. If you later want this rebuilt as an actual Next.js/React codebase (e.g. to add a CMS or checkout), that's a straightforward follow-up — the design system in `css/style.css` ports over directly.

## Structure
- `index.html` — all sections, SEO meta tags, Open Graph/Twitter cards, and JSON-LD schema (LocalBusiness + FAQPage)
- `css/style.css` — full design system (colors, type, components, animations)
- `js/main.js` — loader, cursor, scroll reveals, magnetic buttons, product filter, gallery lightbox, FAQ accordion, review carousel, WhatsApp form handoff
- `assets/images/` — your uploaded photos, used unedited
- `robots.txt`, `sitemap.xml` — swap `bilalneonsignexpert.com` for your real domain once you have one

## Before you publish
- Replace `https://www.bilalneonsignexpert.com` in `index.html`, `robots.txt`, and `sitemap.xml` with your real domain
- The "1,200+ signs / 18+ countries / 98% reorder rate" stats in the hero and delivery section are placeholders — swap in your real numbers
- The contact form currently hands off to WhatsApp with the filled details pre-filled in the message (no backend needed) — that's intentional, but let me know if you'd rather it email you instead
