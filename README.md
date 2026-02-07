# The Craft Table -- Small Business Website Template

A modern, single-page restaurant website template built with Astro and Tailwind CSS. Designed for small businesses that need a polished online presence fast.

![Screenshot](screenshot.png)

[![Astro](https://img.shields.io/badge/Astro-5.x-BC52EE?logo=astro&logoColor=white)](https://astro.build)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile_First-10B981)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Features

- **Single-page layout** -- Hero, Menu, About, Hours & Location, Contact/Reservations, Footer
- **Warm stone & amber color palette** -- premium feel out of the box
- **Fully responsive** -- mobile hamburger menu, adaptive grid layouts, touch-friendly
- **Scroll-reveal animations** -- Intersection Observer-powered fade and slide effects
- **Sticky navigation** -- scroll-aware with backdrop blur and shadow transitions
- **Menu section** with categorized items (Starters, Mains, Desserts) and pricing
- **Reservation form** -- integrated with Formspree (swap in your form ID)
- **Google Maps placeholder** -- ready for your embed code
- **Image placeholders** -- styled containers ready for real photography
- **Testimonial banner** -- quote section for press or customer reviews
- **SEO-ready** -- meta tags, Open Graph, canonical URL, semantic HTML
- **Custom typography** -- Inter (sans) + Playfair Display (serif) via Google Fonts
- **Accessibility** -- focus-visible outlines, semantic structure, ARIA labels
- **Zero JavaScript frameworks** -- vanilla JS for nav toggle and scroll effects only
- **Fast builds** -- static output, deploys anywhere (Vercel, Netlify, Cloudflare Pages)

## Quick Start

```bash
# Clone the repository
git clone https://github.com/SeekerErebus/small-business-template.git
cd small-business-template

# Install dependencies
npm install

# Start the dev server
npm run dev
```

The site will be running at `http://localhost:4321`.

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start dev server at `localhost:4321`         |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview the production build locally        |

## Customization

1. **Business info** -- Update name, address, phone, and hours in `src/pages/index.astro`
2. **Menu items** -- Edit the Starters, Mains, and Desserts sections with your offerings
3. **Colors** -- Modify the `@theme` block in `src/styles/global.css` to change the palette
4. **Contact form** -- Replace `YOUR_FORM_ID` in the form action with your [Formspree](https://formspree.io) endpoint
5. **Google Maps** -- Uncomment the iframe in the Hours & Location section and add your embed URL
6. **Images** -- Replace the placeholder containers with your own photography

## Tech Stack

- [Astro 5](https://astro.build) -- static site generator
- [Tailwind CSS 4](https://tailwindcss.com) -- utility-first CSS via `@tailwindcss/vite`
- Vanilla JavaScript -- no framework overhead
- Google Fonts -- Inter + Playfair Display

## Live Demo

[View Live Demo](#) <!-- Replace with deployed URL -->

## License

MIT
