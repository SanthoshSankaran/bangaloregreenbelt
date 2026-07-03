# Bangalore Green Belt (BGB) — Lead Landing Page

Standalone SEO-optimised enquiry page for **Bangalore Green Belt**: villa plots, farm plots, approved layouts, and gated communities near Sarjapur, Bengaluru. Featured project: **Lawnsview**.

Static HTML + Tailwind CDN + Formspree. Deployed at [unrivaled-rugelach-78efed.netlify.app](https://unrivaled-rugelach-78efed.netlify.app/).

## Before deploy / after domain change

1. **Domain** — Replace `unrivaled-rugelach-78efed.netlify.app` in:
   - `index.html` → canonical, hreflang, OG/Twitter URLs, JSON-LD `@id`s
   - `robots.txt` → Sitemap URL
   - `sitemap.xml` → `<loc>`

2. **WhatsApp (post-submit only)** — In `index.html`:
   ```html
   <script>window.SITE_CONFIG = { whatsapp: '919876543210' };</script>
   ```

3. **Formspree** — Form action: `https://formspree.io/f/xkoawavo`. Test after deploy.

4. **Google Search Console** — Add property, submit sitemap, request indexing.

## SEO checklist (built in)

- Title, meta description, keywords, geo tags, robots directives
- Canonical URL + hreflang `en-in`
- Open Graph + Twitter Card tags
- JSON-LD: Organization, WebSite, WebPage, RealEstateListing (Lawnsview), FAQPage
- Semantic HTML: `<main>`, section headings, `aria-labelledby`, footer nav
- Keyword-rich image alt text
- FAQ section aligned with schema
- `robots.txt` + `sitemap.xml`
- Hero RSA headline rotator (15 ad-aligned headlines) — stable H1 for crawlers

## Local preview

```bash
python3 -m http.server 8080
```

## Form fields

| Field | Required |
|-------|----------|
| Interest type | Yes — General BGB / Lawnsview / Villa notify / Layout notify / Gated notify |
| Name, phone | Yes |
| Budget, timeline | Yes |
| Best time to call | Optional |

Form subject line: `BGB lead — [interest]`

## Lead workflow

1. Visitor finds page via SEO/ads  
2. Submits BGB enquiry form  
3. Formspree emails you  
4. Callback within **36–48 hours**  
5. Qualify → site visit (Lawnsview) → offline close  

## Assets

- Logo: `assets/bgb-logo.png`
- Lawnsview images: hotlinked from [lawnsview.com](https://lawnsview.com/)

## Target keywords (on-page)

Villa plots Bangalore, farm plots near Sarjapur, farmhouse plots Bangalore, gated green community, peri urban villa plots, villa plots Electronic City, villa plots Whitefield, Bangalore green living, Lawnsview, smart land investment, weekend farm property.
