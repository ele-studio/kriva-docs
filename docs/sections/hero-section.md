# Section: hero-section

Source: `sections/hero-section.liquid`

## Purpose

`hero-section` renders the Hero Section section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `hero_image` | `image_picker` | Hero Image |  | Recommended: 583x783px minimum rendered ratio (583:783); upload 2x if available. |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `shop_button` | `text` | Shop Button |  |  |
| `shop_url` | `url` | Shop Url |  |  |
| `how_button` | `text` | How It Works |  |  |
| `how_url` | `url` | How It Works Url |  |  |

## Current Section Image Values

- `hero_image`: `hero-man-image.png` in index.json

## Blocks

### `tick_item`

Tick Item

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `icon` | `image_picker` | Tick Icon |  | Recommended: 22x22px minimum rendered ratio (1:1); upload 2x if available. |
| `text` | `text` | Text |  |  |

Current image values:
- `icon`: `circle-tick.svg` in index.json

## Template Block Instances

### `tick_item`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
