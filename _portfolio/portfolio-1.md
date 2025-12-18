---
title: "Bosons Web — Documentation Summary"
excerpt: "Summary of Bosons Web documentation (architecture, stack, UX flows, and deployment).<br/><img src='/images/bosons-logo.png'>"
collection: portfolio
---

This portfolio entry summarizes the documentation for **Bosons Web**, based on the project docs in:
https://github.com/titanioco/Bosons-web/blob/copilot/create-documentation-description/DOCUMENTACION.md

## Project overview

Bosons Web is a modern, bilingual (ES/EN) web platform for an industrial supplies company in Colombia. It’s designed as a fast, responsive storefront and information hub, enabling visitors to explore products/services, request quotes, contact the business, and complete payments via Stripe.

## Key features

- Bilingual experience (Spanish/English)
- Light/dark theme toggle (with system preference detection)
- Responsive, mobile-first UI
- Product catalog with filtering and category navigation
- SEO-ready meta, Open Graph, and structured data
- Stripe checkout/payment integration

## Tech stack

- React + TypeScript
- Vite (fast dev server + optimized builds)
- Tailwind CSS
- shadcn/ui + Radix UI primitives
- React Router, React Hook Form + Zod, TanStack Query
- Optional integrations mentioned in docs (e.g., Supabase, Google Generative AI)

## Architecture highlights

- Component-based structure (`src/components/features`, `src/components/layout`, `src/components/ui`)
- Context for language/theme; additional state handled with Redux Toolkit / Zustand where needed
- SPA-style navigation with section anchors (services, products, materials, automation, welding, contact)

## Dev workflow (high level)

- Install dependencies and run dev server (`npm install`, `npm run dev`)
- Lint/type-check as part of the workflow
- Production build via `npm run build` and static hosting options (e.g., Vercel/Netlify)

If you want, I can also add a second portfolio entry linking to the live site and a short “how to run locally” quickstart.
