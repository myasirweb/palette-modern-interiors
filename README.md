# Palette — Interior Design Portfolio Website

> A fully responsive interior design portfolio website built with Next.js 15 and Sass — featuring smooth scroll animations, filterable project galleries, and a polished multi-section layout.

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper.js-6332F6?style=flat-square&logo=swiper&logoColor=white)
![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)

🔗 **Live Demo:** [palette.vercel.app](#) *(update with live URL)*

---

## Overview

Palette is a frontend portfolio website designed for interior designers and creative agencies. Built with Next.js 15 App Router and Turbopack for fast development builds, it features animated section reveals with WOW.js, a filterable project gallery powered by Isotope Layout, and smooth image sliders with Swiper.js.

The project demonstrates real-world client website delivery — translating a design-focused brief into a performant, SEO-ready Next.js application with modular SCSS styling.

---

## Features

- Filterable portfolio gallery — Isotope Layout for category-based project filtering
- Scroll animations — WOW.js for entrance effects on scroll
- Image sliders — Swiper.js for project and testimonial carousels
- Next.js App Router — file-based routing with layouts and nested pages
- Modular SCSS — organized component-level stylesheets
- Fully responsive — mobile-first design across all screen sizes
- Fast builds — Turbopack for instant HMR in development
- SEO ready — Next.js metadata API for page-level SEO

---

## Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | Next.js 15 (App Router + Turbopack) |
| **UI Library** | React 18 |
| **Styling** | Sass / SCSS |
| **Slider** | Swiper.js |
| **Animations** | WOW.js |
| **Gallery Filter** | Isotope Layout |
| **Deployment** | Vercel |

---

## Getting Started

### Prerequisites

- Node.js >= 18
- npm >= 9

### Installation

```bash
# Clone the repository
git clone https://github.com/myasirweb/palette.git
cd palette

# Install dependencies
npm install

# Start development server (Turbopack)
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
# Build optimized production bundle
npm run build

# Start production server
npm start
```

### Compile SCSS Manually *(optional)*

```bash
# Runs automatically in dev — use only if needed separately
npm run sass
```

---

## Project Structure

```
palette/
├── app/                    # Next.js App Router pages & layouts
├── components/             # Reusable UI components
│   └── layout/             # Header, Footer, MobileMenu
├── public/                 # Static assets
│   ├── images/             # Project and UI images
│   ├── css/                # Compiled CSS output
│   └── scss/               # Source SCSS files
└── package.json
```

## Author

**Muhammad Yasir** — Frontend Engineer

- 🌐 [yasir-portfolio-nextjs.vercel.app](https://yasir-portfolio-nextjs.vercel.app)
- 💼 [linkedin.com/in/yasirweb](https://linkedin.com/in/yasirweb)
- 📧 muhammad.yasir1368@gmail.com
- 🐙 [github.com/myasirweb](https://github.com/myasirweb)

---

## License

© 2025 Muhammad Yasir. All rights reserved.
