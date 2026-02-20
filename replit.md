# DevLyra - Portfolio Landing Page

## Overview
Modern, creative portfolio/landing page for DevLyra.com - a coding services business. Features scroll-driven zoom in/out animations using framer-motion.

## Tech Stack
- Frontend: React + TypeScript + Vite
- Styling: Tailwind CSS + shadcn/ui components
- Animations: framer-motion (scroll-driven parallax, zoom reveals)
- Backend: Express (minimal, serves static frontend)
- Routing: wouter

## Project Structure
- `client/src/pages/home.tsx` - Main landing page with all sections
- `client/src/App.tsx` - App root with routing
- `client/src/index.css` - Theme tokens (dark-first design)
- `client/src/components/ui/` - shadcn/ui components

## Design
- Dark theme with purple/violet accent colors
- Space Grotesk font for headings, JetBrains Mono for code elements
- Scroll-driven zoom animations on all sections
- Floating gradient orbs for visual depth
- Grid pattern overlays

## Sections
1. Hero - Animated title with gradient text, CTAs
2. Services - 4 service cards with zoom reveal
3. Portfolio - 3 project showcase cards
4. Technology - Tech stack grid + stats
5. Contact - Contact info + CTA

## Running
```
npm run dev
```
Frontend on port 5000.
