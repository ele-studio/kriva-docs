# Template: cart.json

Source: `templates/cart.json`

## Page Structure

1. [main-cart](../sections/main-cart.md) (`cart-section`)
   - Section settings: `color_scheme`, `padding-block-end`, `padding-block-start`, `section_width`
   - Blocks:
       - `_cart-title` (`cart-page-title` static)
         - Settings: `alignment`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_count`, `title`, `type_preset`
       - `_cart-products` (`cart-page-items` static)
         - Settings: `dividers`, `gap`, `image_ratio`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `vendor`
       - `_cart-summary` (`cart-page-summary` static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `extend_summary`, `inherit_color_scheme`
2. [product-list](../sections/product-list.md) (`product_list_NNFgcy`)
   - Name: Featured collection
   - Section settings: `carousel_on_mobile`, `collection`, `color_scheme`, `columns`, `columns_gap`, `gap`, `horizontal_alignment`, `icons_shape`, `icons_style`, `layout_type`, `max_products`, `mobile_card_size`, `mobile_columns`, `padding-block-end`, `padding-block-start`, `rows_gap`, `section_width`
   - Blocks:
       - `_product-list-content` (`static-header` - t:names.header static)
         - Settings: `align_baseline`, `background_image_position`, `background_media`, `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `content_direction`, `custom_height`, `custom_width`, `custom_width_mobile`, `gap`, `height`, `horizontal_alignment`, `horizontal_alignment_flex_direction_column`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `vertical_alignment`, `vertical_alignment_flex_direction_column`, `vertical_on_mobile`, `video_position`, `width`, `width_mobile`
         - `_product-list-text` (`product_list_text_fifeh4` - t:names.collection_title)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
         - `_product-list-button` (`product_list_button_eibbma` - t:names.product_list_button)
           - Settings: `custom_width`, `custom_width_mobile`, `label`, `open_in_new_tab`, `style_class`, `width`, `width_mobile`
       - `_product-card` (`static-product-card` - t:names.product_card static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `product_card_gap`
         - `_product-card-gallery` (`product_card_gallery_PEPpfq` - t:names.product_card_media)
           - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `image_ratio`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`
         - `product-title` (`product_title_WNMpHe` - t:names.product_title)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `type_preset`, `width`, `wrap`
         - `price` (`price_yXfkPX` - t:names.product_price)
           - Settings: `alignment`, `case`, `color`, `font`, `font_size`, `letter_spacing`, `line_height`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_installments`, `show_sale_price_first`, `show_tax_info`, `type_preset`, `width`

## Component Dependencies

Sections: [main-cart](../sections/main-cart.md), [product-list](../sections/product-list.md)
Blocks: `_cart-products`, `_cart-summary`, `_cart-title`, `_product-card`, `_product-card-gallery`, `_product-list-button`, `_product-list-content`, `_product-list-text`, `price`, `product-title`
Snippets: `add-to-cart-button`, `background-media`, `bento-grid`, `border-override`, `button`, `card-gallery`, `cart-bubble`, `cart-discount`, `cart-note`, `cart-products`, `cart-summary`, `disclosure-content`, `disclosure-trigger`, `editorial-blog-grid`, `editorial-collection-grid`, `editorial-product-grid`, `gap-style`, `group`, `layout-panel-style`, `overlay`, `price`, `product-card`, `product-card-badges`, `quantity-selector`, `quick-add`, `resource-list`, `resource-list-carousel`, `size-style`, `slideshow`, `slideshow-arrow`, `slideshow-arrows`, `slideshow-slide`, `spacing-padding`, `spacing-style`, `tax-info`, `text`, `timeline-scope`, `typography-style`, `unit-price`, `volume-pricing-info`
Web Components: `cart-items-component`, `product-price`
