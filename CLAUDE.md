# XIBBIX Sports Entertainment — Website

## Project
Single-page marketing website for Xibbix Sports Entertainment (XSE).
File: `index.html` (self-contained — all CSS and JS are inline)

## Brand Guide
- **Background:** `#1B1A1A`
- **Peach:** `#ffbd59`
- **Red:** `#ff3131`
- **Cream:** `#fffff1`
- **Title font:** Anton (Google Fonts)
- **Body font:** Poppins (Google Fonts)

## Assets
- `XIBBIX Logo.png` — brand logo (red + peach X mark)

## External Dependencies (CDN)
- Google Fonts — Anton + Poppins
- Phosphor Icons `@phosphor-icons/web@2.1.1` — duotone icons in verticals grid
- Unsplash — placeholder images (to be replaced with real event photography)

## Sections (top to bottom)
1. Nav (sticky, mobile-responsive)
2. Hero — full viewport, line-by-line headline reveal
3. Ticker — scrolling marquee
4. About / Who We Are — stats counter animation
5. Vision & Mission
6. Six Verticals grid — 3D card tilt on hover
7. Sports IP Creation — full-bleed MMA image with parallax
8. Sports Marketing — portfolio list
9. Sports Charity — UNICEF event card
10. Xibbix Sports World — tourism image grid
11. Sports Tech — pulsing orb
12. Live Entertainment — full-bleed concert image
13. Team — country stats + sports strip
14. CTA — closing section
15. Footer / Contact

## Animations
- Hero: clip-mask line-by-line reveal (ease-out-expo, staggered)
- Scroll reveals: fade + translate, ease-out-expo 750ms
- Tag labels: line draws left-to-right on enter
- Stat counters: count-up on scroll into view
- Verticals cards: 3D perspective tilt on mousemove
- Parallax: Sports IP background image only
- Progress bar: 2px peach fixed bar at top tracking scroll depth
- Respects `prefers-reduced-motion`

## Contacts
- +91 98200 11 056
- info@xibbix.in
- www.xibbix.com | xibbix.tv
- Offices: Mumbai · Dubai · London
