# Section: trusted

Source: `sections/trusted.liquid`

## Purpose

`trusted` renders the Trusted Section section.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading | Trusted by Everyday Athletes |
| `paragraph` | `textarea` | Paragraph | From the gym to the trail to the weekend tournament, people everywhere are discovering recovery that actually works. |
| `copy_position` | `select` | Copy position | split |

## Blocks

### `review`

Review Card

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `small_image` | `image_picker` | User Image |  | Recommended: at least 100px wide; preserve the current uploaded aspect ratio. |
| `text_heading` | `text` | User Name | User Name |  |
| `text_paragraph` | `text` | User Subtitle | Verified Buyer |  |
| `star_image` | `image_picker` | Star Image |  | Recommended: at least 32px wide; preserve the current uploaded aspect ratio. |
| `review_text` | `textarea` | Review Text | This product really helped me recover faster! |  |
| `product_image` | `image_picker` | Product Image |  | Recommended: at least 150px wide; preserve the current uploaded aspect ratio. |
| `product_name` | `text` | Product Name | gem pineapple |  |
| `box_image` | `image_picker` | Right Side Image |  | Recommended: at least 420px wide; preserve the current uploaded aspect ratio. |

Current image values:
- `box_image`: `trusted-img1.webp` in index.json<br>`trusted-img2.webp` in index.json<br>`trusted-img3.webp` in index.json
- `product_image`: `gem.png` in index.json<br>`glide.png` in index.json<br>`massage.png` in index.json
- `small_image`: `trusted-icon1.png` in index.json<br>`trusted-icon2.png` in index.json<br>`trusted-icon3.png` in index.json
- `star_image`: `star.png` in index.json

## Template Block Instances

### `review`

Source: `blocks/review.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.resource_reference_product_review | |
| `paragraph` | n/a | t:content.app_required_for_ratings | |
| `stars_style` | `select` | t:settings.style | shaded |
| `show_number` | `checkbox` | t:settings.review_count | True |
| `rating_color` | `select` | t:settings.color | primary |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset | paragraph |
| `width` | `select` | t:settings.width | 100% |
| `alignment` | `text_alignment` | t:settings.alignment | left |

## Liquid Dependencies

No direct Liquid component dependencies were detected.
