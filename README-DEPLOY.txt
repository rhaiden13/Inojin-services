INOJIN SERVICES — V3 RELEASE

Files to upload at the root of the Vercel project:
- index.html — full responsive static site and 236-item service directory
- vercel.json — Vercel static output and baseline security headers
- manifest.webmanifest + sw.js + icons/inojin-mark.svg — installable PWA shell and offline navigation fallback
- robots.txt + sitemap.xml — basic search crawler discovery

V3 upgrades:
- Shareable service links: every service can have a direct URL; opening that URL opens its service detail.
- Download a CSV shortlist of services saved on the visitor's device.
- Mobile quick-quote action fixed above the bottom safe-area.
- Install-to-home-screen support where the browser allows it, plus basic offline shell caching.
- Added baseline response security headers in vercel.json.
- Existing search/filter, saved services, quotation prep, accessible keyboard focus, social profiles and explanatory service scope retained.

Deploy on Vercel: upload these files to the project root (not inside a nested folder). Use Other framework preset, no build command, output directory `.`. Re-deploy to production after upload.

Privacy and accuracy:
- This is a static website. The quote form prepares a message for review in the visitor's SMS app; it does not submit to a server or save leads in a database.
- Saved services remain in browser local storage. CSV export occurs only when the visitor clicks Download shortlist.
- No invented customer reviews, prices, booking status, certifications, or guaranteed outcomes.
- Review the actual public website on mobile after deployment.
