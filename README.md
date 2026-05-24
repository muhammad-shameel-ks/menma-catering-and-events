# Menma Catering & Events

A premium landing page for a high-end wedding and event planning company based in Palakkad, Kerala, India.

Built with **Astro** (static output), styled with plain CSS custom properties, and run with **Bun**.

## Tech Stack

- **Framework:** Astro (static site)
- **Runtime:** Bun
- **Styling:** Plain CSS with CSS custom properties
- **Fonts:** Google Fonts (Cormorant Garamond, Great Vibes, Jost)

## Commands

| Command | Action |
| :------ | :----- |
| `bun install` | Install dependencies |
| `bun dev` | Start dev server at `localhost:4321` |
| `bun build` | Build to `./dist/` |
| `bun preview` | Preview production build locally |

## Project Structure

```
src/
  pages/
    index.astro
  components/
    Navbar.astro
    Hero.astro
    Stats.astro
    About.astro
    Services.astro
    WhyUs.astro
    Gallery.astro
    Testimonials.astro
    Contact.astro
    Footer.astro
  styles/
    global.css
public/
  images/
  videos/
```

## Sections

- **Navbar** — Fixed top, CSS-only hamburger, scroll blur, gold accents
- **Hero** — Full-viewport video playlist (auto-cycling, 10s segments), mobile static fallback
- **Stats** — Count-up animation, brand texture background
- **Services** — Collapsible accordion with 5 categories (19 services total)
- **About** — Split layout, gold-framed image, pull quote
- **Why Us** — Split typography, 3 feature blocks, dark textured background
- **Gallery** — Masonry grid with video cards, hover overlay
- **Testimonials** — 3 Kerala client reviews with star ratings
- **Contact** — Contact info with social links
- **Footer** — Logo, tagline, nav, social icons
