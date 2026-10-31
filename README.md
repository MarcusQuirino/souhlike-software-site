# Southlike Software Site

Marketing website for Southlike Software, a software development studio.

Live: https://southlikesoftware.com

Fork of [Southlike-Software/souhlike-software-site](https://github.com/Southlike-Software/souhlike-software-site).

## Sections

The site is a single page (`src/pages/index.astro`) with anchor navigation:

- **Home** – hero with the "World Class Systems" tagline and a "Get Started" button
- **Features** ("Our Expertise") – Custom Software Development, MVP Development & Design Consulting, and AI Automation Pipelines
- **Contact** ("Get In Touch") – email link plus an inline [Cal.com](https://cal.com) scheduler for booking a 30-minute meeting

## Stack

- [Astro](https://astro.build/) 5
- [Tailwind CSS](https://tailwindcss.com/) via `@astrojs/tailwind`
- `@astrojs/sitemap` for the generated sitemap
- Cal.com embed for scheduling

## Project structure

```
src/
  layouts/Layout.astro   # HTML shell, fonts, sitemap link
  pages/index.astro      # the single page
  assets/                # logo and background pattern
public/                  # favicon, robots.txt
```

## Local development

Requires [Bun](https://bun.sh/).

```sh
bun install
bun run dev      # start the dev server at localhost:4321
bun run build    # build to dist/
bun run preview  # preview the production build
```

## TODO

See [TODO.md](TODO.md).
