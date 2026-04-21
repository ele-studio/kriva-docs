# Section: product-information

Source: `sections/product-information.liquid`

## Purpose

`product-information` renders the t:names.product_information section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets. It uses Web Components for interactive behavior.

## Used By Templates

- [product.json](../templates/product.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `header` | n/a | t:content.layout | |
| `content_width` | `select` | t:settings.width | content-center-aligned |
| `desktop_media_position` | `select` | t:settings.media_position | left |
| `equal_columns` | `checkbox` | t:settings.equal_columns | False |
| `limit_details_width` | `checkbox` | t:settings.limit_product_details_width | False |
| `gap` | `range` | t:settings.gap | 16 |
| `enable_sticky_add_to_cart` | `checkbox` | t:settings.enable_sticky_add_to_cart | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

### `@app`



## Template Block Instances

### `_divider`

Source: `blocks/_divider.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `thickness` | `range` | t:settings.thickness | 1 |
| `corner_radius` | `select` | t:settings.border_radius | square |
| `width_percent` | `range` | t:settings.length | 100 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

### `_product-details`

Source: `blocks/_product-details.liquid`

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | t:content.size | | |
| `width` | `select` | t:settings.width | fill |  |
| `custom_width` | `range` | t:settings.custom_width | 100 |  |
| `width_mobile` | `select` | t:settings.width_mobile | fill |  |
| `custom_width_mobile` | `range` | t:settings.custom_width | 100 |  |
| `height` | `select` | t:settings.height | fit |  |
| n/a | `header` | t:content.layout | | |
| `details_position` | `select` | t:settings.position | flex-start |  |
| `gap` | `range` | t:settings.gap | 12 |  |
| `sticky_details_desktop` | `checkbox` | t:settings.make_details_sticky_desktop | False |  |
| n/a | `header` | t:content.appearance | | |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |  |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |  |
| `background_media` | `select` | t:settings.background_media | none |  |
| `video` | `video` | t:settings.video |  |  |
| `video_position` | `select` | t:settings.video_position | cover |  |
| `background_image` | `image_picker` | t:settings.image |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| `background_image_position` | `select` | t:settings.image_position | cover |  |
| `border` | `select` | t:settings.borders | none |  |
| `border_width` | `range` | t:settings.border_width | 1 |  |
| `border_opacity` | `range` | t:settings.border_opacity | 100 |  |
| `border_radius` | `range` | t:settings.border_radius | 0 |  |
| n/a | `header` | t:content.padding | | |
| `padding-block-start` | `range` | t:settings.top | 0 |  |
| `padding-block-end` | `range` | t:settings.bottom | 0 |  |
| `padding-inline-start` | `range` | t:settings.left | 0 |  |
| `padding-inline-end` | `range` | t:settings.right | 0 |  |

Current image values:
- `background_image`: No current image set in templates.

### `_product-media-gallery`

Source: `blocks/_product-media-gallery.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `media_presentation` | `select` | t:settings.type | grid |
| `header` | n/a | t:content.grid | |
| `media_columns` | `select` | t:settings.columns | one |
| `image_gap` | `range` | t:settings.gap | 0 |
| `large_first_image` | `checkbox` | t:settings.full_width_first_image | False |
| `header` | n/a | t:content.carousel | |
| `icons_style` | `select` | t:settings.icons | arrow |
| `slideshow_controls_style` | `select` | t:settings.desktop_pagination |  |
| `slideshow_mobile_controls_style` | `select` | t:settings.mobile_pagination |  |
| `header` | n/a | t:content.thumbnails | |
| `thumbnail_position` | `select` | t:settings.desktop_position | bottom |
| `thumbnail_width` | `range` | t:settings.width_desktop | 64 |
| `thumbnail_radius` | `range` | t:settings.corner_radius | 0 |
| `header` | n/a | t:content.media | |
| `aspect_ratio` | `select` | t:settings.aspect_ratio | adapt |
| `constrain_to_viewport` | `checkbox` | t:settings.limit_media_to_screen_height | False |
| `media_fit` | `select` | t:settings.media_fit | cover |
| `media_radius` | `range` | t:settings.border_radius | 4 |
| `extend_media` | `checkbox` | t:settings.extend_media_to_screen_edge | True |
| `zoom` | `checkbox` | t:settings.enable_zoom | True |
| `video_loop` | `checkbox` | t:settings.enable_video_looping | False |
| `hide_variants` | `checkbox` | t:settings.hide_unselected_variant_media | False |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `accelerated-checkout`

Source: `blocks/accelerated-checkout.liquid`
No standalone block schema settings were found, or this is a local/custom block type.

### `add-to-cart`

Source: `blocks/add-to-cart.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `style_class` | `select` | t:settings.style | button-secondary |

### `buy-buttons`

Source: `blocks/buy-buttons.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product | |
| `stacking` | `checkbox` | t:settings.always_stack_buttons | False |
| `show_pickup_availability` | `checkbox` | t:settings.show_pickup_availability | True |
| `gift_card_form` | `checkbox` | t:settings.gift_card_form | True |
| `paragraph` | n/a | t:content.gift_card_form_description | |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `group`

Source: `blocks/group.liquid`
No standalone block schema settings were found, or this is a local/custom block type.

### `price`

Source: `blocks/price.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_price | |
| `paragraph` | n/a | t:content.edit_price_in_theme_settings | |
| `show_sale_price_first` | `checkbox` | t:settings.show_sale_price_first | True |
| `show_installments` | `checkbox` | t:settings.installments | False |
| `show_tax_info` | `checkbox` | t:settings.show_tax_info | False |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset |  |
| `width` | `select` | t:settings.width | 100% |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `font` | `select` | t:settings.font | var(--font-body--family) |
| `font_size` | `select` | t:settings.size | 1rem |
| `line_height` | `select` | t:settings.line_height | normal |
| `letter_spacing` | `select` | t:settings.letter_spacing | normal |
| `case` | `select` | t:settings.case | none |
| `color` | `select` | t:settings.color | var(--color-foreground) |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `quantity`

Source: `blocks/quantity.liquid`
No standalone block schema settings were found, or this is a local/custom block type.

### `text`

Source: `blocks/text.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `text` | `richtext` | t:settings.text |  |
| `header` | n/a | t:content.layout | |
| `width` | `select` | t:settings.width | fit-content |
| `max_width` | `select` | t:settings.max_width | normal |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset | rte |
| `font` | `select` | t:settings.font | var(--font-body--family) |
| `font_size` | `select` | t:settings.size | 1rem |
| `line_height` | `select` | t:settings.line_height | normal |
| `letter_spacing` | `select` | t:settings.letter_spacing | normal |
| `case` | `select` | t:settings.case | none |
| `wrap` | `select` | t:settings.wrap |  |
| `color` | `select` | t:settings.color | var(--color-foreground) |
| `header` | n/a | t:content.appearance | |
| `background` | `checkbox` | t:settings.background | False |
| `background_color` | `color` | t:settings.background_color | #00000026 |
| `corner_radius` | `range` | t:settings.corner_radius | 0 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `variant-picker`

Source: `blocks/variant-picker.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_variant_picker | |
| `paragraph` | n/a | t:content.edit_variants_in_theme_settings | |
| `variant_style` | `select` | t:settings.style | buttons |
| `show_swatches` | `checkbox` | t:settings.swatches | True |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 8 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

## Liquid Dependencies

Content-for blocks: `_product-details`, `_product-media-gallery`
Direct snippets: `price`, `product-information-content`
Web Components: `sticky-add-to-cart`
