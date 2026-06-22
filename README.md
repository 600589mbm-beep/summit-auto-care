# Summit Auto Care — premium garage website

A single-file, premium redesign of an independent auto-shop site. Trustworthy but high-end —
"modern garage meets brutalist minimalism with film-grain warmth," like a watch brand that
happens to fix cars.

**Live demo:** open `index.html` in any browser (no build step).

## Design system
- **Typography** — Clash Display (headings) + General Sans (body), via Fontshare.
- **Palette** — deep charcoal/black base (`#0b0c0e`), warm tungsten gold accents
  (`#c38a4f` / `#d8b487`), steel grays, and a single sharp red-orange (`#df4f29`)
  reserved exclusively for CTAs.
- **Texture** — ambient tungsten radial wash + SVG film-grain overlay.
- **Motion** — staggered hero entrance, IntersectionObserver scroll reveals, hover lifts
  with shadow, a continuous trust marquee. All pure CSS/JS; honors `prefers-reduced-motion`.

## Stack
- TailwindCSS (CDN) + vanilla JavaScript. **No build, no backend, one file.**

## Functionality
- 3-step booking modal (service → date/time → details → confirmation), keyboard/Escape close.
- Every section and all original copy preserved: services, tires, why-us, offers, reviews,
  journal, hours/map, mobile call bar.

## Customizing per shop
Edit the swap list in the comment at the top of `index.html`:
shop name, town, phone (update **every** `tel:` link), address, founding year, hours,
real reviews + star count, real coupons, and the Google Maps embed.

> The booking flow is a front-end demo — wire the final submit step to email/Twilio for
> a live build. Never fabricate founding years, reviews, or stats.
