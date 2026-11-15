# Migration checklist — NOT ready for DNS cutover

- Confirm catalogue currency. Wix CSV has prices but no currency field. Prototype currently displays $ as a placeholder assumption.
- Migrate the full existing text of the other 23 blog articles before publishing. Only five previously drafted articles are included here.
- Obtain original About Us, Shipping Policy, Privacy Policy and Terms text; do not invent legal or shipping promises.
- Verify the five blog drafts against live Wix content and metadata; current drafts may differ.
- Retrieve original blog images and update article image metadata.
- Audit the remaining Wix member-profile and blog-category sitemap URLs.
- Verify all product options, prices, currency and availability against Wix.
- Configure proper HTTP 301 redirects for any changed URL using Cloudflare/hosting edge.
- Validate contact forms; prototype currently opens WhatsApp with the enquiry, rather than storing or emailing it.
- Test GA4 events, Search Console ownership, robots, canonicals and full sitemap on staging before launch.
- Confirm original logo appearance on light/dark backgrounds.
- Update/restore all policy and About pages before production.
