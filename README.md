# TradePulse Nepal public website

Premium static SEO site for **https://tradepulsenepal.com**.

## Publish
1. Upload all files in this folder to the root of the `tradepulse-website` GitHub repository.
2. GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)`.
3. Custom domain: `tradepulsenepal.com`.
4. Configure DNS in Cloudflare.
5. Enable Enforce HTTPS when available.
6. Add the domain to Google Search Console and submit `https://tradepulsenepal.com/sitemap.xml`.

## Updating monthly data
The public site highlights the latest Customs release. When a new month is available, update the headline numbers/product tables and sitemap modification cadence as needed. The interactive Streamlit dashboard remains the source for historical release switching.

## Architecture
- `tradepulsenepal.com` → public SEO/content layer
- `https://tradepulsenepal.streamlit.app/` → interactive dashboard


## SEO V2 (2026-09-05)
- Added a dedicated `nepal-trade-data-2083-84.html` current fiscal-year report.
- Strengthened unique page titles and meta descriptions around Nepal trade search intent.
- Added self-referencing canonicals, Open Graph/Twitter social metadata and a 1200x630 social preview.
- Added Organization, WebSite, WebPage, Breadcrumb, Article and Dataset structured data where relevant.
- Added contextual internal links to the current FY report across the core data pages.
- Updated sitemap with the new report and `lastmod` values.
- Set the custom 404 page to `noindex,follow`.

After deployment, submit the updated sitemap in Google Search Console. You only need to manually request indexing for the new FY report; Google can discover the other updated URLs through the sitemap and internal links.
