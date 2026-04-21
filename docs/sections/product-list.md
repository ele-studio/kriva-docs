# Section: product-list

Source: `sections/product-list.liquid`

## Purpose

`product-list` renders the Product List section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets.

## Used By Templates

- [404.json](../templates/404.json.md)
- [cart.json](../templates/cart.json.md)

## Schema Settings

No section schema settings were found.

## Blocks

This section does not declare local schema blocks.

## Template Block Instances

### `_product-card`

Source: `blocks/_product-card.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_card | |
| `product_card_gap` | `range` | t:settings.vertical_gap | 16 |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.borders | |
| `border` | `select` | t:settings.style | none |
| `border_width` | `range` | t:settings.thickness | 1 |
| `border_opacity` | `range` | t:settings.opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `_product-card-gallery`

Source: `blocks/_product-card-gallery.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_media | |
| `image_ratio` | `select` | t:settings.aspect_ratio | portrait |
| `header` | n/a | t:content.borders | |
| `border` | `select` | t:settings.style | none |
| `border_width` | `range` | t:settings.thickness | 1 |
| `border_opacity` | `range` | t:settings.opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `_product-list-button`

Source: `blocks/_product-list-button.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.visible_if_collection_has_more_products | |
| `label` | `text` | t:settings.label | t:text_defaults.button_label |
| `open_in_new_tab` | `checkbox` | t:settings.open_new_tab | False |
| `style_class` | `select` | t:settings.style | button |
| `header` | n/a | t:content.size | |
| `width` | `select` | t:settings.width_desktop | fit-content |
| `custom_width` | `range` | t:settings.custom_width | 100 |
| `width_mobile` | `select` | t:settings.width_mobile | fit-content |
| `custom_width_mobile` | `range` | t:settings.custom_width | 100 |

### `_product-list-content`

Source: `blocks/_product-list-content.liquid`

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | t:content.layout | | |
| `content_direction` | `select` | t:settings.direction | column |  |
| `vertical_on_mobile` | `checkbox` | t:settings.vertical_on_mobile | True |  |
| `horizontal_alignment` | `select` | t:settings.alignment | flex-start |  |
| `vertical_alignment` | `select` | t:settings.position | center |  |
| `align_baseline` | `checkbox` | t:settings.align_baseline | False |  |
| `horizontal_alignment_flex_direction_column` | `select` | t:settings.alignment | flex-start |  |
| `vertical_alignment_flex_direction_column` | `select` | t:settings.position | center |  |
| `gap` | `range` | t:settings.gap | 12 |  |
| n/a | `header` | t:content.size | | |
| `width` | `select` | t:settings.width | fill |  |
| `custom_width` | `range` | t:settings.custom_width | 100 |  |
| `width_mobile` | `select` | t:settings.width_mobile | fill |  |
| `custom_width_mobile` | `range` | t:settings.custom_width | 100 |  |
| `height` | `select` | t:settings.height | fit |  |
| `custom_height` | `range` | t:settings.custom_height | 100 |  |
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

### `_product-list-text`

Source: `blocks/_product-list-text.liquid`

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

### `product-title`

Source: `blocks/product-title.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_title | |
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

## Liquid Dependencies

Content-for blocks: `_product-card`, `_product-list-content`
Direct snippets: `gap-style`, `resource-list`, `spacing-style`
