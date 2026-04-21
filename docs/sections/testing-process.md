# Section: testing-process

Source: `sections/testing-process.liquid`

## Purpose

`testing-process` renders the Testing Process section.

## Used By Templates

- [page.transparency.json](../templates/page.transparency.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading |  |
| `description` | `text` | Description |  |

## Blocks

### `process`

Process

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `icon` | `image_picker` | Icon |  | Recommended: 40x40px minimum rendered ratio (1:1); upload 2x if available. |
| `process_name` | `text` | Process Name |  |  |
| `process_description` | `text` | Process Description |  |  |

Current image values:
- `icon`: `comprehensive.svg` in page.transparency.json<br>`quality.svg` in page.transparency.json<br>`third-party.svg` in page.transparency.json

## Template Block Instances

### `process`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
