# Section: main-404

Source: `sections/main-404.liquid`

## Purpose

`main-404` renders the t:names.404 section. It delegates repeated markup to snippets.

## Used By Templates

- [404.json](../templates/404.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `content_direction` | `select` | t:settings.direction | column |
| `header` | n/a | t:content.layout | |
| `section_width` | `select` | t:settings.width | page-width |
| `section_height` | `select` | t:settings.height |  |
| `horizontal_alignment_flex_direction_column` | `select` | t:settings.alignment | center |
| `vertical_alignment_flex_direction_column` | `select` | t:settings.position | center |
| `gap` | `range` | t:settings.gap | 12 |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

### `@theme`



### `@app`



### `_divider`



## Template Block Instances

### `button`

Source: `blocks/button.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `label` | `text` | t:settings.label | t:text_defaults.button_label |
| `link` | `url` | t:settings.link |  |
| `open_in_new_tab` | `checkbox` | t:settings.open_new_tab | False |
| `style_class` | `select` | t:settings.style | button |
| `header` | n/a | t:content.size | |
| `width` | `select` | t:settings.width_desktop | fit-content |
| `custom_width` | `range` | t:settings.custom_width | 100 |
| `width_mobile` | `select` | t:settings.width_mobile | fit-content |
| `custom_width_mobile` | `range` | t:settings.custom_width | 100 |

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

Direct snippets: `layout-panel-style`, `spacing-style`
