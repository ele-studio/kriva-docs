# Section: backed-by

Source: `sections/backed-by.liquid`

## Purpose

`backed-by` renders the Backed By section.

## Used By Templates

- [page.education.json](../templates/page.education.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | Spacing | | |
| `margin_top_mobile` | `number` | Margin Top — Mobile (px) | 64 |  |
| `margin_bottom_mobile` | `number` | Margin Bottom — Mobile (px) | 64 |  |
| `margin_top_desktop` | `number` | Margin Top — Desktop (px) | 142 |  |
| `margin_bottom_desktop` | `number` | Margin Bottom — Desktop (px) | 145 |  |
| n/a | `header` | Content | | |
| `position_image` | `image_picker` | Position Image |  | Recommended: 149x137px minimum rendered ratio (149:137); upload 2x if available. |
| `kriva_image` | `image_picker` | Kriva Image |  | Recommended: 466x833px minimum rendered ratio (466:833); upload 2x if available. |
| `kriva_image_bg` | `image_picker` | Kriva Image Background |  | Recommended: at least 577px wide; preserve the current uploaded aspect ratio. |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `description_2` | `text` | Description 2 |  |  |
| `description_3` | `text` | Description 3 |  |  |
| `benefit_text` | `text` | Benefit Text |  |  |
| `primary_button` | `text` | Primary Button |  |  |
| `primary_url` | `url` | Primary Url |  |  |
| `secondary_button` | `text` | Secondary Button |  |  |
| `secondary_url` | `url` | Secondary Url |  |  |

## Current Section Image Values

- `kriva_image`: `ED4_-_v2.png` in page.education.json
- `kriva_image_bg`: No current image set in templates.
- `position_image`: `footer-img.png` in page.education.json

## Blocks

### `benefit_text`

Benefit Text

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `list_item` | `text` | List Item |  |

## Template Block Instances

### `benefit_text`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
