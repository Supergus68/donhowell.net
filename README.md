# Keystone

Marketing site for the home + business technology startup, built with [Astro](https://astro.build).

## Stack

- Astro (static output)
- Plain global CSS design system (ink background, signal lime accent, mono labels)
- Google Fonts: Space Grotesk, Inter, JetBrains Mono

## Develop

```sh
npm run dev
```

## Build

```sh
npm run build
```

Output lands in `dist/`.

## Structure

- `src/pages/index.astro` — single-page site
- `src/components/` — Layout, Nav, Hero, Ticker, Services, Approach, Security, Cta, Footer
- `src/styles/global.css` — design tokens + all styles
- `public/favicon.svg` — site mark

## Notes

- Single-page marketing site for now; sections: Services, Approach, Security, Contact.
- No CMS, no backend. Contact CTA is a mailto link.
