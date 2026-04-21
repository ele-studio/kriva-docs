# Section: section

Source: `sections/section.liquid`

## Purpose

`section` renders the Section section. It delegates repeated markup to snippets.

## Used By Templates

- [collection.json](../templates/collection.json.md)
- [page.contact.json](../templates/page.contact.json.md)

## Schema Settings

No section schema settings were found.

## Blocks

This section does not declare local schema blocks.

## Template Block Instances

### `contact-form`

Source: `blocks/contact-form.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading |  |
| `description` | `text` | Description |  |
| `name_label` | `text` | Name Label |  |
| `email_label` | `text` | Email Label |  |
| `phone_label` | `text` | Phone Label |  |
| `inquiry_label` | `text` | Inquiry Label |  |
| `message_label` | `text` | Message Label |  |
| `contact_heading` | `text` | Contact Heading |  |
| `follow_heading` | `text` | Follow Heading |  |
| `interested_heading` | `text` | Interested Heading |  |
| `interested_description` | `text` | Interested Description |  |
| `interested_cta` | `text` | Interested Cta |  |
| `width` | `select` | t:settings.width_desktop | fit-content |
| `custom_width` | `range` | t:settings.width | 100 |
| `width_mobile` | `select` | t:settings.width_mobile | fit-content |
| `custom_width_mobile` | `range` | t:settings.width | 100 |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `contact-form-submit-button`

Source: `blocks/contact-form-submit-button.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `label` | `text` | t:settings.label | t:text_defaults.contact_form_button_label |
| `style_class` | `select` | t:settings.style | button |
| `header` | n/a | t:content.size | |
| `width` | `select` | t:settings.width_desktop | fit-content |
| `custom_width` | `range` | t:settings.width | 100 |
| `width_mobile` | `select` | t:settings.width_mobile | fit-content |
| `custom_width_mobile` | `range` | t:settings.width | 100 |

### `text`

Source: `blocks/text.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `text` | `richtext` | t:settings.text |  |
| `header` | n/a | t:content.layout | |
| `width` | `select` | t:settings.width | fit-content |
| `max_width` | `select` | t:settings.max_width | normal |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset | rte |
| `font` | `select` | t:settings.font | var(--font-body--family) |
| `font_size` | `select` | t:settings.size | 1rem |
| `line_height` | `select` | t:settings.line_height | normal |
| `letter_spacing` | `select` | t:settings.letter_spacing | normal |
| `case` | `select` | t:settings.case | none |
| `wrap` | `select` | t:settings.wrap |  |
| `color` | `select` | t:settings.color | var(--color-foreground) |
| `header` | n/a | t:content.appearance | |
| `background` | `checkbox` | t:settings.background | False |
| `background_color` | `color` | t:settings.background_color | #00000026 |
| `corner_radius` | `range` | t:settings.corner_radius | 0 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

## Liquid Dependencies

Direct snippets: `section`
