# Section: athelete-stories

Source: `sections/athelete-stories.liquid`

## Purpose

`athelete-stories` renders the Athelete Stories section.

## Used By Templates

- [page.community.json](../templates/page.community.json.md)
- [page.education.json](../templates/page.education.json.md)

## Schema Settings

| ID | Type | Label | Default |
| --- | --- | --- | --- |
| `header` | n/a | Spacing | |
| `margin_top_desktop` | `range` | Top Margin - Desktop | 112 |
| `margin_bottom_desktop` | `range` | Bottom Margin - Desktop | 0 |
| `margin_top_mobile` | `range` | Top Margin - Mobile | 64 |
| `margin_bottom_mobile` | `range` | Bottom Margin - Mobile | 0 |
| `heading` | `text` | Heading |  |
| `description` | `text` | Description |  |

## Blocks

### `stories`

Stories

| ID | Type | Label | Default | Image guidance |
| --- | --- | --- | --- | --- |
| `image` | `image_picker` | Image |  | Recommended: 332x251px minimum rendered ratio (332:251); upload 2x if available. |
| `story_description` | `text` | Story Description |  |  |
| `batch_1` | `text` | Batch 1 |  |  |
| `batch_2` | `text` | Batch 2 |  |  |
| `batch_3` | `text` | Batch 3 |  |  |
| `story_name` | `text` | Story Name |  |  |
| `position` | `text` | Position |  |  |
| `using_duration` | `text` | Using Duration |  |  |
| `link` | `url` | Link |  |  |

Current image values:
- `image`: `amanda-rodriguez.png` in page.community.json, page.education.json<br>`david-park.png` in page.community.json<br>`jake-thompson.png` in page.community.json, page.education.json<br>`marcus-chen.png` in page.community.json, page.education.json

## Template Block Instances

### `stories`

No standalone block schema settings were found, or this is a local/custom block type.

## Liquid Dependencies

No direct Liquid component dependencies were detected.
