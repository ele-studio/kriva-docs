# Template: page.transparency.json

Source: `templates/page.transparency.json`

## Page Structure

1. [main-page](../sections/main-page.md) (`main` disabled)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`heading` - Title)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `page-content` (`page-content`)
2. [new-hero-section](../sections/new-hero-section.md) (`new_hero_section_tnbhAy`)
   - Name: New Hero Section
   - Section settings: `alignment`, `background_color`, `background_options`, `description`, `heading`, `hero_image`, `hero_image_mobile`, `how_button`, `how_url`, `min_height_desktop`, `overlay_color`, `overlay_enable`, `overlay_opacity`, `shop_button`, `shop_url`
3. [common-hero](../sections/common-hero.md) (`common_hero_RMh9R7` disabled)
   - Name: Common Hero Section
   - Section settings: `description`, `heading`, `hero_image`, `how_button`, `how_url`, `shop_button`, `shop_url`
4. [latest-blog](../sections/latest-blog.md) (`latest_blog_YtcVjy` disabled)
   - Name: Latest Blogs
   - Section settings: `button`, `description`, `heading`
5. [certificate](../sections/certificate.md) (`certificate_hj9dLG`)
   - Name: Certificate
   - Section settings: `batches`, `description`, `heading`, `placeholder`, `product_name`, `trust_image`
   - Blocks:
       - `batches` (`batches_3GQtcq`)
         - Settings: `expiry_date`, `product_title`, `production_date`, `tag`, `test_date`, `tested_by`
       - `batches` (`batches_tjLzaW`)
         - Settings: `expiry_date`, `product_title`, `production_date`, `tag`, `test_date`, `tested_by`
       - `batches` (`batches_bMKDmR`)
         - Settings: `expiry_date`, `product_title`, `production_date`, `tag`, `test_date`, `tested_by`
       - `option` (`option_xtidbK`)
         - Settings: `label`, `value`
       - `option` (`option_EUf9fe`)
         - Settings: `label`, `value`
       - `option` (`option_dPzPkz`)
         - Settings: `label`, `value`
6. [testing-process](../sections/testing-process.md) (`testing_process_VqWKhh`)
   - Name: Testing Process
   - Section settings: `description`, `heading`
   - Blocks:
       - `process` (`process_BznEf9`)
         - Settings: `icon`, `process_description`, `process_name`
       - `process` (`process_Tg9RtW`)
         - Settings: `icon`, `process_description`, `process_name`
       - `process` (`process_DQaJCg`)
         - Settings: `icon`, `process_description`, `process_name`
7. [accredited](../sections/accredited.md) (`accredited_F4UYTP`)
   - Name: Accredited
   - Section settings: `center_heading`, `heading`
   - Blocks:
       - `partners` (`partners_UBGhzi`)
         - Settings: `batch`, `description`, `title`
       - `partners` (`partners_LdGB4Q`)
         - Settings: `batch`, `description`, `title`
       - `partners` (`partners_ygyiBA`)
         - Settings: `batch`, `description`, `title`

## Component Dependencies

Sections: [main-page](../sections/main-page.md), [new-hero-section](../sections/new-hero-section.md), [common-hero](../sections/common-hero.md), [latest-blog](../sections/latest-blog.md), [certificate](../sections/certificate.md), [testing-process](../sections/testing-process.md), [accredited](../sections/accredited.md)
Blocks: `batches`, `option`, `page-content`, `partners`, `process`, `text`
Snippets: `gap-style`, `layout-panel-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
Web Components: `rte-formatter`
