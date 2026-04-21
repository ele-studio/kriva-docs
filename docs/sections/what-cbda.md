# Section: what-cbda

Source: `sections/what-cbda.liquid`

## Purpose

`what-cbda` renders the What Cbda section.

## Used By Templates

- [page.education.json](../templates/page.education.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | Margin | | |
| `padding_top_desktop` | `range` | Margin Top — Desktop | 52 |  |
| `padding_bottom_desktop` | `range` | Margin Bottom — Desktop | 60 |  |
| `padding_top_mobile` | `range` | Margin Top — Mobile | 52 |  |
| `padding_bottom_mobile` | `range` | Margin Bottom — Mobile | 52 |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 149x137px minimum rendered ratio (149:137); upload 2x if available. |
| `kriva_image` | `image_picker` | Kriva Image |  | Recommended: 466x833px minimum rendered ratio (466:833); upload 2x if available. |
| `kriva_image_bg` | `image_picker` | Kriva Image Background |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `benefit_text` | `text` | Benefit Text |  |  |
| `primary_button` | `text` | Primary Button |  |  |
| `primary_url` | `url` | Primary Url |  |  |
| `secondary_button` | `text` | Secondary Button |  |  |
| `secondary_url` | `url` | Secondary Url |  |  |

## Current Section Image Values

- `kriva_image`: `ED2_-_v2.png` in page.education.json
- `kriva_image_bg`: No current image set in templates.
- `position_image`: No current image set in templates.

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
