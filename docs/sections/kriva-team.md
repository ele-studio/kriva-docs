# Section: kriva-team

Source: `sections/kriva-team.liquid`

## Purpose

`kriva-team` renders the kriva-team section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `heading` | `text` | Heading | The Kriva A Team |  |
| `paragraph` | `textarea` | Paragraph | Kriva A-Team Trusted by everyday athletes |  |
| `left-arrow` | `image_picker` | Left Arrow Icon |  | Recommended: 24x24px minimum rendered ratio (1:1); upload 2x if available. |
| `right-arrow` | `image_picker` | Right Arrow Icon |  | Recommended: 24x24px minimum rendered ratio (1:1); upload 2x if available. |

## Current Section Image Values

- `left-arrow`: `slider-arrow.svg` in index.json
- `right-arrow`: `slider-arrow-right.svg` in index.json

## Blocks

### `team_image`

Team Image

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `image` | `image_picker` | Team Image |  | Recommended: 600x600px minimum rendered ratio (1:1); upload 2x if available. |
| `slide_link` | `url` | Slide link |  |  |
| `show_social_icons` | `checkbox` | Show social icons | True |  |
| `icon1` | `image_picker` | Icon 1 |  | Recommended: square SVG or PNG, at least 96x96px for raster uploads. |
| `icon_link1` | `url` | Icon 1 URL |  |  |
| `icon2` | `image_picker` | Icon 2 |  | Recommended: square SVG or PNG, at least 96x96px for raster uploads. |
| `icon_link2` | `url` | Icon 2 URL |  |  |
| `icon3` | `image_picker` | Icon 3 |  | Recommended: square SVG or PNG, at least 96x96px for raster uploads. |
| `icon_link3` | `url` | Icon 3 URL |  |  |

Current image values:
- `icon1`: `black-linkedin.svg` in index.json
- `icon2`: `facebook.svg` in index.json
- `icon3`: `insta.svg` in index.json
- `image`: `harnessed-person-holds-onto-the-edge-of-a-rock-cliff.jpg` in index.json<br>`kriva-team-1.webp` in index.json<br>`kriva-team-2.webp` in index.json<br>`kriva-team-3.webp` in index.json

## Template Block Instances

### `team_image`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
