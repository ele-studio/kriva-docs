# Section: absorption-result

Source: `sections/absorption-result.liquid`

## Purpose

`absorption-result` renders the Absorption Result section.

## Used By Templates

- [page.education.json](../templates/page.education.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `primary_button` | `text` | Primary Button |  |  |
| `primary_url` | `url` | Primary Url |  |  |
| `secondary_button` | `text` | Secondary Button |  |  |
| `secondary_url` | `url` | Secondary Url |  |  |
| `focus_text` | `text` | Focus Text |  |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 149x137px minimum rendered ratio (149:137); upload 2x if available. |
| `absorption_image` | `image_picker` | Absorption Image |  | Recommended: 511x357px minimum rendered ratio (73:51); upload 2x if available. |
| `absorption_image_bg` | `image_picker` | Absorption Image Background |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |

## Current Section Image Values

- `absorption_image`: `ED3_-_v3.png` in page.education.json
- `absorption_image_bg`: `kriva-bg.png` in page.education.json
- `position_image`: `footer-img.png` in page.education.json

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
