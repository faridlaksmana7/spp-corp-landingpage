# SPP Corp — Official Landing Page & Portfolio

> **"Big ideas, built for the real world."**  
> Hyperbundle Agency: Event Production, Advertising & Branding, Digital Experience, and Manpower with 15+ years of nationwide experience.

---

## 🚀 Overview

This repository contains the complete, production-ready landing page and interactive project portfolio for **SPP Corp**. Built with a dark glassmorphic luxury aesthetic and vibrant cyan branding (`#00B2FE`), it delivers high performance, fluid animations, and responsive layouts across all devices.

---

## ✨ Key Features

1. **Cybernetic Lottie Asset Preloader**:
   - Fullscreen Bodymovin SVG animation with rotating orbital rings and glowing SPP emblem.
   - Real asset synchronization (`document.fonts.ready`, critical images, window load) with smooth 0% → 100% digital counter interpolation.
   - Eliminates FOUC (Flash of Unstyled Content) and calibrates GSAP ScrollSmoother measurements before the page reveals.
   - 100% mobile-responsive with dynamic viewport height (`100dvh`).

2. **Cinematic Hero Section**:
   - High-definition 1080p looping showreel video backdrop with zero UI clutter.
   - Mobile-first typography and CTA button hierarchy.

3. **Client Brand Showcase**:
   - Infinite smooth ticker featuring major corporate and consumer brand partners:
     *GoJek, GoFood, Pertamina, Bank Mandiri, Bank BJB, Gudang Garam, Gentle Gen, LG Electronics, ANTV, Mie Gacoan, Le Minerale, Dewa United, and eFishery*.
   - Specially calibrated high-contrast dark vector logos and tight spacing on both mobile and desktop.

4. **Interactive 58-Project Portfolio & Gallery**:
   - Category filtering (*Event Production, Retail Branding, Outdoor Advertising, Digital Experience, etc.*).
   - Dynamic popup modal with high-res multi-image project carousels, client briefs, deliverable tags, and specifications.
   - 100% optimized WebP assets ensuring rapid loading.

5. **GSAP ScrollSmoother & Micro-Interactions**:
   - Inertia scrolling, parallax image reveals, magnetic buttons, and custom magic cursor.

---

## 🛠️ Tech Stack

- **Markup**: Semantic HTML5 with SEO meta tags, OpenGraph, and JSON-LD structured data.
- **Styling**: Vanilla CSS3, CSS Grid/Flexbox, Bootstrap 5.3 utilities, Glassmorphism.
- **Animations**: GSAP 3 (ScrollTrigger, ScrollSmoother), Bodymovin Lottie (`lottie.min.js`).
- **Assets**: 100% WebP image compression with high fidelity.
- **Deployment**: Apache `.htaccess` with Brotli/Gzip deflate, WebP MIME types, 1-year browser caching, and security headers.

---

## 📁 Repository Structure

```
spp-corp-landingpage/
├── index.html                 # Main landing page markup
├── .htaccess                  # Production Apache performance & caching config
├── robots.txt                 # SEO crawler rules
├── sitemap.xml                # Search engine sitemap
├── assets/
│   ├── css/
│   │   ├── main.css           # Core styling and typography
│   │   ├── spp-preloader.css  # Fullscreen Lottie preloader styles
│   │   └── vendors/           # Bootstrap, Swiper, spacing, etc.
│   ├── js/
│   │   ├── main.js            # GSAP animations & ScrollSmoother init
│   │   ├── spp-loader.js      # Asset synchronization engine
│   │   ├── spp-loader.json    # Lottie vector animation config
│   │   └── vendors/           # Lottie.js, jQuery, Isotope, Swiper
│   ├── fonts/                 # FontAwesome Pro & Web fonts
│   └── imgs/
│       ├── template/          # SPP logo, favicon, GIF showcase, hero poster
│       ├── icons/             # Clean client brand logos (WebP)
│       └── about/             # Hardware mixer & equipment assets
└── projects/                  # 200 optimized WebP portfolio assets (58 projects)
```

---

## 💻 Local Development

To run the landing page locally:

```bash
# Using any static server (e.g. serve, http-server, or Python)
npx serve .

# Or with Python 3:
python3 -m http.server 3000
```

Open `http://localhost:3000/` in your browser.

---

## 🌐 Production Deployment

- **cPanel / Apache**: Upload all files directly to `public_html/`. The included `.htaccess` file automatically configures compression, caching, and clean routing.
- **Vercel / Netlify / GitHub Pages**: Deploy directly from the `main` branch.

---

## 📄 License

Proprietary © 2026 SPP Corp. All rights reserved.
