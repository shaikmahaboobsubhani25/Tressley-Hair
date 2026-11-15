# Tressley Hair static HTML preview

This is a **staging prototype**, not a complete SEO-safe migration. See MIGRATION_TODO.md before launch.

## Preview locally

From the project folder run `python -m http.server 8000` and open http://localhost:8000.

## GitHub Pages

Upload the contents to a GitHub repository, then use GitHub Pages deployment from main branch/root. Test at a staging domain. Do NOT connect tressleyhair.com until all migration tasks are completed.

## Editing

Static HTML pages are in folders matching current Wix paths. Edit CSS in assets/style.css. The product JSON is in products.json; to regenerate the variant selectors from modified JSON, update the embedded JSON in each product page (or rerun the build script, which is included).

## Analytics

GA4 ID G-5Q89W1KJ3X is embedded in the pages. Verify realtime tracking after deploying.

**Staging safety:** All pages include noindex and robots.txt blocks crawling. Remove these only when launching the complete site.
