# Section: main-page

Source: `sections/main-page.liquid`

## Purpose

`main-page` renders the t:names.page section. It delegates repeated markup to snippets.

## Used By Templates

- [page.about.json](../templates/page.about.json.md)
- [page.article.json](../templates/page.article.json.md)
- [page.community.json](../templates/page.community.json.md)
- [page.contact.json](../templates/page.contact.json.md)
- [page.education.json](../templates/page.education.json.md)
- [page.faq.json](../templates/page.faq.json.md)
- [page.json](../templates/page.json.md)
- [page.transparency.json](../templates/page.transparency.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `content_direction` | `select` | t:settings.direction | column |
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

### `page-content`

Source: `blocks/page-content.liquid`
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

Direct snippets: `layout-panel-style`, `spacing-style`
