# HackLodge

Builder infrastructure for hackathons.

HackLodge helps hackathon organizers turn existing venue space into temporary infrastructure for 24-72 hour events: sleep zones, charging stations, secure lockers, recovery areas, and gear rental.

Tagline: **Sleep. Recharge. Ship.**

## What This Project Contains

This repository currently contains the first Astro landing page for HackLodge.

Landing page sections:

- Hero with primary waitlist CTA
- Problem section for overnight hackathon pain points
- Solution section covering core HackLodge services
- Organizer benefits
- Participant benefits
- Setup/package options
- Participant and organizer waitlist forms

Core services shown:

- Sleep Zones
- Charging Stations
- Lockers
- Recovery Areas
- Gear Rentals

## Tech Stack

- [Astro](https://astro.build/)
- HTML, CSS, and small vanilla browser script
- Static assets served from `public/`

## Project Structure

```text
.
├── PRD.md
├── README.md
├── astro.config.mjs
├── package.json
├── public/
│   ├── hacklodge-venue.png
│   └── logo.png
└── src/
    ├── env.d.ts
    ├── pages/
    │   └── index.astro
    └── styles/
        └── global.css
```

## Local Setup

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local site:

```text
http://127.0.0.1:4321/
```

## Available Scripts

Run the local dev server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

Run Astro CLI commands:

```bash
npm run astro
```

## Deployment Notes

This is a static Astro site. Any static host that supports Node builds can deploy it.

Recommended build settings:

- Install command: `npm install`
- Build command: `npm run build`
- Output directory: `dist`

Suitable hosts:

- Vercel
- Netlify
- Cloudflare Pages
- GitHub Pages

## Current Status

This is an early landing page MVP for validating demand and collecting interest from:

- Hackathon organizers
- University hackathon teams
- Corporate innovation teams
- AI hackathon organizers
- Hackathon participants

The current waitlist forms are frontend-only and show local confirmation feedback. A backend or form provider should be connected before collecting real signups.
