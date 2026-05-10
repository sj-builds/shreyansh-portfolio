<div align="center">

# Shreyansh Jain — Futuristic Cybersecurity Portfolio

An immersive, cinematic portfolio experience built with a hacker-inspired interface, glassmorphism UI, and neon cyberpunk accents.

[![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-19.x-149ECA?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.x-38BDF8?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</div>

## Overview

This project is a premium, production-ready portfolio for **Shreyansh Jain**, designed to feel like a secure terminal session inside a cinematic UI. The goal is simple: communicate capability and taste—fast—through a responsive, motion-first interface with careful typography, subtle depth, and a restrained neon palette.

The aesthetic is intentionally “cyber”: grid fields, glow accents, glass surfaces, and a boot-sequence style entry—without sacrificing clarity, performance, or accessibility.

## Features

- **Immersive motion**: Framer Motion transitions and view-based reveals with a cinematic feel.
- **Glassmorphism UI**: layered panels, subtle borders, and glow shadows tuned for dark environments.
- **Futuristic typography**: display + mono pairing for “terminal meets product” contrast.
- **Responsive by design**: mobile-first constraints with desktop preserved.
- **Production contact form**: Formspree-backed submissions with validation + loading/success/error states.
- **Downloadable resume**: direct PDF download with a stable filename.
- **SEO metadata**: canonical SPA head metadata in `index.html`.
- **Vercel-ready**: standard Vite SPA output to `dist/` with SPA rewrites configured.

## Tech Stack

| Category | Tools |
| --- | --- |
| Framework | React + TypeScript |
| Build | Vite |
| Styling | Tailwind CSS |
| Motion | Framer Motion |
| Icons | Lucide React |
| Forms | Formspree |
| Deployment | Vercel (static SPA) |

## Project Architecture

- **Standard SPA**: Vite builds a static bundle to `dist/`.
- **Client-side routing**: React Router DOM powers SPA navigation and path fallback.
- **Component-driven UI**: sections are composed from focused, reusable components.
- **Data-driven content**: JSON files in `src/data/` keep content editable without touching layout.
- **Performance-first defaults**: minimized runtime complexity (no SSR, no server adapters).

## Folder Structure

```text
.
├─ public/
│  ├─ favicon.svg
│  ├─ site.webmanifest
│  └─ resume.pdf
├─ src/
│  ├─ components/
│  ├─ data/
│  ├─ App.tsx
│  ├─ main.tsx
│  └─ styles.css
├─ index.html
├─ vite.config.ts
└─ vercel.json
```

## Getting Started

### Prerequisites

- Node.js \(LTS recommended\)
- npm

### Install

```bash
npm install
```

### Run locally

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Deployment (Vercel)

This project is configured as a **static Vite SPA**:

- Build command: `npm run build`
- Output directory: `dist`
- SPA routing: `vercel.json` rewrites all routes to `index.html`

Deploying on Vercel should work out of the box with static hosting.

## Environment Variables

This repo is production-ready without required environment variables. If you prefer not to hardcode service endpoints, you can optionally introduce:

```bash
# Optional (if you choose to wire it)
VITE_FORMSPREE_ENDPOINT="https://formspree.io/f/mlgzopqr"
```

## Screenshots

Add your screenshots to a folder such as `docs/screens/` and replace the placeholders below.

```md
![Home / Hero](docs/screens/hero.png)
![Projects](docs/screens/projects.png)
![Contact](docs/screens/contact.png)
```

## Credits

- **Framer Motion** — animation and motion primitives
- **Vite** — fast dev/build tooling
- **Tailwind CSS** — styling system
- **Lucide React** — icon set

## License

UNLICENSED — All rights reserved.

## Contact

- **GitHub**: `https://github.com/sj-builds`
- **LinkedIn**: `https://www.linkedin.com/in/shreyanshjain-profile`
- **X (Twitter)**: `https://x.com/jshreyansh962`
- **Email**: `jshreyansh962@gmail.com`

