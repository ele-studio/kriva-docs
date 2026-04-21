# Template: page.article.json

Source: `templates/page.article.json`

## Page Structure

1. [main-page](../sections/main-page.md) (`main`)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`heading` - Title disabled)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `page-content` (`page-content`)

## Component Dependencies

Sections: [main-page](../sections/main-page.md)
Blocks: `page-content`, `text`
Snippets: `gap-style`, `layout-panel-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
Web Components: `rte-formatter`
