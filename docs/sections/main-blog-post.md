# Section: main-blog-post

Source: `sections/main-blog-post.liquid`

## Purpose

`main-blog-post` renders the t:names.blog_post section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets.

## Used By Templates

- [article.json](../templates/article.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `content_direction` | `select` | t:settings.direction | column |
| `gap` | `range` | t:settings.gap | 12 |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

### `@theme`



### `@app`



## Template Block Instances

### `_blog-post-content`

Source: `blocks/_blog-post-content.liquid`
No standalone block schema settings were found, or this is a local/custom block type.

### `_blog-post-featured-image`

Source: `blocks/_blog-post-featured-image.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `header` | n/a | t:content.size | |
| `image_ratio` | `select` | t:settings.aspect_ratio | adapt |
| `width` | `select` | t:settings.width_desktop | fill |
| `custom_width` | `range` | t:settings.custom_width | 100 |
| `width_mobile` | `select` | t:settings.width_mobile | fill |
| `custom_width_mobile` | `range` | t:settings.custom_width | 100 |
| `height` | `select` | t:settings.height | fit |
| `header` | n/a | t:content.borders | |
| `border` | `select` | t:settings.style | none |
| `border_width` | `range` | t:settings.thickness | 1 |
| `border_opacity` | `range` | t:settings.opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `_blog-post-info-text`

Source: `blocks/_blog-post-info-text.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `show_date` | `checkbox` | t:settings.show_date | True |
| `show_author` | `checkbox` | t:settings.show_author | True |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset |  |
| `alignment` | `text_alignment` | t:settings.alignment |  |
| `show_alignment` | `checkbox` | t:settings.show_alignment | True |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 24 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

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

Content-for blocks: `_blog-post-content`, `_blog-post-featured-image`, `_blog-post-info-text`, `text`
Direct snippets: `blog-comment-form`, `layout-panel-style`, `spacing-style`
