# DecodeLabs — Project 2: DecodeLabs-Digital-Agency

## Overview
This project is part of the DecodeLabs Industrial Training Kit (Batch 2026), built under the Frontend Development track. It is a fully responsive single-page website demonstrating fluid layout design using pure CSS — no frameworks involved. The goal was to build an interface that adapts cleanly across desktop, tablet, and mobile screens using CSS Media Queries.

## Features
- **Responsive Navigation** — Sticky navbar with a hamburger menu that activates on smaller screens, plus active-link highlighting that updates automatically as the user scrolls.
- **Hero Section** — Introductory banner with a call-to-action button that smoothly scrolls to the Services section.
- **Services Section** — Grid-based cards outlining core offerings, with hover animations.
- **Projects Section** — A showcase of training milestones, highlighting the current project in the track.
- **About Section** — Brief description of DecodeLabs with key stats displayed in a clean layout.
- **Contact Section** — A styled, functional contact form (name, email, message) with front-end submission feedback.
- **Scroll Reveal Animations** — Sections and cards fade in as the user scrolls, using the Intersection Observer API.
- **Fully Responsive Layout** — Verified across three breakpoints: 992px (tablet), 768px (mobile), and 480px (small mobile).

## Tech Stack
- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Media Queries)
- Vanilla JavaScript (DOM manipulation, Intersection Observer, scroll events)

## File Structure
```
project/
├── index.html
├── css/
│   └── style.css
└── README.md
```

## Responsive Strategy
The layout uses a mobile-first spacing system controlled through a single `section` padding rule, scaled down at each breakpoint. Grid-based sections (Services, Projects) collapse from 3 columns → 2 columns → 1 column as the viewport shrinks, and the navigation switches from a horizontal menu to a collapsible mobile menu below 768px.

## Notes
- The contact form is currently front-end only; submissions are not sent to a backend or email service. It can be connected to a service like Formspree or EmailJS for full functionality.
- No external CSS frameworks (e.g. Bootstrap, Tailwind) were used — all responsive behavior is handled with custom CSS to demonstrate core media query skills as required by the project brief.