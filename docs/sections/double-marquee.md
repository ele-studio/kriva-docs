# Section: double-marquee

Source: `sections/double-marquee.liquid`

## Purpose

`double-marquee` renders the Double Marquee section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `bg_one` | `color` | Marquee 1 Background | #F8F3EA |  |
| `bg_two` | `color` | Marquee 2 Background | #3C59A2 |  |
| `star_one` | `image_picker` | Marquee 1 Star Image |  | Recommended: at least 24px wide; preserve the current uploaded aspect ratio. |
| `star_two` | `image_picker` | Marquee 2 Star Image |  | Recommended: at least 24px wide; preserve the current uploaded aspect ratio. |

## Current Section Image Values

- `star_one`: `blue-st.svg` in index.json
- `star_two`: `pumpkin-st.svg` in index.json

## Blocks

### `line_one`

Marquee 1 Text

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `text` | `text` | Text | MADE IN THE USA |

### `line_two`

Marquee 2 Text

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `text` | `text` | Text | NSF FOR SPORT GMP |

## Template Block Instances

### `line_one`

No standalone block schema settings were found, or this is a local/custom block type.

### `line_two`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
