# Section: main-cart

Source: `sections/main-cart.liquid`

## Purpose

`main-cart` renders the t:names.cart section. It composes Horizon block components with `content_for 'block'`. It delegates repeated markup to snippets. It uses Web Components for interactive behavior.

## Used By Templates

- [cart.json](../templates/cart.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `section_width` | `select` | t:settings.width | page-width |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-1 |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |

## Blocks

### `@theme`



### `@app`



### `text`



### `icon`



### `image`



### `button`



### `video`



### `group`



### `spacer`



## Template Block Instances

### `_cart-products`

Source: `blocks/_cart-products.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `gap` | `range` | t:settings.gap | 24 |
| `image_ratio` | `select` | t:settings.aspect_ratio | adapt |
| `dividers` | `checkbox` | t:settings.dividers | True |
| `vendor` | `checkbox` | t:settings.vendor | False |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 0 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

### `_cart-summary`

Source: `blocks/_cart-summary.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `extend_summary` | `checkbox` | t:settings.extend_summary | True |
| `inherit_color_scheme` | `checkbox` | t:settings.inherit_color_scheme | False |
| `color_scheme` | `color_scheme` | t:settings.color_scheme | scheme-3 |
| `header` | n/a | t:content.borders | |
| `border` | `select` | t:settings.style | none |
| `border_width` | `range` | t:settings.thickness | 1 |
| `border_opacity` | `range` | t:settings.opacity | 100 |
| `border_radius` | `range` | t:settings.border_radius | 0 |

### `_cart-title`

Source: `blocks/_cart-title.liquid`

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `title` | `inline_richtext` | t:settings.cart_title | t:text_defaults.cart |
| `show_count` | `checkbox` | t:settings.cart_count | True |
| `header` | n/a | t:content.typography | |
| `type_preset` | `select` | t:settings.preset |  |
| `alignment` | `text_alignment` | t:settings.alignment | left |
| `header` | n/a | t:content.padding | |
| `padding-block-start` | `range` | t:settings.top | 16 |
| `padding-block-end` | `range` | t:settings.bottom | 0 |
| `padding-inline-start` | `range` | t:settings.left | 0 |
| `padding-inline-end` | `range` | t:settings.right | 0 |

## Liquid Dependencies

Content-for blocks: `_cart-products`, `_cart-summary`, `_cart-title`
Direct snippets: `spacing-style`
Web Components: `cart-items-component`
