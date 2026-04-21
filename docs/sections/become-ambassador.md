# Section: become-ambassador

Source: `sections/become-ambassador.liquid`

## Purpose

`become-ambassador` renders the Become Ambassador section.

## Used By Templates

- [page.community.json](../templates/page.community.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading |  |
| `description` | `text` | Description |  |
| `qualification_text` | `text` | Qualification Text |  |

## Blocks

### `qualification`

Qualification

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `list` | `text` | List |  |

### `qualification_card`

Qualification Card

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `icon_image` | `image_picker` | Icon Image |  | Recommended: 50x50px minimum rendered ratio (1:1); upload 2x if available. |
| `title` | `text` | Title |  |  |
| `cards_description` | `text` | Cards Description |  |  |

Current image values:
- `icon_image`: `exclusive-icon.svg` in page.community.json<br>`performance-icon.svg` in page.community.json<br>`support-icon.svg` in page.community.json<br>`vip-icon.svg` in page.community.json

## Template Block Instances

### `qualification`

No standalone block schema settings were found, or this is a local/custom block type.

### `qualification_card`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
