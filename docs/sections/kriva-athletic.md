# Section: kriva-athletic

Source: `sections/kriva-athletic.liquid`

## Purpose

`kriva-athletic` renders the Kriva Athletic section.

## Used By Templates

- [page.about.json](../templates/page.about.json.md)
- [page.json](../templates/page.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `heading` | `text` | Heading |  |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 346x319px minimum rendered ratio (346:319); upload 2x if available. |

## Current Section Image Values

- `position_image`: `athletic-logo.png` in page.about.json, page.json

## Blocks

### `athletic_board`

Athletic Board

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `title` | `text` | Title |  |  |
| `description` | `text` | Description |  |  |
| `athletic_image` | `image_picker` | Athletic Image |  | Recommended: 300x150px minimum rendered ratio (2:1); upload 2x if available. |

Current image values:
- `athletic_image`: `barry.png` in page.about.json, page.json

## Template Block Instances

### `athletic_board`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
