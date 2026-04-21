# Section: why-kriva

Source: `sections/why-kriva.liquid`

## Purpose

`why-kriva` renders the Why Kriva section.

## Used By Templates

- [page.about.json](../templates/page.about.json.md)
- [page.json](../templates/page.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | Margin | | |
| `margin_top_desktop` | `range` | Margin Top — Desktop | 24 |  |
| `margin_bottom_desktop` | `range` | Margin Bottom — Desktop | 76 |  |
| `margin_top_mobile` | `range` | Margin Top — Mobile | 52 |  |
| `margin_bottom_mobile` | `range` | Margin Bottom — Mobile | 52 |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 149x137px minimum rendered ratio (149:137); upload 2x if available. |
| `kriva_image` | `image_picker` | Kriva Image |  | Recommended: 466x833px minimum rendered ratio (466:833); upload 2x if available. |
| `kriva_image_bg` | `image_picker` | Kriva Image Background |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| `heading` | `text` | Heading |  |  |
| `description_1` | `text` | Description 1 |  |  |
| `description_2` | `text` | Description 2 |  |  |
| `description_3` | `text` | Description 3 |  |  |
| `primary_button` | `text` | Primary Button |  |  |
| `primary_url` | `url` | Primary Url |  |  |
| `secondary_button` | `text` | Secondary Button |  |  |
| `secondary_url` | `url` | Secondary Url |  |  |

## Current Section Image Values

- `kriva_image`: `About2_-_v2.png` in page.about.json<br>`why-kriva-image_268027e3-cd4c-4a72-b1dc-62d145659ae4.png` in page.json
- `kriva_image_bg`: `kriva-bg.png` in page.json
- `position_image`: `footer-img.png` in page.json

## Blocks

This section does not declare local schema blocks.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
