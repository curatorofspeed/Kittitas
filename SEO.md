# SEO — Kittitas County

## Done (on the site)
- **Optimized title + meta** describing services + location.
- **LocalBusiness structured data** (JSON-LD) on the homepage with `areaServed` covering
  Kittitas County and every town, your phone, and map coordinates.
- **Geo + Open Graph tags** so the site is geotagged to Cle Elum and previews well when shared.
- **Two local landing pages** with their own titles, descriptions, and Service schema:
  - `web-design-kittitas-county.html`
  - `3d-tours-cle-elum.html`
  - Linked to/from the homepage (Coverage section + footers) so Google can crawl them.
- **`sitemap.xml`** and **`robots.txt`** at the site root.

## Do after deploy (5 minutes)
1. **Google Search Console** — search.google.com/search-console. Add your property
   (`kittitasdigital.com`), verify (Cloudflare makes this one click via DNS), then
   **submit `https://kittitasdigital.com/sitemap.xml`** under Sitemaps. This is how Google
   discovers and tracks your pages.
2. **Bing Webmaster Tools** — bing.com/webmasters. Same idea; you can import from Search
   Console in one step. (Bing also feeds some AI search results.)

## Still on you (the big levers — 1–3 from our chat)
1. **Google Business Profile** — google.com/business. The single most important thing for
   local "near me" / map-pack results. Set it up as a **service-area business** covering
   Kittitas County, pick the right primary category, add phone/hours/photos, and verify.
2. **Reviews** — ask every happy client (start with Lapiers Painting) for a Google review
   that names the service + town. This drives both ranking and trust.
3. **NAP consistency** — same Name / Area / Phone everywhere: GBP, site, Facebook, Bing
   Places, Apple Business Connect, the Cle Elum & Kittitas County Chamber, Yelp.

## Before going live — update the URL
The pages, sitemap, and schema all assume `https://kittitasdigital.com`. If your live domain
ends up different, find-and-replace that URL across `index.html`, the two landing pages,
`sitemap.xml`, and `robots.txt`.

## Adding more local pages later
Two strong pages beat twenty thin ones. Google penalizes near-duplicate "doorway" pages, so
only add a new one when it has genuinely different content (a real service or a real audience),
not just the same page with a town name swapped.
