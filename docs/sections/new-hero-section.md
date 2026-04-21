# Section: new-hero-section

Source: `sections/new-hero-section.liquid`

## Purpose

`new-hero-section` renders the New Hero Section section.

## Used By Templates

- [collection.json](../templates/collection.json.md)
- [index.json](../templates/index.json.md)
- [page.about.json](../templates/page.about.json.md)
- [page.contact.json](../templates/page.contact.json.md)
- [page.education.json](../templates/page.education.json.md)
- [page.transparency.json](../templates/page.transparency.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `background_options` | `select` | Background | color |  |
| `background_color` | `color` | Background Color |  |  |
| `background_image` | `image_picker` | Background Image |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| n/a | `header` | Height | | |
| `min_height_desktop` | `range` | Min Height — Desktop | 600 |  |
| n/a | `header` | Overlay | | |
| `overlay_enable` | `checkbox` | Enable Overlay | False |  |
| `overlay_color` | `color` | Overlay Color | #000000 |  |
| `overlay_opacity` | `range` | Overlay Opacity | 40 |  |
| `alignment` | `select` | Alignment |  |  |
| `hero_image` | `image_picker` | Hero Image (Desktop) |  | Recommended: 583x783px minimum rendered ratio (583:783); upload 2x if available. |
| `hero_image_mobile` | `image_picker` | Hero Image (Mobile) |  | Recommended: 750x1000px or larger mobile portrait; keep important content centered. |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `shop_button` | `text` | Shop Button |  |  |
| `shop_url` | `url` | Shop Url |  |  |
| `how_button` | `text` | How It Works |  |  |
| `how_url` | `url` | How It Works Url |  |  |

## Current Section Image Values

- `background_image`: No current image set in templates.
- `hero_image`: `About_-_v1.png` in page.about.json<br>`Education_v-1.jpg` in page.education.json<br>`Home_-_v1.png` in page.contact.json<br>`Products_-_v1_bdd91de0-088c-4109-adaf-b58866d46bac.png` in collection.json<br>`Transparency_-_v1.png` in page.transparency.json<br>`athlete-close-up-running.png` in index.json
- `hero_image_mobile`: `Home_-_v1-mobile.png` in page.contact.json<br>`Products_mobile_v1.png` in collection.json<br>`Transparency_mobile_v1_c276e536-4427-48ea-b5b9-c41c813fb5fd.png` in page.transparency.json<br>`about-mobile.png` in page.about.json<br>`education-mobile.jpg` in page.education.json<br>`home_mobile_hero.jpg` in index.json

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
