# Section: fast-relief

Source: `sections/fast-relief.liquid`

## Purpose

`fast-relief` renders the Comfort section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading |  |
| `description` | `text` | Description |  |
| `button` | `text` | Button |  |
| `button_url` | `url` | Button url |  |

## Blocks

### `comfort_block`

Comfort

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `icon` | `image_picker` | Icon Image |  | Recommended: 35x35px minimum rendered ratio (1:1); upload 2x if available. |
| `title` | `text` | Title |  |  |
| `description` | `text` | Description |  |  |

Current image values:
- `icon`: `clean-confidence.svg` in index.json<br>`fast-relief.svg` in index.json<br>`smarter.svg` in index.json

## Template Block Instances

### `comfort_block`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
