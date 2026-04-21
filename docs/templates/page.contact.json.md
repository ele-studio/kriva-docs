# Template: page.contact.json

Source: `templates/page.contact.json`

## Page Structure

1. [new-hero-section](../sections/new-hero-section.md) (`new_hero_section_RdWfPm`)
   - Name: New Hero Section
   - Section settings: `alignment`, `background_color`, `background_options`, `description`, `heading`, `hero_image`, `hero_image_mobile`, `how_button`, `how_url`, `min_height_desktop`, `overlay_color`, `overlay_enable`, `overlay_opacity`, `shop_button`, `shop_url`
2. [common-hero](../sections/common-hero.md) (`common_hero_QbGFfd` disabled)
   - Name: Common Hero Section
   - Section settings: `description`, `heading`, `hero_image`, `how_button`, `how_url`, `shop_button`, `shop_url`
3. [main-page](../sections/main-page.md) (`main` disabled)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`title` - t:names.title)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `text` (`content` - t:names.content)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
4. [section](../sections/section.md) (`form`)
   - Name: t:names.contact_form
   - Section settings: `align_baseline`, `background_image_position`, `background_media`, `border`, `border_opacity`, `border_radius`, `border_width`, `color_scheme`, `content_direction`, `gap`, `gradient_direction`, `horizontal_alignment`, `horizontal_alignment_flex_direction_column`, `overlay_color`, `overlay_style`, `padding-block-end`, `padding-block-start`, `section_height`, `section_height_custom`, `section_width`, `toggle_overlay`, `vertical_alignment`, `vertical_alignment_flex_direction_column`, `vertical_on_mobile`, `video_position`
   - Blocks:
       - `contact-form` (`contact_form_UwiCkQ`)
         - Settings: `color_scheme`, `contact_heading`, `custom_width`, `custom_width_mobile`, `description`, `email_label`, `follow_heading`, `heading`, `inherit_color_scheme`, `inquiry_label`, `interested_cta`, `interested_description`, `interested_heading`, `message_label`, `name_label`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `phone_label`, `width`, `width_mobile`
         - `contact-form-submit-button` (`submit-button` static)
           - Settings: `custom_width`, `custom_width_mobile`, `label`, `style_class`, `width`, `width_mobile`

## Component Dependencies

Sections: [new-hero-section](../sections/new-hero-section.md), [common-hero](../sections/common-hero.md), [main-page](../sections/main-page.md), [section](../sections/section.md)
Blocks: `contact-form`, `contact-form-submit-button`, `text`
Snippets: `background-media`, `border-override`, `contact-form`, `gap-style`, `layout-panel-style`, `overlay`, `section`, `size-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
