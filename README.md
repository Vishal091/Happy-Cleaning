# Happy Cleaning website

A polished, responsive single-page marketing site for Happy Cleaning, serving South Jersey and the Philadelphia area. It uses semantic HTML, custom CSS, and lightweight vanilla JavaScript. No package install or build step is required.

## Files

- `index.html` — homepage, services, care gallery, customer-review excerpts, FAQ, service-area guidance, and WhatsApp quote flow.
- `privacy.html` — plain-language explanation of how the quote flow hands visitor-entered details to WhatsApp.
- `favicon.svg` — matching brand mark.
- `robots.txt` and `sitemap.xml` — basic search-engine discovery files.

## Visual and UX features

- Editorial home-service styling with a forest/sage/cream palette, large typography, and a responsive photo collage.
- Sticky header, scroll-progress indicator, subtle hero-image parallax, staggered section reveals, hover motion, and a scrolling brand ticker.
- Native IntersectionObserver and CSS transitions only; no animation library.
- Reduced-motion support, keyboard focus states, semantic headings, image alt text, responsive mobile contact bar, and accessible FAQ buttons.
- Canonical/social metadata and basic LocalBusiness structured data without made-up ratings, counters, or business hours.

## Run locally

Open `index.html` in a browser, or serve the repository root with any static web server.

## Quote flow

The form validates required fields and prepares a WhatsApp message for the business number published on the official site. It does not write visitor details to a website database; the visitor reviews the draft and chooses whether to send it. Phone and email contact links remain available.

## Before production launch

1. Replace illustrative stock photography with Happy Cleaning's own approved, high-quality project photos. Real before/after pairs would create stronger evidence than stock images.
2. Ask the business to review and approve the testimonial excerpts, faith-based brand language, insurance/licensing wording, service coverage, email, and contact routes.
3. Confirm the WhatsApp link from a phone and desktop and verify that messages arrive at the intended business account.
4. Connect the Vercel project to this repository's `main` branch and confirm the first deployment before attaching or changing the production domain.
5. Consider adding dedicated local landing pages once the exact service towns/ZIP codes are confirmed; do not publish unverified location pages.
6. If the business wants online scheduling or instant estimates, agree on actual availability and pricing rules before integrating a booking/calculator tool.
7. Review the privacy notice for the business's actual data-handling practices and any legal requirements before launch.

The supplied photos are illustrative references, not claims that Happy Cleaning performed the pictured work. This repository does not confirm a live production deployment or replace the currently hosted website by itself.
