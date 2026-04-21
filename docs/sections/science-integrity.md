# Section: science-integrity

Source: `sections/science-integrity.liquid`

## Purpose

`science-integrity` renders the Science Imtegrity section.

## Used By Templates

- [page.about.json](../templates/page.about.json.md)
- [page.json](../templates/page.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | Margin | | |
| `margin_top_desktop` | `range` | Margin Top — Desktop | 0 |  |
| `margin_bottom_desktop` | `range` | Margin Bottom — Desktop | 0 |  |
| `margin_top_mobile` | `range` | Margin Top — Mobile | 0 |  |
| `margin_bottom_mobile` | `range` | Margin Bottom — Mobile | 0 |  |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `focus_text` | `text` | Focus Text |  |  |
| `primary_button` | `text` | Primary Button |  |  |
| `primary_url` | `url` | Primary Url |  |  |
| `secondary_button` | `text` | Secondary Button |  |  |
| `secondary_url` | `url` | Secondary Url |  |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 149x137px minimum rendered ratio (149:137); upload 2x if available. |
| `science_image` | `image_picker` | Science Image |  | Recommended: 468x357px minimum rendered ratio (156:119); upload 2x if available. |
| `science_image_bg` | `image_picker` | Science Image Background |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |

## Current Section Image Values

- `position_image`: `footer-img.png` in page.json
- `science_image`: `About3_-_v1.png` in page.about.json<br>`science-integrity.png` in page.json
- `science_image_bg`: `kriva-bg.png` in page.json

## Blocks

### `focus_text`

Focus Text

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `list_item` | `text` | List Item |  |

## Template Block Instances

### `focus_text`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
