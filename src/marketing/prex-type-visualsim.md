---
ee_only: true
title: Visual similarity
---

The _Visual similarity_ recommendation type recommends similar looking products to the product being viewed. This recommendation type is most useful where images and visual aspects of the products are important parts of the shopping experience.

## How it works

The _Visual similarity_ recommendation type offers recommendations for other products in your catalog that have a visual similarity to the imagery currently being viewed. Visual similarity includes aspects such as:

- Color
- Shape
- Size
- Texture
- Material
- Style

Adobe Sensei uses AI to process and analyze the imagery in your catalog and builds attributes used to determine visual similarities. If you are testing this recommendation type in a non-production environment, make sure your image URLs are publicly accessible. Because this recommendation type is not applicable to most catalogs, it is not enabled by default. You must explicitly enable this recommendation type.

### Enable Visual similarity recommendation type

{:.bs-callout-info}
The _Visual similarity_ recommendation type is available when you [install an optional module](https://devdocs.magento.com/recommendations/install-configure.html#vissimsupport).

1. On the _Admin_ sidebar, go to **Marketing** > _Promotions_ > **Product Recommendations** to display the **Product Recommendations** dashboard.

1. Click **Settings** (gear icon) to display the **Settings** page.

1. In the **Visual Recommendations** section, select to **Enable Visual Recommendations**.

1. Click <span class="btn">Save changes</span> when you are finished.

   The [Create New Recommendations page]({% link marketing/create-new-rec.md %}) now displays **Visual similarity** as a selectable recommendation type when the page type is **Product Detail**.

After you enable visual recommendations, Adobe Sensei initiates the image processing. How long it takes depends on the size of your catalog.

### Where used

- Product detail

### Suggested storefront labels

- "You may also like"
- "We found other products you might like"
- "Inspired by this style"

## Example

The following image shows the product detail page for the _Clamber Watch_:

   ![Clamber Watch]({% link images/images-ee/visual-sim-pdp.png %}){: .zoom}

The following shows the _Visual similarity_ recommendation unit for _Clamber Watch_:

   ![Visual similarity unit]({% link images/images-ee/visual-sim-unit.png %}){: .zoom}
