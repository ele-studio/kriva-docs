# Section: main-collection-list

Source: `sections/main-collection-list.liquid`

## Purpose

`main-collection-list` renders the t:names.collection_list section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets.

## Used By Templates

- [list-collections.json](../templates/list-collections.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `header` | n/a | t:content.cards_layout | |
| `layout_type` | `select` | t:settings.layout_type | grid |
| `carousel_on_mobile` | `checkbox` | t:settings.carousel_on_mobile | False |
| `columns` | `range` | t:settings.columns | 4 |
| `mobile_columns` | `select` | t:settings.mobile_columns | 2 |
| `columns_gap` | `range` | t:settings.horizontal_gap | 8 |
| `bento_gap` | `range` | t:settings.gap | 8 |
| `rows_gap` | `range` | t:settings.vertical_gap | 8 |
| `max_collections` | `range` | t:settings.collection_count | 4 |
| `header` | n/a | t:content.carousel_navigation | |
| `icons_style` | `select` | t:settings.icon | arrow |
| `icons_shape` | `select` | t:settings.icon_background | none |
| `header` | n/a | t:content.section_layout | |
| `section_width` | `select` | t:settings.width | page-width |
| `gap` | `range` | t:settings.gap | 12 |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

### `@theme`



### `@app`



### `text`



### `icon`



### `image`



### `button`



### `video`



### `group`



### `spacer`



### `_divider`



## Template Block Instances

### `_collection-card`

Source: `blocks/_collection-card.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_collection_card | |
| `header` | n/a | t:content.text | |
| `placement` | `select` | t:settings.placement |  |
| `horizontal_alignment` | `select` | t:settings.alignment | flex-start |
| `vertical_alignment` | `select` | t:settings.position | center |
| `collection_card_gap` | `range` | t:settings.vertical_gap | 8 |
| `header` | n/a | t:content.appearance | |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `border` | `select` | t:settings.borders | none |
| `border_width` | `range` | t:settings.border_width | 1 |
| `border_opacity` | `range` | t:settings.border_opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |

### `_collection-card-image`

Source: `blocks/_collection-card-image.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_collection_card_image | |
| `image_ratio` | `select` | t:settings.aspect_ratio | portrait |
| `toggle_overlay` | `checkbox` | t:settings.media_overlay |  |
| `overlay_color` | `color` | t:settings.overlay_color | #00000026 |
| `overlay_style` | `select` | t:settings.overlay_style | solid |
| `gradient_direction` | `select` | t:settings.gradient_direction | to top |
| `header` | n/a | t:content.borders | |
| `border` | `select` | t:settings.style | none |
| `border_width` | `range` | t:settings.thickness | 1 |
| `border_opacity` | `range` | t:settings.opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |

### `collection-title`

Source: `blocks/collection-title.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_collection_title | |
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

### `group`

Source: `blocks/group.liquid`
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

## Liquid Dependencies

Content-for blocks: `_collection-card`
Direct snippets: `gap-style`, `resource-list`, `spacing-style`
