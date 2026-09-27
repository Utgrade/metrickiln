# MetricKiln landing page V3 — SEO-ready

This package is the SEO/conversion update of the current MetricKiln landing page.

## Upload now

Upload or replace these files in the root of the public GitHub repository:

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `assets/` (the five existing dashboard screenshots)

Keep the existing `license.html`.

The public canonical URL remains:

`https://utgrade.github.io/metrickiln/`

## Lemon Squeezy placeholder

The two purchase buttons intentionally still use:

`LIVE_CHECKOUT_URL`

Do **not** replace it until the Lemon Squeezy live store is approved.

After approval:
1. Copy the validated test product to Live Mode.
2. Verify the live product and attached ZIP.
3. Copy the permanent Lemon Squeezy live `/checkout/buy/...` URL.
4. Replace both occurrences of `LIVE_CHECKOUT_URL` in `index.html`.
5. Change the checkout status text from the approval message to a short purchase reassurance, e.g. `Secure checkout and digital delivery via Lemon Squeezy.`
6. Add an `offers` object to the Product JSON-LD only when the product can actually be purchased live.

Recommended live `offers` object:

```json
"offers": {
  "@type": "Offer",
  "url": "https://utgrade.github.io/metrickiln/",
  "price": "49.00",
  "priceCurrency": "USD",
  "availability": "https://schema.org/OnlineOnly",
  "itemCondition": "https://schema.org/NewCondition"
}
```

## SEO work included

- Descriptive `<title>` focused on Power BI + PMO dashboard template intent.
- Search-oriented meta description.
- Canonical URL.
- Robots indexing directive.
- Open Graph and Twitter metadata with absolute image URLs.
- Product JSON-LD without a live Offer while checkout is unavailable.
- More descriptive image alt text.
- Explicit image dimensions and lazy loading for gallery images.
- Natural on-page language around:
  - Power BI PMO dashboard template
  - project portfolio dashboard
  - PMO reporting
  - Excel to Power BI workflow
- `robots.txt`
- `sitemap.xml`

## Public support

`metrickiln@outlook.com`
