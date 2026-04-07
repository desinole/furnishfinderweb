# Chattahoochee Rentals — Rental Properties in Chattahoochee, FL

SEO-optimized static website listing rental properties in Chattahoochee, Florida with monthly and annual lease options.

🔗 **Live Site**: [chattahoochee-rentals.com](https://www.chattahoochee-rentals.com/)

## About

This site lists rental properties in Chattahoochee, FL, targeting travel nurses, contractors, remote workers, snowbirds, and outdoor enthusiasts seeking housing in the Florida Panhandle. Properties are displayed as cards with "Contact for Pricing" inquiry forms. Each listing supports monthly and annual lease options.

## SEO Features

- Schema.org structured data (RealEstateAgent + FAQPage)
- Open Graph & Twitter Card meta tags
- Geo meta tags for local search
- `sitemap.xml` for search engine indexing
- `robots.txt` allowing all crawlers
- `llms.txt` for AI chatbot visibility
- Semantic HTML5 with accessibility features
- Mobile-first responsive design
- FAQ section optimized for featured snippets

## Adding a New Property

To add a new property listing, duplicate a `<article class="property-card">` block in `index.html` and update:

1. The property image/placeholder
2. Badges (furnished, pet-friendly, etc.)
3. Title, location, specs, features
4. Lease options (monthly, annual, or both)
5. Amenity preview tags
6. The `data-property` attribute on the contact button

## Adding Photos

1. Add photos to the `images/` directory
2. Replace `property-image-placeholder` divs with `<img>` tags
3. Add an `og-chattahoochee-rentals.jpg` (1200x630px) for social sharing previews

## Hosting

Hosted on GitHub Pages from the `main` branch.
