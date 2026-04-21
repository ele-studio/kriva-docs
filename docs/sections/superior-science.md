# Section: superior-science

Source: `sections/superior-science.liquid`

## Purpose

`superior-science` renders the Superior Science section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `position_img` | `image_picker` | Position Image |  | Recommended: 293x270px minimum rendered ratio (293:270); upload 2x if available. |
| `mobile_bg` | `image_picker` | Mobile Background Image |  | Recommended: 750x1000px or larger mobile portrait; keep important content centered. |
| `superior_bg` | `image_picker` | Superior background |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| `superior_image` | `image_picker` | Superior Image |  | Recommended: 422x828px minimum rendered ratio (211:414); upload 2x if available. |
| `full_height_image` | `checkbox` | Image Full Height | False |  |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `button_url` | `url` | Button Url |  |  |
| `button` | `text` | Button |  |  |

## Current Section Image Values

- `mobile_bg`: `superior-bg-1.png` in index.json
- `position_img`: `footer-img.png` in index.json
- `superior_bg`: `superior-bg-1.png` in index.json
- `superior_image`: `Superior_Science_product.png` in index.json

## Blocks

This section does not declare local schema blocks.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
