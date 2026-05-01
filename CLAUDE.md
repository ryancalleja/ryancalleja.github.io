# CLAUDE.md — Ryan Calleja Portfolio Website

This file gives Claude Code full context on this project. Read it before making any changes.

---

## Project Overview

A personal portfolio / consultancy landing site for **Ryan Calleja**, an Engineering Leadership Consultant based in Malta. The goal is to establish a professional online presence, get indexed by Google and LLMs, and attract inbound consultancy enquiries.

**Target audience:** CTOs, VPs of Engineering, Founders at tech startups and scale-ups who need help with engineering team transformation, fractional EM coverage, or growth engineering.

---

## Tech Stack

- **Single file:** `index.html` — pure HTML/CSS/JS, no framework, no build step
- **Hosting:** GitHub Pages (`ryancalleja.github.io` repo)
- **Custom domain:** `ryancalleja.com` (or equivalent — check DNS is live)
- **Fonts:** DM Serif Display (headings) + DM Sans (body) via Google Fonts
- **No dependencies** beyond Google Fonts CDN

---

## Site Structure

The site is a **single HTML file** with two "pages" toggled via JavaScript:
- `#home` section — Landing page
- `#contact` section — Contact page

Navigation between pages is handled by `showPage('home')` and `showPage('contact')` JS functions.

---

## Design System (do not change without good reason)

| Token | Value |
|---|---|
| `--ink` | `#1a1814` (primary text) |
| `--ink-mid` | `#4a4740` (body text) |
| `--ink-soft` | `#8a8680` (captions, labels) |
| `--paper` | `#f7f4ef` (page background) |
| `--paper-warm` | `#efe9df` (section backgrounds) |
| `--accent` | `#c45c2a` (burnt orange — primary accent) |
| `--accent-light` | `#f0d4c2` (light orange fills) |
| `--green` | `#2a6b4a` (availability badge) |
| `--green-light` | `#d4ede0` (green fills) |

**Typography:** DM Serif Display for all headings and display numbers. DM Sans 300/400/500 for body. Never use Inter, Roboto, or system fonts as primary.

**Aesthetic:** Warm editorial — think consultancy meets craft magazine. Not corporate. Not startup-purple. Earthy, confident, human.

---

## Ryan Calleja — Key Facts & Content

### Contact
- Email: callejaryan@gmail.com
- Phone: +356 79 251 409
- LinkedIn: https://mt.linkedin.com/in/ryncalleja
- Location: Malta (CET) — remote-native

### Career Summary
- 14 years software engineering experience
- 4+ years engineering leadership (since 2020)
- BSc 1st Class Hons — Internet Applications Development
- Career break 2017–18: volunteered supporting children in third-world countries

### Key Roles
| Role | Company | Period |
|---|---|---|
| Engineering Manager (B2B/B2B2C) | Airalo | May 2025 – Current |
| Engineering Manager (Growth Tribe) | Hotjar | May 2023 – April 2025 |
| Software Engineer (Growth Tribe) | Hotjar | May 2022 – May 2023 |
| Senior Full Stack Engineer | Pixel.bet | Oct 2018 – April 2022 |
| Senior Full Stack Engineer | Tipico | Aug 2015 – Jun 2017 |
| Fullstack Developer | YoBetit | Jun 2013 – Jul 2015 |
| Web/Mobile Developer | Betclic Expekt | May 2012 – Jun 2013 |
| Junior Software Developer | iCube+ | Oct 2009 – Mar 2011 |

### Proven Metrics (verified, use accurately)
- **95%** sprint completion rate — Airalo, after transforming chaotic workflows (8-person squad)
- **–20%** integration support tickets — Airalo, via scalable partner onboarding fixes
- **+10.05%** paid conversion — Hotjar, in 3 months via cross-selling trial strategy
- **Elite** DORA metrics — Hotjar, ~10 deployments/week sustained
- **+46%** website performance score — Hotjar, hotjar.com (NextJS, LCP/CLS improvements)
- **0** engineer attrition during 3-way company merger — Hotjar

### Consultancy Pillars (4 services offered)
1. **Team Transformation** — dysfunctional → high-performing, done at Airalo and Hotjar
2. **Fractional Engineering Manager** — part-time EM/VP Eng coverage for startups
3. **Growth Engineering Audit** — funnel, performance, conversion optimisation
4. **B2B Integration Advisory** — partner ecosystems, public APIs, observability

### Tech Stack Knowledge
- Languages: JavaScript, TypeScript, Java, Python
- Frameworks: React, NextJS, VueJS, Node.js, Spring/Hibernate, AngularJS
- Databases: MySQL, MongoDB, PostgreSQL, Redis
- Infra/Ops: DataDog, Sentry, Jenkins, Bamboo, GCP, RabbitMQ/Kafka
- Tools: Mixpanel, Heap, LinearB, Atlassian, Git

---

## Where We Left Off (conversation context)

This site was built in a Claude.ai conversation in May 2025. The conversation covered:

1. Resume analysis and consultancy positioning
2. Stack recommendation (GitHub Pages + custom domain, single HTML file)
3. Domain advice: `ryancalleja.com` on Namecheap recommended
4. Full site build: landing page + contact page, mobile-first

### What still needs doing (content refresh)
- [ ] Add **LinkedIn recommendations** as a Testimonials section once exported
- [ ] Add **Airalo performance review feedback** to enrich the Results section
- [ ] Replace contact form with a real submission backend (suggested: Formspree or Netlify Forms — free tier)
- [ ] Add a **Calendly booking link** to replace or supplement the contact form
- [ ] Consider adding `robots.txt` and `sitemap.xml`
- [ ] Add a blog/writing section for longer-term SEO and LLM indexing

---

## Instructions for Claude Code

When updating this site:

1. **Preserve the single-file structure** — everything stays in `index.html`
2. **Do not introduce a framework or build step** — this is intentionally simple
3. **Do not change the design tokens** unless Ryan explicitly asks
4. **All metrics must be accurate** — do not invent or round up numbers
5. **Mobile-first** — test all changes at 375px width mentally before committing
6. **When adding a Testimonials section**, place it between the Results section and the CTA band
7. **Form backend:** if wiring up the contact form, use Formspree (`https://formspree.io`) — free, no server needed, just swap the form action attribute
8. **Google Fonts** are loaded via CDN — do not self-host unless Ryan asks
