# Pedex landing — acceptance check report

Preview: https://matrixneoaiagent.github.io/pedex-landing/
Repo: https://github.com/matrixneoaiagent/pedex-landing

| Acceptance item | Evidence |
|---|---|
| Landing page exists | `index.html` at repo root; live preview returns HTTP 200. |
| Responsive | `@media (max-width: 980px)` and `@media (max-width: 560px)`; mobile-first grid and stacked form. |
| Hero: headline, subheadline, CTA | `h1#hero-title` = “Know what you own.”; `.lede` subheadline; two CTA links (`Explore the asset`, `Book a walkthrough`). |
| Features: ≥3 with title + description | Three `<article class="feature">` cards: “The underlying business”, “The evidence”, “The rights”, each with a description. |
| Contact form: name, email, message, submit | `#name`, `#email`, `#message`; `button[type=submit]`; client-side validation and `mailto:contact@pedex.org` fallback. |
| SEO title + description | `<title>Pedex — Know what you own</title>`; `<meta name="description" content="A clearer view of real-world assets…">`; OG/Twitter tags and canonical. |

Verified with a local HTML parse; live URL: HTTP 200, 22,057 bytes at 2026-11-09 09:39 UTC.
