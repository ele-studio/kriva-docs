# Section: search-header

Source: `sections/search-header.liquid`

## Purpose

`search-header` renders the t:names.search section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets.

## Used By Templates

- [search.json](../templates/search.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `alignment` | `select` | t:settings.alignment | flex-start |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

This section does not declare local schema blocks.

## Template Block Instances

### `_heading`

Source: `blocks/_heading.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `type_preset` | `select` | t:settings.preset | rte |
| `font` | `select` | t:settings.font | var(--font-body--family) |
| `font_size` | `select` | t:settings.size | 1rem |
| `line_height` | `select` | t:settings.line_height | normal |
| `letter_spacing` | `select` | t:settings.letter_spacing | normal |
| `case` | `select` | t:settings.case | none |
| `wrap` | `select` | t:settings.wrap |  |
| `color` | `select` | t:settings.color | var(--color-foreground) |
| `text` | `richtext` | t:settings.text |  |
| `read_only` | `checkbox` | t:settings.read_only | False |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `show_alignment` | `checkbox` | t:settings.show_alignment | True |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `_search-input`

Source: `blocks/_search-input.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `width` | `select` | t:settings.width | custom |
| `custom_width` | `range` | t:settings.custom_width | 50 |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |

## Liquid Dependencies

Content-for blocks: `_heading`, `_search-input`
Direct snippets: `spacing-style`
