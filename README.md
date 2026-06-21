# Free Next.js 15 Personal Portfolio / CV Template — Tailwind CSS, Multi-Page, TypeScript

A clean, minimal, production-ready personal portfolio and CV template built with **Next.js 15**, **Tailwind CSS v3**, and **TypeScript**. Deploy to Vercel in minutes. Fully customize every word and link by editing a single config file.

**Live Demo:** [https://20-personal-cv.vercel.app](https://20-personal-cv.vercel.app)

![Portfolio Template Preview](./preview-full.png)

---

## Features

- **Multi-page layout** — Home, About, Portfolio, Blog, Contact (each as a dedicated route)
- **Single-file customization** — all content lives in `src/data/config.ts`; no need to hunt through components
- **Working contact form** — API route included, drop-in ready for your email provider
- **Static Site Generation (SSG)** — blazing-fast, zero server cost, deploys perfectly on Vercel / Netlify / GitHub Pages
- **SEO-ready** — per-page `<title>` and `<meta description>` generated from config
- **TypeScript strict mode** — zero `any`, fully typed config
- **Tailwind CSS v3** — utility-first, dark-mode-friendly, easy to restyle
- **Zero JS framework lock-in for content** — swap real CMS data into the typed config shapes when you need to scale
- **Responsive** — mobile-first grid, tested at 375 px → 1440 px
- **Accessibility** — semantic HTML, keyboard navigable, WCAG AA contrast

---

## Quick Start

### 1. Clone

```bash
git clone https://github.com/cekuu35/free-nextjs-cv-template.git my-portfolio
cd my-portfolio
```

### 2. Install

```bash
npm install
```

### 3. Develop

```bash
npm run dev
# Open http://localhost:3000
```

### 4. Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/cekuu35/free-nextjs-cv-template)

Or push to GitHub and import in [vercel.com/new](https://vercel.com/new) — no extra configuration needed.

---

## Customize in One File

Open `src/data/config.ts` and edit the exported constants:

| Constant | What it controls |
|---|---|
| `SITE` | Name, title, tagline, bio, email, location, availability badge |
| `NAV_LINKS` | Top navigation items |
| `SOCIAL_LINKS` | GitHub, LinkedIn, Dribbble, Read.cv, Twitter — add/remove freely |
| `SKILL_GROUPS` | Skill tag groups on the About page |
| `EXPERIENCE` | Work history timeline |
| `EDUCATION` | Education timeline |
| `CERTIFICATIONS` | Optional certifications row |
| `PROJECTS` | Portfolio cards with slug, tags, gradient, live URL |
| `BLOG_POSTS` | Inline markdown blog content with tags and reading time |

Every page reads from this single source of truth — update once, reflect everywhere.

---

## Project Structure

```
src/
  app/
    page.tsx          # Home (hero + featured projects)
    about/            # About, experience, skills, education
    portfolio/        # Project grid + individual project pages
    blog/             # Post list + individual post pages
    contact/          # Contact form (API route at app/api/)
    layout.tsx        # Root layout — NavBar + Footer
  components/
    NavBar.tsx
    Footer.tsx
    ContactForm.tsx
  data/
    config.ts         # ← Edit this file only
```

---

## Tech Stack

| Layer | Choice |
|---|---|
| Framework | Next.js 15 (App Router) |
| Language | TypeScript 5 (strict) |
| Styling | Tailwind CSS v3 |
| Deployment | Vercel (one-click) |
| Node | 18+ |

---

## License

MIT — free for personal and commercial use. See [LICENSE](./LICENSE).

---

## Need a ready-made business site?

This template is a taste of the full collection. If you need a **production-ready site for a real business** — not just a personal CV — check out the premium pack:

### 20 Premium Next.js + Tailwind Templates — $49 each or all 20 for $299

Includes complete, deployable sites for:

| # | Template | Type |
|---|---|---|
| 01 | Modern SaaS Landing | SaaS / startup |
| 02 | AI Startup | AI product landing |
| 03 | Digital Agency | Creative agency |
| 04 | Restaurant & Cafe | Food & beverage |
| 05 | Real Estate | Property listings |
| 06 | Fitness & Gym | Health & wellness |
| 07 | E-Commerce Store | Product / shop |
| 08 | Online Course | EdTech / creator |
| 09 | Dental Clinic | Medical / local service |
| 10 | Restaurant Reservation | Booking-focused food |
| 11 | Barber & Salon | Local service |
| 12 | Photography Portfolio | Creative portfolio |
| 13 | Event & Conference | Events / ticketing |
| 14 | Web3 & Crypto | Blockchain / DeFi |
| 15 | Mobile App Landing | App marketing |
| 16 | Newsletter & Creator | Content creator |
| 17 | Hotel Booking | Hospitality |
| 18 | Construction Company | Trade / B2B |
| 19 | Law Firm | Professional services |
| 20 | Personal CV (this one) | Personal / freelance |

Every template: TypeScript, App Router, Tailwind CSS, fully responsive, Vercel-deployable, single-config customization.

**Get the full bundle → [cenkkurtoglu.com](https://cenkkurtoglu.com)**

Full showcase with live demos for all 20 templates:  
**[github.com/cekuu35/nextjs-website-templates](https://github.com/cekuu35/nextjs-website-templates)**

Questions? Open an issue or reach out via the site.
