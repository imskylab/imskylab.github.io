# imskylab.github.io

The public pages served by GitHub Pages from this repository, at `https://imskylab.github.io/`.

## Skylabs (site root)

- Studio landing page: https://imskylab.github.io/ (`index.html`)

Maintained here directly. It introduces Skylabs and links to each app's pages below; it uses
`vedic-mitra/logo.png` and `legal-mitra/icon.png` (the Legal Mitra launcher icon, 512 px, from
`docs/brand/` in the private repository). It loads nothing from third parties and has no analytics.

## Vedic Mitra

- Landing page: https://imskylab.github.io/vedic-mitra/
- Privacy policy: https://imskylab.github.io/vedic-mitra/privacy/

These moved here from the `imskylab/vedic-mitra-site` repository, which served them at
`/vedic-mitra-site/`. **That old address still has to work**: the privacy-policy link is compiled
into every released build of the app — v1.0.0 through v1.1.0 all point at `/vedic-mitra-site/privacy/`
— and the Google Play listing's privacy URL must resolve for the listing to stay valid. The old
repository therefore keeps serving redirects rather than being deleted.

## Legal Mitra

- Landing page: https://imskylab.github.io/legal-mitra/
- Privacy policy: https://imskylab.github.io/legal-mitra/privacy/

Master copy: `docs/PRIVACY.md` in the private `imskylab/legal-mitra` repository;
`legal-mitra/privacy/index.html` here is its HTML rendering. Change both together, with a new
effective date. `legal-mitra/index.html` (the landing page) is maintained here directly.

## Where the source of these pages lives

The app itself is proprietary and its source is not public. The **master copies** of these two pages
live in that private repository, not here:

| Published here | Master |
| --- | --- |
| `vedic-mitra/privacy/index.html` | `docs/PRIVACY.md` (Markdown; this is the HTML rendering of it) |
| `vedic-mitra/index.html` | `docs/index.html` |
| `vedic-mitra/logo.png` | `docs/logo.png` |

Change the master and this copy together, and move the privacy policy's effective date when its
substance changes. The two had already drifted by a sentence once, which is what that instruction is
for.

`.nojekyll` is required: these are hand-written pages and Jekyll must not process them.

© 2026 Jayvardhan Potabatti. All rights reserved.
