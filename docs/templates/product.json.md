# Template: product.json

Source: `templates/product.json`

## Page Structure

1. [product-information](../sections/product-information.md) (`main`)
   - Section settings: `color_scheme`, `content_width`, `desktop_media_position`, `enable_sticky_add_to_cart`, `equal_columns`, `gap`, `limit_details_width`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `_product-media-gallery` (`media-gallery` static)
         - Settings: `aspect_ratio`, `constrain_to_viewport`, `extend_media`, `hide_variants`, `icons_style`, `image_gap`, `large_first_image`, `media_columns`, `media_fit`, `media_presentation`, `media_radius`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `slideshow_controls_style`, `slideshow_mobile_controls_style`, `thumbnail_position`, `thumbnail_radius`, `thumbnail_width`, `video_loop`, `zoom`
       - `_product-details` (`product-details` static)
         - Settings: `background_image_position`, `background_media`, `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `custom_width`, `custom_width_mobile`, `details_position`, `gap`, `height`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `sticky_details_desktop`, `video_position`, `width`, `width_mobile`
         - `group` (`group_icgrde` - Header)
           - Settings: `align_baseline`, `background_image_position`, `background_media`, `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `content_direction`, `custom_height`, `custom_width`, `custom_width_mobile`, `gap`, `gradient_direction`, `height`, `horizontal_alignment`, `horizontal_alignment_flex_direction_column`, `inherit_color_scheme`, `link`, `open_in_new_tab`, `overlay_color`, `overlay_style`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `placeholder`, `toggle_overlay`, `vertical_alignment`, `vertical_alignment_flex_direction_column`, `vertical_on_mobile`, `video_position`, `width`, `width_mobile`
           - `text` (`text_xrnftG` - Product title)
             - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
           - `text` (`text_9LULDp` - t:names.text)
             - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
           - `price` (`price_tVjtKg`)
             - Settings: `alignment`, `case`, `color`, `font`, `font_size`, `letter_spacing`, `line_height`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_installments`, `show_sale_price_first`, `show_tax_info`, `type_preset`, `width`
         - `_divider` (`divider_VJhene` - t:names.divider disabled)
           - Settings: `corner_radius`, `padding-block-end`, `padding-block-start`, `thickness`, `width_percent`
         - `variant-picker` (`variant_picker_R3rGDr`)
           - Settings: `alignment`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_swatches`, `variant_style`
         - `text` (`text_aEtTtq` - Product description)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
         - `buy-buttons` (`buy_buttons_eYQEYi`)
           - Settings: `gift_card_form`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_pickup_availability`, `stacking`
           - `quantity` (`quantity` static)
           - `add-to-cart` (`add-to-cart` static)
             - Settings: `style_class`
           - `accelerated-checkout` (`accelerated-checkout` static)
2. [product-detail-faq](../sections/product-detail-faq.md) (`product_detail_faq_eUQfbY`)
   - Name: Product Detail Faq
   - Section settings: `coa`, `how_to_use`, `ingredients`
3. [product-recommendations](../sections/product-recommendations.md) (`product_recommendations_qggXJq` disabled)
   - Name: t:names.product_recommendations
   - Section settings: `carousel_on_mobile`, `color_scheme`, `columns`, `columns_gap`, `gap`, `icons_shape`, `icons_style`, `layout_type`, `max_products`, `mobile_columns`, `padding-block-end`, `padding-block-start`, `product`, `recommendation_type`, `rows_gap`, `section_width`
   - Blocks:
       - `text` (`text_cbcgyb` - t:names.header)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `_product-card` (`static-product-card` - t:names.product_card static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `inherit_color_scheme`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `product_card_gap`
         - `_product-card-gallery` (`product_card_gallery_DNizbJ` - t:names.product_card_media)
           - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `image_ratio`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`
         - `product-title` (`product_title_M7MJkb` - t:names.product_title)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `type_preset`, `width`, `wrap`
         - `price` (`price_gLWgA6`)
           - Settings: `alignment`, `case`, `color`, `font`, `font_size`, `letter_spacing`, `line_height`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `show_installments`, `show_sale_price_first`, `show_tax_info`, `type_preset`, `width`

## Component Dependencies

Sections: [product-information](../sections/product-information.md), [product-detail-faq](../sections/product-detail-faq.md), [product-recommendations](../sections/product-recommendations.md)
Blocks: `_divider`, `_product-card`, `_product-card-gallery`, `_product-details`, `_product-media-gallery`, `accelerated-checkout`, `add-to-cart`, `buy-buttons`, `group`, `price`, `product-title`, `quantity`, `text`, `variant-picker`
Snippets: `add-to-cart-button`, `background-media`, `border-override`, `card-gallery`, `divider`, `gap-style`, `gift-card-recipient-form`, `group`, `icon`, `layout-panel-style`, `overlay`, `price`, `product-card`, `product-card-badges`, `product-information-content`, `product-media`, `product-media-gallery-content`, `quantity-selector`, `quick-add`, `resource-list-carousel`, `size-style`, `skip-to-content-link`, `slideshow`, `slideshow-arrow`, `slideshow-arrows`, `slideshow-controls`, `slideshow-slide`, `spacing-padding`, `spacing-style`, `strikethrough-variant`, `swatch`, `text`, `timeline-scope`, `typography-style`, `unit-price`, `variant-main-picker`, `video`
Web Components: `dialog-component`, `local-pickup`, `product-form-component`, `product-price`, `product-recommendations`, `sticky-add-to-cart`, `volume-pricing`
