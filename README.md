# PVTworks website
Original, responsive Vite-powered industrial website inspired by the broad information architecture of FloWorks. No FloWorks logos, photos, or copy are included.

## Run locally
Install Node.js 20+; run `npm install` then `npm run dev`.

## Deploy to Cloudflare Pages
Push this directory to a GitHub repository. In Cloudflare Pages choose Connect to Git, select repository, use build command `npm run build`, output directory `dist`, and deploy. The `public/_redirects` file supports SPA routing.

## Before production
- Replace `REPLACE_WITH_CONFIRMED_EMAIL` in src.js with your verified PVTworks business email address, or preferably integrate a server-side form handler with validation, spam protection and privacy notices.
- Confirm actual offered products/services, business identity, contacts, manufacturer authorizations and compliance statements.
- Replace illustrative CSS-only hero with properly licensed industrial photography if desired.
- Add legally reviewed privacy policy and terms as applicable.
- Test quote handling and contact links before publishing.

This is a functional frontend demo; the RFQ button prepares a mailto draft and does not submit data to a server.

## Image updates
Original generated industrial imagery is stored in `public/images/` and served locally. Company: rotating equipment; Expertise: large valves and technical experts; Products & Services: valve operator. Removed the catch-all `_redirects` rule that Cloudflare rejected with error 100324.
