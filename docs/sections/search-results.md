# Section: search-results

Source: `sections/search-results.liquid`

## Purpose

`search-results` renders the t:names.search_results section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets. It uses Web Components for interactive behavior.

## Used By Templates

- [search.json](../templates/search.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.edit_empty_state_collection_in_theme_settings | |
| `layout_type` | `select` | t:settings.type | grid |
| `product_card_size` | `select` | t:settings.card_size | medium |
| `mobile_product_card_size` | `select` | t:settings.mobile_card_size | small |
| `enable_infinite_scroll` | `checkbox` | t:settings.auto_load_products | True |
| `products_per_page` | `range` | t:settings.products_per_page | 24 |
| `header` | n/a | t:content.layout | |
| `product_grid_width` | `select` | t:settings.width | centered |
| `full_width_on_mobile` | `checkbox` | t:settings.full_width_on_mobile | True |
| `columns_gap_horizontal` | `range` | t:settings.horizontal_gap | 16 |
| `columns_gap_vertical` | `range` | t:settings.vertical_gap | 16 |
| `padding-inline-start` | `range` | t:settings.left_padding | 0 |
| `padding-inline-end` | `range` | t:settings.right_padding | 0 |
| `header` | n/a | t:content.section_layout | |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `padding-block-start` | `range` | t:settings.top_padding | 8 |
| `padding-block-end` | `range` | t:settings.bottom_padding | 8 |

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

### `filters`

Source: `blocks/filters.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `enable_filtering` | `checkbox` | t:settings.enable_filtering | False |
| `filter_style` | `select` | t:settings.direction | horizontal |
| `filter_width` | `select` | t:settings.width | centered |
| `text_label_case` | `select` | t:settings.text_label_case | default |
| `show_swatch_label` | `checkbox` | t:settings.show_swatch_label | False |
| `show_filter_label` | `checkbox` | t:settings.show_filter_label | False |
| `enable_sorting` | `checkbox` | t:settings.enable_sorting | True |
| `enable_grid_density` | `checkbox` | t:settings.enable_grid_density | True |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |
| `header` | n/a | t:content.margin | |
| `facets_margin_bottom` | `range` | t:settings.bottom | 8 |
| `facets_margin_right` | `range` | t:settings.right | 20 |

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

## Liquid Dependencies

Content-for blocks: `_product-card`, `filters`
Direct snippets: `product-grid`, `skip-to-content-link`
Web Components: `results-list`
