# Section: active-bodies

Source: `sections/active-bodies.liquid`

## Purpose

`active-bodies` renders the Active Bodies Tabs section. It delegates repeated markup to snippets.

## Used By Templates

- [index.json](../templates/index.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `heading` | `text` | Heading | Everyday Essentials for Active Bodies |
| `description` | `text` | Description | Simple, effective formulas that support movement, sleep, and daily performance. |
| `products_only` | `checkbox` | Show products only (hide collection info panel) | False |
| `products_limit` | `range` | Product cards per tab | 3 |

## Blocks

### `tab`

Collection Tab

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `tab_label` | `text` | Tab Label | LOTION |  |
| `products_source` | `select` | Product source | collection |  |
| `collection` | `collection` | Select Collection (used for Collection products) |  |  |
| `manual_products` | `product_list` | Manual products (used for Manual products source) |  |  |
| `collection_image` | `image_picker` | Select Collection Image |  | Recommended: preserve the current rendered aspect ratio; use at least 2x the rendered size when possible. |

Current image values:
- `collection_image`: `logo-white.png` in index.json

## Template Block Instances

### `tab`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

Direct snippets: `hero-tab-card`
