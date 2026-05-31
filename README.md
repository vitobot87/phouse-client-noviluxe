# Novi Luxe Demo

Client-facing demo for Novi Luxe, built under the pHouse Productions website-agency workflow.

## URLs

- Client-facing demo: https://noviluxe.demo.phouseweb.ca
- Cloudflare Pages fallback: https://noviluxe-demo.pages.dev
- Linear issue: PHO-176

## Notes

- Demo is `noindex,nofollow` and includes an unofficial concept banner.
- Visual direction intentionally stays close to the current Novi Luxe website.
- Main improvement is spam-resistant appointment form infrastructure.
- Form endpoint: `/api/contact` via Cloudflare Pages `_worker.js`.
- Production should require Turnstile on `noviluxe.ca` / `www.noviluxe.ca` once launched.

## Agency defaults

- Client-facing demos use `https://{client-slug}.demo.phouseweb.ca`, not `pages.dev`.
- Outreach uses `vito@phouseweb.ca` with Mike CC'd.
- All lead/demo work belongs in the Linear `Website Agency` project.
