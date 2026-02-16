# CLAUDE.md

## Project Overview

A static business card webpage for Mike Hudson (Frontend Developer). Built with plain HTML and CSS, served via Vite. This is an educational/learning project with embedded CSS challenges and stretch goals.

## Project Structure

```
/
├── index.html      # Single-page HTML (card layout with profile image, name, title, location)
├── styles.css      # All styling (flexbox card, color scheme, embedded challenge comments)
├── mh.jpg          # Profile photo asset
└── package.json    # Vite dev server config
```

All source files live in the root directory. There are no subdirectories, components, or modules.

## Tech Stack

- **HTML5 / CSS3** — No JavaScript, no TypeScript, no frameworks
- **Vite** — Dev server and build tool (default config, no vite.config.js)
- **normalize.css** — Loaded via CDN (`cdnjs.cloudflare.com`)
- **No linter, formatter, or test framework configured**

## Commands

```sh
npm start       # Start Vite dev server
npm run dev     # Same as start
npm run build   # Production build via Vite
npm run preview # Preview production build locally
```

## Design Conventions

- **Font**: Verdana, Geneva, Tahoma, sans-serif
- **Colors**: Background `#ddebf8`, text `#2b2839`, accent `#6351ab` (purple border)
- **Layout**: Flexbox-centered card, 400px width
- **Image**: 150px wide circular profile photo

## Key Notes for AI Assistants

- This is a static site — no server-side logic, no API calls, no state management.
- The CSS file contains educational challenge comments and stretch goals (border customization, border-radius, shadows, hover effects, animations). Preserve these when editing.
- External dependency is only normalize.css via CDN. Keep the project minimal.
- No vite.config.js exists; Vite uses its defaults. Only add one if custom configuration is genuinely needed.
- No CI/CD or deployment pipeline is configured.
