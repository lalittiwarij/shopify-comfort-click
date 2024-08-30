# Shopify Homepage Localization

## Task Overview
Localized the Shopify homepage to dynamically switch content based on the customer's country. Currently, the supported regions are India and France. This process involved modifying existing theme sections and creating a new custom image block section.

## Modified Files
- **`sections/slideshow.liquid`**: Added dynamic banner content switching based on the customer's country.
- **`sections/featured-collection.liquid`**: Integrated a product slider with localization for featured products.
- **`sections/footer.liquid`**: Adjusted footer content to reflect country-specific information.

## Custom Created Section
- **`sections/image-block-section.liquid`**:  
  - This section was built from scratch.
  - It allows customization of rows and columns and adapts content dynamically based on the customer's country.

## Localization Method
Utilized Shopify's Markets and the Translate & Adapt app to implement dynamic content switching. For now, images for French localization remain as placeholders due to the unavailability of appropriate assets.

## Outcome
The homepage now supports dynamic localization, including localized banners, featured products, and content sections, offering a tailored experience for different countries.
