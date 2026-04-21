# Template: page.json

Source: `templates/page.json`

## Page Structure

1. [main-page](../sections/main-page.md) (`main` disabled)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`heading` - Title)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `page-content` (`page-content`)
2. [common-hero](../sections/common-hero.md) (`common_hero_RMh9R7`)
   - Name: Common Hero Section
   - Section settings: `description`, `heading`, `hero_image`, `how_button`, `shop_button`
3. [why-kriva](../sections/why-kriva.md) (`why_kriva_xHbhFe`)
   - Name: Why Kriva
   - Section settings: `description_1`, `description_2`, `description_3`, `heading`, `kriva_image`, `kriva_image_bg`, `position_image`
4. [science-integrity](../sections/science-integrity.md) (`science_integrity_thFe87`)
   - Name: Science Integrity
   - Section settings: `description`, `focus_text`, `heading`, `position_image`, `science_image`, `science_image_bg`
   - Blocks:
       - `focus_text` (`focus_text_kfjekN`)
         - Settings: `list_item`
       - `focus_text` (`focus_text_aUPLTi`)
         - Settings: `list_item`
       - `focus_text` (`focus_text_36UxK8`)
         - Settings: `list_item`
       - `focus_text` (`focus_text_rxAhHb`)
         - Settings: `list_item`
       - `focus_text` (`focus_text_qkLV7b`)
         - Settings: `list_item`
5. [kriva-athletic](../sections/kriva-athletic.md) (`kriva_athletic_dLqnbV`)
   - Name: Kriva Athletic
   - Section settings: `heading`, `position_image`
   - Blocks:
       - `athletic_board` (`athletic_board_KDCJed`)
         - Settings: `athletic_image`, `description`, `title`
       - `athletic_board` (`athletic_board_aaQUtq`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_Uj6Jqn`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_6Rq3Rw`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_FpaqPN`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_jAmxpw`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_KLzttp`)
         - Settings: `description`, `title`
       - `athletic_board` (`athletic_board_EfbH7Y`)
         - Settings: `description`, `title`

## Component Dependencies

Sections: [main-page](../sections/main-page.md), [common-hero](../sections/common-hero.md), [why-kriva](../sections/why-kriva.md), [science-integrity](../sections/science-integrity.md), [kriva-athletic](../sections/kriva-athletic.md)
Blocks: `athletic_board`, `focus_text`, `page-content`, `text`
Snippets: `gap-style`, `layout-panel-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
Web Components: `rte-formatter`
