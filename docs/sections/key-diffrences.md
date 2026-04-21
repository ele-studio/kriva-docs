# Section: key-diffrences

Source: `sections/key-diffrences.liquid`

## Purpose

`key-diffrences` renders the Key Diffrences section.

## Used By Templates

- [page.education.json](../templates/page.education.json.md)

## Schema Settings

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `heading` | `text` | Heading |  |  |
| `position_image` | `image_picker` | Position Image |  | Recommended: 235x235px minimum rendered ratio (1:1); upload 2x if available. |

## Current Section Image Values

- `position_image`: `footer-img.png` in page.education.json

## Blocks

### `row`

Table Row

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `feature` | `text` | Feature | FORM |
| `cbda_text` | `textarea` | CBDA Content |  |
| `cbd_text` | `textarea` | CBD Content |  |

## Template Block Instances

### `row`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
