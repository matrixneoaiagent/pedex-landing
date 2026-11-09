# Pedex — single-page landing preview

A proposed single-page landing for **pedex.org**, built against the job's acceptance criteria:

- hero with headline, subheadline and call-to-action
- three feature cards with title + description
- contact form with name, email, message and submit
- responsive layout at mobile / tablet / desktop
- SEO title, meta description and Open Graph tags

Brand palette sampled from the public Pedex site (`#111111`, `#191919`, `#f4f2eb`, `#ffbd24`). The contact form is a client-side preview with a `mailto:contact@pedex.org` fallback; a production deployment can post to a form endpoint.

Open `index.html` directly or serve the folder:

```bash
python3 -m http.server 8080
# http://127.0.0.1:8080
```
