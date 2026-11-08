# Jainam Shah — Responsive Portfolio

A one-page personal portfolio built with semantic HTML and plain CSS. The layout is mobile-first and adapts to phone, tablet, and laptop widths.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a browser.

No build tools, package installation, or backend are required. Google Fonts are loaded online; system sans-serif fallbacks are included.

## What’s included

- Responsive navigation and hero section
- About section with real profile and skills content
- Two project summaries: Smart Tally Assistant and Task Management System
- Contact call-to-action and GitHub link
- CSS-built project previews and decorative hero artwork
- Responsive image/artwork containers using `max-width`, `aspect-ratio`, and `overflow: hidden`

## Design decisions

- Used a dark, minimal visual direction with a lime accent for contrast.
- Used CSS illustrations for the project previews instead of external image assets, keeping the page lightweight and avoiding image overflow or broken image links.
- Used a single-column layout on small screens and a two-column layout on wider screens.
- The contact email is a placeholder (`jainam@example.com`); replace it with your preferred public contact email before publishing.

## Mobile check

The stylesheet includes a dedicated breakpoint at 420px. The page uses `box-sizing: border-box`, bounded content widths, and no fixed-width image elements to prevent horizontal scrolling at 375px.

## Publish to a public GitHub repository

Create a new **public** repository on GitHub, then run these commands in this folder:

```bash
git init
git add .
git commit -m "Build responsive one-page portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with the URL of your new repository.
