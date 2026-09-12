<div align="center">
  <img src="public/icon512x512.jpg" alt="FlickClean logo" width="140" />
  <h1>FlickClean</h1>
  <p><b>Swipe your photo gallery clean and free up storage in minutes.</b><br/>The Next.js marketing site for FlickClean — hero, feature sections, blog and legal pages (not the mobile app itself).</p>
  <p>
    <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
    <img alt="Next.js" src="https://img.shields.io/badge/Next.js-16-black?logo=nextdotjs">
    <img alt="React" src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-4-38BDF8?logo=tailwindcss&logoColor=white">
    <img alt="Framer Motion" src="https://img.shields.io/badge/Framer_Motion-0055FF?logo=framer&logoColor=white">
  </p>
</div>

---

Marketing website for **FlickClean** — a phone gallery cleanup app that lets you
swipe through your photos and free up storage in minutes instead of hours. This
repo is the Next.js landing site (hero, feature sections, blog, and legal pages),
not the mobile app itself.

## Features

- Landing page composed of modular sections (hero, impact, problems, solution,
  feature visual, trust, why-FlickClean, call-to-action, blog preview)
- Blog with individual post pages (`/blog/[slug]`)
- Static support, contact, privacy, and terms pages
- SEO metadata, Open Graph / Twitter cards, `robots.ts` and `sitemap.ts`
- Google Analytics and Vercel Analytics with custom scroll-depth and session
  tracking
- Animations via Framer Motion; UI built with Radix / shadcn primitives

## Tech Stack

- **Framework:** Next.js 16 (App Router) + React 19
- **Language:** TypeScript
- **Styling:** Tailwind CSS v4, `tailwind-merge`, `class-variance-authority`
- **UI:** Radix UI / shadcn, lucide-react icons, Framer Motion
- **Analytics:** Google Analytics (`@next/third-parties`), Vercel Analytics

## Getting Started

```bash
# install dependencies (pnpm, npm, or yarn)
pnpm install

# run the dev server
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Configuration

Optional environment variables:

- `NEXT_PUBLIC_SITE_URL` — canonical site URL (defaults to `https://flickclean.app`)
- `NEXT_PUBLIC_GA_ID` — Google Analytics measurement ID

## Build

```bash
pnpm build && pnpm start
```

## Project Structure

```
app/            # App Router pages (landing, blog, contact, privacy, terms, support)
components/     # landing sections, analytics, and UI components
lib/            # analytics helpers and utilities
public/         # static assets
```

## License

Released under the [MIT License](LICENSE) © 2026 Olivier Lüthy. You're free to use, modify and distribute this
software, including commercially, as long as the copyright notice and license are included.

## Author

Built by **Olivier Lüthy** — [GitHub](https://github.com/olivierluethy).
