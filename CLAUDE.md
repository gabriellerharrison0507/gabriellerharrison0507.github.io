# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## Overview

Gabrielle ("Gabby") Harrison's personal website. Deployed at `gabriellerharrison0507.github.io` via GitHub Pages (auto-deploys on push to `main`).

- **Purpose**: Personal brand + resume site for job searching in data & AI engineering
- **Target roles**: Data analysis, AI tooling, agentic systems — something like her current work at Charter but better compensated
- **Vibe**: Colorful, fun, bubbly — matches the apartment tracker aesthetic

## File Structure

```
index.html     # Entire site — all CSS, JS, HTML in one file
```

**No build step.** Open `index.html` directly in a browser to preview. Deploy with:

```bash
git add index.html
git commit -m "message"
git push   # live within ~1 minute
```

## Architecture — Sections in `index.html`

- **Nav** — sticky, links to all sections
- **Hero** — name, tagline, CTA buttons, animated blobs
- **About** — bio, fun facts, photo placeholder (Gabby to swap in real photo)
- **Skills** — chip/badge grid grouped by category (AI & Agents, Data & Pipelines, Analytics & Viz, Process & Delivery)
- **Projects** — cards: Apartment Tracker (live link), Analytics Automation Pipeline (case study TBD), Test Validation Pipeline (case study TBD)
- **Blog** — 5 placeholder posts, all "Coming soon" — Gabby will write these over time
- **Contact** — email, LinkedIn, GitHub

## Design System

Same as apartment tracker:
```css
--cream: #F0FAFA      /* background */
--ink: #0A2525        /* text */
--accent: #0ABAB5     /* teal, primary */
--pink: #FF0090       /* secondary / hero highlight */
--lavender: #9B84B8
--sage: #7A9E7E
--serif: 'DM Serif Display'
--sans: 'DM Sans'
```

## Key Details

- **Email**: gabrielle.r.harrison0507@gmail.com
- **LinkedIn**: linkedin.com/in/gabriellerharrison (confirm URL is correct)
- **GitHub**: github.com/gabriellerharrison0507
- **Apartment Tracker**: gabriellerharrison0507.github.io/apartment-tracker/

## Content Notes

- Focus on **skills and brand**, not specific employment history or salary
- Blog post ideas already seeded:
  1. How I built a daily apartment price tracker (data pipelines)
  2. Agentic AI isn't magic — how it actually works
  3. Prompt engineering for real production AI
  4. From spreadsheets to multi-agent pipelines (career story)
  5. The tools I actually use as a data & AI engineer in 2026
- Photo placeholder in About section — needs a real photo
- Two project case studies marked "coming soon"

## What NOT to Touch

- Salary info — never include
- Specific employer details beyond what's already there
- The design system colors — keep consistent with apartment tracker
