# Section: password

Source: `sections/password.liquid`

## Purpose

`password` renders the t:names.section section. It delegates repeated markup to snippets.

## Used By Templates

- [password.json](../templates/password.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| n/a | `header` | t:content.layout | | |
| `content_direction` | `select` | t:settings.direction | column |  |
| `vertical_on_mobile` | `checkbox` | t:settings.vertical_on_mobile | True |  |
| `horizontal_alignment` | `select` | t:settings.alignment | flex-start |  |
| `vertical_alignment` | `select` | t:settings.position | center |  |
| `align_baseline` | `checkbox` | t:settings.align_baseline | False |  |
| `horizontal_alignment_flex_direction_column` | `select` | t:settings.alignment | flex-start |  |
| `vertical_alignment_flex_direction_column` | `select` | t:settings.position | center |  |
| `gap` | `range` | t:settings.gap | 12 |  |
| n/a | `header` | t:content.size | | |
| `section_width` | `select` | t:settings.width | page-width |  |
| n/a | `header` | t:content.appearance | | |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |  |
| `background_media` | `select` | t:settings.background_media | none |  |
| `video` | `video` | t:settings.video |  |  |
| `video_position` | `select` | t:settings.video_position | cover |  |
| `background_image` | `image_picker` | t:settings.image |  | Recommended: 1920x1080px or larger background image; keep focal content away from edges. |
| `background_image_position` | `select` | t:settings.image_position | cover |  |
| `border` | `select` | t:settings.borders | none |  |
| `border_width` | `range` | t:settings.border_width | 1 |  |
| `border_opacity` | `range` | t:settings.border_opacity | 100 |  |
| `border_radius` | `range` | t:settings.border_radius | 0 |  |
| n/a | `header` | t:content.padding | | |
| `padding-block-start` | `range` | t:settings.top | 0 |  |
| `padding-block-end` | `range` | t:settings.bottom | 0 |  |

## Current Section Image Values

- `background_image`: No current image set in templates.

## Blocks

### `@theme`



### `@app`



### `_divider`



## Template Block Instances

### `email-signup`

Source: `blocks/email-signup.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `paragraph` | n/a | t:content.email_signups_create_customer_profiles | |
| `width` | `select` | t:settings.width | fill |
| `custom_width` | `range` | t:settings.custom_width | 100 |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | True |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | primary |
| `header` | n/a | t:content.heading | |
| `heading` | `text` | t:settings.text |  |
| `heading_preset` | `select` | t:settings.type_preset | h3 |
| `header` | n/a | t:content.input | |
| `border_style` | `select` | t:settings.border | all |
| `border_width` | `range` | t:settings.border_width | 1 |
| `border_radius` | `range` | t:settings.border_radius | 100 |
| `input_type_preset` | `select` | t:settings.type_preset | paragraph |
| `header` | n/a | t:content.submit_button | |
| `style_class` | `select` | t:settings.style | button |
| `display_type` | `select` | t:settings.display | text |
| `label` | `text` | t:settings.label | t:text_defaults.sign_up |
| `integrated_button` | `checkbox` | t:settings.integrated_button | False |
| `button_type_preset` | `select` | t:settings.type_preset | paragraph |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `logo`

Source: `blocks/logo.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `inverse` | `checkbox` | t:settings.use_inverse_logo | False |
| `font` | `select` | t:settings.font | heading |
| `paragraph` | n/a | t:content.edit_logo_in_theme_settings | |
| `header` | n/a | t:content.size | |
| `unit` | `select` | t:settings.unit | percent |
| `percent_width` | `range` | t:settings.width | 100 |
| `pixel_height` | `range` | t:settings.height | 48 |
| `custom_mobile_size` | `checkbox` | t:settings.custom_mobile_size | False |
| `header` | n/a | t:content.mobile_size | |
| `unit_mobile` | `select` | t:settings.unit | percent |
| `percent_width_mobile` | `range` | t:settings.width | 100 |
| `pixel_height_mobile` | `range` | t:settings.height | 120 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

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

Direct snippets: `background-media`, `border-override`, `layout-panel-style`, `spacing-style`
