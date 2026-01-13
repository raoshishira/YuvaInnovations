# Yuva Innovations - Knowledge Base

## Project Overview
Yuva Innovations is a modern, high-performance website built with **Astro 5**. It features a clean, professional design with interactive elements powered by GSAP. The project supports internationalization (i18n) for English and Italian and is optimized for deployment on Cloudflare Pages.

## Tech Stack
- **Framework**: [Astro 5](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animations**: [GSAP](https://gsap.com/)
- **Runtime/Package Manager**: [Bun](https://bun.sh/)
- **Deployment**: [Cloudflare Pages](https://pages.cloudflare.com/)
- **Icons**: [Astro-icon](https://github.com/natemoo-re/astro-icon)
- **Content**: MDX with Astro Content Collections

## Key Features
- 🌍 **Internationalization (i18n)**: Support for multiple languages (EN, IT) located in `src/pages/it` and coordinated via `astro.config.mjs`.
- ✍️ **Content Collections**: Managed schemas for Blog Posts, Projects, and Authors in `src/content`.
- 🎨 **Rich Aesthetics**: 
  - Blob animations and custom cursor followers.
  - Grainy gradients and background textures.
  - Responsive design using Tailwind's typography and aspect-ratio plugins.
- 🚀 **SEO & Performance**: 
  - Sitemap generation.
  - MDX support for rich content.
  - BaseHead component for meta tags.
- 🛠️ **Integrations**: Tailwind, Sitemap, MDX, and Icon integrations configured in `astro.config.mjs`.

## Directory Structure
- `/src/pages`: Website routes and localized versions.
- `/src/components`: UI components categorized by section (landing, blog, global, etc.).
- `/src/content`: Markdown/MDX content and schemas (`config.ts`).
- `/src/i18n`: Translation logic and strings.
- `/src/layouts`: Page templates.
- `/src/styles`: Global CSS.
- `/functions`: Cloudflare Pages functions (e.g., mail handled via MailChannels).
- `/public`: Static assets, including the logo and PWA assets.

## Recent Updates
- [2026-01-13] **Contact Email Updated**:
  - ✅ Changed all contact email instances to `yuvainnovations@gmail.com` (Footer, Terms, Privacy).
- [2025-12-22] **Package Updates Completed**: All packages updated to latest stable versions:
  - **Astro**: 5.12.6 → 5.16.6
  - **@astrojs/mdx**: 4.3.1 → 4.3.13
  - **@astrojs/rss**: 4.0.12 → 4.0.14
  - **@astrojs/sitemap**: 3.4.2 → 3.6.0
  - **GSAP**: 3.12.7 → 3.14.2
  - **Tailwind CSS**: 3.4.1 → 3.4.19 (latest v3, v4 deferred due to build compatibility)
  - **Sharp**: 0.33.5 → 0.34.5
  - **Prettier**: 3.5.2 → 3.7.4
  - **Prettier Tailwind Plugin**: 0.6.11 → 0.7.2
  - **Unlighthouse**: 0.15.0 → 0.17.4
  - **@tailwindcss/forms**: 0.5.10 → 0.5.11
  - **@tailwindcss/typography**: 0.5.16 → 0.5.19
  - **@vite-pwa/assets-generator**: 0.2.6 → 1.0.2
  - **@iconify-json/ic**: 1.2.2 → 1.2.4
  - **@iconify-json/octicon**: 1.2.5 → 1.2.19
  - **@cloudflare/workers-types**: 4.20250214.0 → 4.20251221.0
  - Build verified successful ✅
- [2025-12-22] Initialized `GEMINI.md` for project tracking and reference.
- [2025-12-22] **Content Rebrand Implementation - Phase 2 Completed**:
  - ✅ Created new `WhyChooseUs.astro` component with 6 key differentiators
  - ✅ Updated `Facts.astro` component with accurate Yuva Innovations stats:
    - 10+ Happy Clients
    - 5+ Websites Developed
    - 12+ Brands Supported
    - 20+ Projects Completed
  - ✅ Added English i18n translations for WhyChooseUs section
  - ✅ Updated homepage (`index.astro`) to include new components in logical flow:
    - Hero → Services → WhyChooseUs → Facts → WorkPreview → Tagline → FAQ
  - ✅ Build verified successful
  - **Pending**: Italian translations, About page update, final testing


---
*This file is updated periodically by the Antigravity AI assistant.*
