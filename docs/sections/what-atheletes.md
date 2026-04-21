# Section: what-atheletes

Source: `sections/what-atheletes.liquid`

## Purpose

`what-atheletes` renders the Athelete Say section.

## Used By Templates

- [page.community.json](../templates/page.community.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading | Trusted by Everyday Athletes |
| `paragraph` | `textarea` | Paragraph | From the gym to the trail to the weekend tournament, people everywhere are discovering recovery that actually works. |
| `copy_position` | `select` | Copy position | split |

## Blocks

### `review`

Review Card

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `text_heading` | `text` | User Name | User Name |
| `post_date` | `text` | Post Date |  |
| `cta_text` | `text` | CTA |  |
| `title` | `text` | Title |  |
| `description` | `text` | Description |  |
| `like_people` | `text` | Like People |  |

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
