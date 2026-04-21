# Section: common-hero

Source: `sections/common-hero.liquid`

## Purpose

`common-hero` renders the Common Hero Section section.

## Used By Templates

- [collection.json](../templates/collection.json.md)
- [list-collections.json](../templates/list-collections.json.md)
- [page.about.json](../templates/page.about.json.md)
- [page.community.json](../templates/page.community.json.md)
- [page.contact.json](../templates/page.contact.json.md)
- [page.education.json](../templates/page.education.json.md)
- [page.faq.json](../templates/page.faq.json.md)
- [page.json](../templates/page.json.md)
- [page.transparency.json](../templates/page.transparency.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `hero_image` | `image_picker` | Hero Image |  | Recommended: 473x783px minimum rendered ratio (473:783); upload 2x if available. |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `shop_button` | `text` | Community Button |  |  |
| `how_button` | `text` | Learn More Button |  |  |
| `shop_url` | `url` | Community Url |  |  |
| `how_url` | `url` | Learn More Url |  |  |

## Current Section Image Values

- `hero_image`: `about-hero-image.png` in page.about.json, page.json<br>`collection-hero.png` in collection.json, list-collections.json<br>`community-hero.png` in page.community.json<br>`contact-hero.png` in page.contact.json<br>`education-image.png` in page.education.json<br>`faq-hero.png` in page.faq.json<br>`transparency-hero.png` in page.transparency.json

## Blocks

This section does not declare local schema blocks.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
