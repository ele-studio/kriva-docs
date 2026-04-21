# Template: article.json

Source: `templates/article.json`

## Page Structure

1. [main-blog-post](../sections/main-blog-post.md) (`section` disabled)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`blog-post-title` - Title static)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `_blog-post-info-text` (`blog-post-details` - Details static)
         - Settings: `alignment`, `padding-block-end`, `padding-block-start`, `show_alignment`, `show_author`, `show_date`, `type_preset`
       - `_blog-post-featured-image` (`blog-post-image` static)
         - Settings: `border`, `border_opacity`, `border_radius`, `border_width`, `custom_width`, `custom_width_mobile`, `height`, `image_ratio`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `width`, `width_mobile`
       - `_blog-post-content` (`blog-post-content` static)
2. [blog-details](../sections/blog-details.md) (`blog_details_jMJCiD`)
   - Name: Blog Details

## Component Dependencies

Sections: [main-blog-post](../sections/main-blog-post.md), [blog-details](../sections/blog-details.md)
Blocks: `_blog-post-content`, `_blog-post-featured-image`, `_blog-post-info-text`, `text`
Snippets: `blog-comment-form`, `border-override`, `gap-style`, `layout-panel-style`, `size-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
Web Components: `rte-formatter`
