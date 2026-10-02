# MD Projects NZ website

Single-page website for MD Projects NZ (mdprojects.co.nz), "From plan to reality".

- `index.html`: the whole site (HTML, CSS and JavaScript). Animations use GSAP, ScrollTrigger and Lenis from public CDNs.
- `images/`: the logo, project photos and hero video (`hero.webm`, `hero.mp4`).

It's a static site with no build step. Vercel serves `index.html` from the repository root.

## Before going live
- Connect the quote form to a form handler. For now it only shows a thank-you message.
- Replace `images/logo.png` with the original logo file (ideally SVG).
- Confirm the homes-built figure (1,000+).
