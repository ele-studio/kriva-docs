# Template: search.json

Source: `templates/search.json`

## Page Structure

1. [search-header](../sections/search-header.md) (`search`)
   - Section settings: `alignment`, `color_scheme`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `_heading` (`heading` static)
         - Settings: `alignment`, `case`, `color`, `font`, `font_size`, `letter_spacing`, `line_height`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `read_only`, `show_alignment`, `text`, `type_preset`, `wrap`
       - `_search-input` (`search` static)
         - Settings: `color_scheme`, `custom_width`, `inherit_color_scheme`, `width`
2. [search-results](../sections/search-results.md) (`main`)
   - Section settings: `color_scheme`, `columns_gap_horizontal`, `columns_gap_vertical`, `full_width_on_mobile`, `layout_type`, `mobile_product_card_size`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `product_card_size`, `product_grid_width`
   - Blocks:
       - `filters` (`filters` static)
         - Settings: `color_scheme`, `enable_filtering`, `enable_grid_density`, `enable_sorting`, `facets_margin_bottom`, `facets_margin_right`, `filter_style`, `filter_width`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_filter_label`, `show_swatch_label`, `text_label_case`
       - `_product-card` (`product-card` static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `product_card_gap`
         - `_product-card-gallery` (`product_card_gallery_cFExAi` - t:names.product_card_media)
           - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `image_ratio`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`
         - `product-title` (`product_title_j7qXTx` - t:names.product_title)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `type_preset`, `width`, `wrap`
         - `price` (`price_fYkUgG` - t:names.product_price)
           - Settings: `alignment`, `case`, `color`, `font`, `font_size`, `letter_spacing`, `line_height`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_installments`, `show_sale_price_first`, `show_tax_info`, `type_preset`, `width`

## Component Dependencies

Sections: [search-header](../sections/search-header.md), [search-results](../sections/search-results.md)
Blocks: `_heading`, `_product-card`, `_product-card-gallery`, `_search-input`, `filters`, `price`, `product-title`
Snippets: `add-to-cart-button`, `border-override`, `card-gallery`, `facets-actions`, `filter-remove-buttons`, `gap-style`, `grid-density-controls`, `icon`, `layout-panel-style`, `overflow-list`, `pagination-controls`, `price`, `product-card`, `product-card-badges`, `product-grid`, `quick-add`, `size-style`, `skip-to-content-link`, `slideshow`, `slideshow-arrow`, `slideshow-arrows`, `sorting`, `spacing-padding`, `spacing-style`, `swatch`, `text`, `timeline-scope`, `typography-style`, `unit-price`, `util-product-grid-card-size`
Web Components: `dialog-component`, `facets-form-component`, `product-price`, `results-list`, `scroll-hint`, `search-page-input-component`
