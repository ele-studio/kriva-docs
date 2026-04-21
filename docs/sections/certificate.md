# Section: certificate

Source: `sections/certificate.liquid`

## Purpose

`certificate` renders the Certificate section.

## Used By Templates

- [page.transparency.json](../templates/page.transparency.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `heading` | `text` | Heading |  |  |
| `description` | `text` | Description |  |  |
| `placeholder` | `text` | Placeholder Text | Premium Omega-3 Fish Oil |  |
| `product_name` | `text` | Product Name |  |  |
| `batches` | `text` | Batches |  |  |
| `trust_image` | `image_picker` | Trust Image |  | Recommended: 511x351px minimum rendered ratio (511:351); upload 2x if available. |

## Current Section Image Values

- `trust_image`: `Trans2_-_v1.png` in page.transparency.json

## Blocks

### `option`

Dropdown Option

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `label` | `text` | Option Label | Omega 3 Capsules |
| `value` | `text` | Option Value | omega-3 |

### `batches`

Product Batches

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `product_title` | `text` | Product Title |  |
| `tag` | `text` | Tag |  |
| `production_date` | `text` | Production Date |  |
| `expiry_date` | `text` | Expiry Date |  |
| `test_date` | `text` | Test Date |  |
| `tested_by` | `text` | Tested By |  |

## Template Block Instances

### `batches`

No standalone block schema settings were found, or this is a local/custom block type.

### `option`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
