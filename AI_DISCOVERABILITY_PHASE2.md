# TradePulse Nepal — AI Discoverability Phase 2

Production update dated 2026-09-06.

## Changes
- Preserves the Phase 1 crawler policy and llms.txt.
- Standardizes export growth at 61.72% across the package.
- Connects Organization, WebSite, WebPage, Article, DataCatalog, Dataset and DataDownload entities with stable @id values.
- Adds Dataset publisher, identifier, temporal coverage, keywords, methodology and provenance metadata.
- Adds Article schema to the Shrawan trade report with explicit source provenance.
- Adds visible source / coverage / citation blocks to the report, import dataset, export dataset and data library.
- Updates the methodology citation to a specific, canonical dataset citation.
- Does not add a license because no source license was verified.
- Does not claim that llms.txt guarantees AI citation.

## Deployment
Safest method: replace the site with this complete package, preserving the `data/` directory already in your production repository. This package intentionally does not include the large data directory; do not delete it from GitHub.

After deploy, verify `/robots.txt`, `/llms.txt`, the Shrawan report, import-data page, export-data page, and data-download page.
