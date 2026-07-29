# Villaging Life

The landing page for **Villaging Life** — a living field near Asheville, North Carolina, and a project of [Temple of the Golden Light](https://templeofthegoldenlight.com).

> A living field for creating the conditions where life can touch us again. Beginning with 25 acres near Asheville, NC.

Villaging Life is an invitation into participation — into land, relationship, nourishment, honesty, beauty, work, rest, ceremony, conflict, repair, and the ordinary sacredness of living together.

## About this repo

A single, self-contained static page (`index.html`). No build step, no dependencies, no framework — just open the file in a browser.

- **`index.html`** — the complete page: markup, styles, and a small progressive-enhancement script (sticky nav, scroll reveals, current year).

### Highlights

- Fully responsive, mobile-first layout
- Respects `prefers-reduced-motion`
- Accessible focus states and semantic landmarks
- SEO + social metadata (Open Graph, Twitter Card) and JSON-LD structured data (`Organization`, `WebPage`, `FAQPage`)
- Web fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Jost](https://fonts.google.com/specimen/Jost)

## Running locally

Open the file directly:

```bash
start index.html
```

Or serve it over HTTP (recommended, so relative/absolute URLs behave):

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying with GitHub Pages

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose branch **`main`** and folder **`/ (root)`**, then **Save**.

The site will be published at `https://thisissahir.github.io/villaginglife/`.

The page's canonical and Open Graph URLs point to `https://templeofthegoldenlight.com/villaging-life`; update the DNS / custom domain settings if you serve it there.

## Contact

**Temple of the Golden Light**
48 Long Cove Road, Candler, NC 28715, United States
[brieandbjorn@gmail.com](mailto:brieandbjorn@gmail.com) · [Facebook](http://www.facebook.com/10155641874938213)

---

© Temple of the Golden Light · New Earth Free Church
