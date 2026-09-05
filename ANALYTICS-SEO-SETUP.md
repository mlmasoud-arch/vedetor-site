# Vedetor analytics + SEO setup

## Google Analytics 4
1. Create a GA4 property and a Web data stream for `https://vedetor.com`.
2. Copy its Measurement ID (format `G-XXXXXXXXXX`).
3. Put that value in `analytics-config.js` as `window.VEDETOR_GA_ID = 'G-XXXXXXXXXX';`
4. Publish the site. The Google tag is then loaded on the main site, localized pages and pricing page.

The site emits useful events such as `language_change`, `feature_view`, `pairing_section_view`, `view_pricing`, and `pricing_cta_click`.

## Google Search Console
Use a Domain property for `vedetor.com` when possible. Domain-property verification is done in DNS. Then submit `https://vedetor.com/sitemap.xml`.

## SEO
The site includes canonical URLs, hreflang/x-default, robots.txt, sitemap.xml, Open Graph/Twitter metadata and JSON-LD for the organization, website and Android application.
