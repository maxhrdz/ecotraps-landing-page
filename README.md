# EcoTraps — Business Website

Responsive website for EcoTraps, a business focused on industrial grease-trap products.

**Live site:** https://ecotraps-landing-page.vercel.app/

## Stack

React · TypeScript · Vite · Tailwind CSS

## What is included

- Responsive product and company information pages
- Mobile navigation and an FAQ section
- Contact form integration using Formspree
- React components and TypeScript configuration
- Vite-based development and production builds

## Run locally

Requires Node.js and npm.

~~~bash
git clone https://github.com/maxhrdz/ecotraps-landing-page.git
cd ecotraps-landing-page
npm ci
npm run dev
~~~

## Check and build

~~~bash
npm run build
npm run lint
npm run preview
~~~

These scripts are defined in [package.json](package.json). Any contact-form integration may require service-side configuration.

## Project files

- [src/](src/) — application components and styles
- [public/](public/) — publicly served static assets
- [vite.config.ts](vite.config.ts) — Vite configuration
- [tailwind.config.js](tailwind.config.js) — Tailwind configuration

This repository contains the website source code, not a transactional e-commerce backend.
