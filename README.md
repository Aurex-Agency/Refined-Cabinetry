# Refined Cabinetry — client demonstration

A responsive ad landing page and interactive project application, built for the client presentation. Uses supplied Refined Cabinetry photos, a labeled design rendering, and project video.

## Run

- `npm run dev` — local server on port 3000 (Python 3 required)
- `npm run build` — copies the static site into `dist`
- Vercel: build command `npm run build`, output `dist`

## Demo behavior

All calls to action open a three-step application (project type; location/budget/timeline; sample contact details), then a project recap and illustrative booking/confirmation flow. No form endpoint, CRM, calendar, marketing tracking, uploads, or persistent lead storage is connected. Data exists only in memory and resets on modal close. Calendar slots are examples, not real appointments. Search indexing is disabled in HTML and response headers.

## Before a live campaign

Confirm offer/design terms, pricing ranges, service eligibility and approved project media with Refined. Connect the approved CRM and actual booking availability; replace demo text with consent/privacy information appropriate to the real integration. Add attribution and conversion measurement only after configuration and testing. Enable indexing only if appropriate for the paid funnel.

## Asset sources

Client-supplied Drive folder: 1J9sIG_BdCG4j8ttUZuRUFKMuItiSgdkL.
- green-kitchen.webp: IMG_5459.JPG
- kitchen.webp: IMG_5457.jpg
- detail.webp: IMG_5458.JPG
- built-ins.webp: IMG_5460.JPG
- design.webp: Screenshot 2026-10-26 163523.png (labeled rendering)
- 10676.mp4: supplied project video

Images compressed to WebP without generative editing. Fonts: DM Sans via Google Fonts, Georgia system serif fallback.

## Validation

JavaScript syntax and static build checked. Application exercised in browser from project selection through sample booking confirmation, using fictional contact information.
