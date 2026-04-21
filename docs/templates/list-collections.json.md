# Template: list-collections.json

Source: `templates/list-collections.json`

## Page Structure

1. [common-hero](../sections/common-hero.md) (`common_hero_MBUpdL`)
   - Name: Common Hero Section
   - Section settings: `description`, `heading`, `hero_image`, `how_button`, `shop_button`
2. [collections-tab](../sections/collections-tab.md) (`collections_tab_LDdCab`)
   - Name: Collection Tabs Products
   - Section settings: `description`, `heading`
3. [main-collection-list](../sections/main-collection-list.md) (`collection_list_Wfgh3m` disabled)
   - Name: Collection list
   - Section settings: `bento_gap`, `carousel_on_mobile`, `color_scheme`, `columns`, `columns_gap`, `gap`, `icons_shape`, `icons_style`, `layout_type`, `max_collections`, `mobile_columns`, `padding-block-end`, `padding-block-start`, `rows_gap`, `section_width`
   - Blocks:
       - `group` (`group_4FtiAg` - t:names.header)
         - Settings: `align_baseline`, `background_image_position`, `background_media`, `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `content_direction`, `custom_height`, `custom_width`, `custom_width_mobile`, `gap`, `gradient_direction`, `height`, `horizontal_alignment`, `horizontal_alignment_flex_direction_column`, `inherit_color_scheme`, `link`, `open_in_new_tab`, `overlay_color`, `overlay_style`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `placeholder`, `toggle_overlay`, `vertical_alignment`, `vertical_alignment_flex_direction_column`, `vertical_on_mobile`, `video_position`, `width`, `width_mobile`
         - `text` (`text_fRMQMR` - t:names.text)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `_collection-card` (`static-collection-card` - t:names.collection_card static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `collection_card_gap`, `color_scheme`, `horizontal_alignment`, `inherit_color_scheme`, `placement`, `vertical_alignment`
         - `collection-title` (`collection_title_7YgBPU` - t:names.collection_title)
           - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `type_preset`, `width`, `wrap`
         - `_collection-card-image` (`collection-card-image` - t:names.collection_card_image static)
           - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `gradient_direction`, `image_ratio`, `overlay_color`, `overlay_style`, `toggle_overlay`

## Component Dependencies

Sections: [common-hero](../sections/common-hero.md), [collections-tab](../sections/collections-tab.md), [main-collection-list](../sections/main-collection-list.md)
Blocks: `_collection-card`, `_collection-card-image`, `collection-title`, `group`, `text`
Snippets: `background-media`, `bento-grid`, `border-override`, `collection-card`, `editorial-blog-grid`, `editorial-collection-grid`, `editorial-product-grid`, `gap-style`, `group`, `layout-panel-style`, `overlay`, `resource-image`, `resource-list`, `resource-list-carousel`, `size-style`, `slideshow`, `slideshow-arrow`, `slideshow-arrows`, `slideshow-slide`, `spacing-padding`, `spacing-style`, `text`, `timeline-scope`, `typography-style`
