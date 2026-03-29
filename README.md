# Inside a Computer — An Interactive Web Experience

**Frontend Odyssey 2026 | Inside a Computer**

---

## Concept

*Inside a Computer* is an immersive, scroll-driven storytelling experience that takes the user on a visual journey through the five core components of modern computing: the CPU, GPU, RAM, Storage, and Network. Rather than presenting dry technical documentation, the project transforms hardware education into an exploration — where every scroll, click, and hover reveals a new layer of the silicon world.

The narrative arc follows a deliberate five-act structure: a cinematic Hero introduction, a Motherboard overview that contextualizes all components, an interactive Exploration gallery for deep-diving into each chip, a live Data Flow Insight visualizer showing how information moves between components, and a Conclusion that ties the story together with animated statistics.

---

## Design Process

The aesthetic direction was rooted in **tech-noir**: deep navy and black backgrounds, neon cyan and violet accent colors, monospace and geometric display typefaces (Share Tech Mono + Orbitron + Syne), and a pervasive circuit-board grid motif. The goal was to evoke the inside of a machine — cold, precise, electric — without sacrificing readability.

The build is a single, dependency-free HTML file. Animations rely entirely on native CSS keyframes and the Web Animations API, keeping load times minimal. The SVG motherboard diagram uses `animateMotion` to render live data packets traveling between chips. An Intersection Observer drives all scroll-reveal transitions, while a custom cursor, parallax layers, and a simulated CPU clock bar add depth and interactivity.

Component cards use a horizontal drag-scroll track with momentum, each card opening a modal with real-world hardware specifications. A data flow toggle panel lets users isolate specific bus paths and adjust packet animation speed via a range slider.

---

## Tech Stack

HTML · CSS · Vanilla JavaScript · SVG Animations · Intersection Observer API

## Live Demo

> https://inside-a-computerr.netlify.app/
