# Florida Hotel: concept homepage (Nexora Tech Designs)
Static site, no build step. Files: index.html, 404.html, favicon.svg, robots.txt, sitemap.xml.

## Deploy to Vercel
1. Push this folder to a GitHub repo.
2. Vercel > Add New Project > import the repo. Framework preset: Other. Build command: none. Output directory: `.`
3. Replace `https://example.com` in index.html, robots.txt and sitemap.xml with the final domain.

## Needs management confirmation
Phone +256 704 023485 (provisional) and WhatsApp use of it; exact location (verify the Maps link); room categories, descriptions, amenities; restaurant/bar details and hours; sauna, garden, parking and Wi-Fi details; event capacity and offerings; official email; verified social links; permission to publish guest reviews; final domain.

## Photos to supply
All `.ph` slots are placeholders: hero, intro, 2 rooms, 4 dining, 4 facilities, 6 gallery, location image, Open Graph image (og.jpg). Replace with official hotel photos: put `<img src alt loading="lazy">` inside each `.ph` (hero image should not be lazy).

## Audit status
No tests have been run. Not yet performed: browser/device visual check, link and WhatsApp tests, console check, accessibility audit, Lighthouse. Still to do: real alt text and responsive image sizes once photos exist; a Google Maps embed once the location is verified.

## Config (index.html, end of file)
`CONFIG` holds the phone number, display text and optional `mapEmbed` URL. `phoneVerified` is false until management confirms. Demo build has `noindex`; remove that meta tag at launch.
