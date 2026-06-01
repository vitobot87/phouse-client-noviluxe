# pHouse Client — Novi Luxe

Client site/rebuild work for Novi Luxe under the pHouse Productions website-agency workflow.

## URLs

- Client-facing review URL: https://noviluxe.demo.phouseweb.ca
- Cloudflare Pages fallback: https://noviluxe-demo.pages.dev
- Linear issue: PHO-176
- Cloudflare Pages project: `noviluxe-demo` (internal legacy project name)

## Notes

- Review URL stays on `*.demo.phouseweb.ca` until production launch.
- Visual direction intentionally stays close to the current Novi Luxe website.
- Main improvement is spam-resistant appointment form infrastructure.
- Form endpoint: `/api/contact` via Cloudflare Pages `_worker.js`.
- Current review build has no visible demo banner, but remains `noindex,nofollow` until production approval.
- Production should require Turnstile on `noviluxe.ca` / `www.noviluxe.ca` once launched.

## Agency defaults

- Repo naming: `phouse-client-{client-slug}` for client work.
- Client review/demo URLs use `https://{client-slug}.demo.phouseweb.ca`, not `pages.dev`.
- All website-agency lead/demo issues belong in the Linear `Website Agency` project.
- Every client/demo site gets a GitHub repo under `vitobot87` and the repo link goes in Linear.
