# Template: page.community.json

Source: `templates/page.community.json`

## Page Structure

1. [main-page](../sections/main-page.md) (`main` disabled)
   - Section settings: `color_scheme`, `content_direction`, `gap`, `padding-block-end`, `padding-block-start`
   - Blocks:
       - `text` (`heading` - Title)
         - Settings: `alignment`, `background`, `background_color`, `case`, `color`, `corner_radius`, `font`, `font_size`, `letter_spacing`, `line_height`, `max_width`, `padding-block-end`, `padding-block-start`, `padding-inline-end`, `padding-inline-start`, `text`, `type_preset`, `width`, `wrap`
       - `page-content` (`page-content`)
2. [common-hero](../sections/common-hero.md) (`common_hero_RMh9R7`)
   - Name: Common Hero Section
   - Section settings: `description`, `heading`, `hero_image`, `how_button`, `how_url`, `shop_button`, `shop_url`
3. [athelete-stories](../sections/athelete-stories.md) (`athelete_stories_tgz4L9` disabled)
   - Name: Athelete Stories
   - Section settings: `description`, `heading`
   - Blocks:
       - `stories` (`stories_QYgA4y`)
         - Settings: `batch_1`, `batch_2`, `batch_3`, `image`, `position`, `story_description`, `story_name`, `using_duration`
       - `stories` (`stories_Vh97Wn`)
         - Settings: `batch_1`, `batch_2`, `batch_3`, `image`, `position`, `story_description`, `story_name`, `using_duration`
       - `stories` (`stories_wk3pnq`)
         - Settings: `batch_1`, `batch_2`, `batch_3`, `image`, `position`, `story_description`, `story_name`, `using_duration`
       - `stories` (`stories_4yNgjV`)
         - Settings: `batch_1`, `batch_2`, `batch_3`, `image`, `position`, `story_description`, `story_name`, `using_duration`
4. [what-atheletes](../sections/what-atheletes.md) (`what_atheletes_iQADaR`)
   - Name: Athelete Say
   - Section settings: `heading`, `paragraph`
   - Blocks:
       - `review` (`review_jJqB8X`)
         - Settings: `cta_text`, `description`, `like_people`, `post_date`, `text_heading`, `title`
       - `review` (`review_HJAbqm`)
         - Settings: `cta_text`, `description`, `like_people`, `post_date`, `text_heading`, `title`
       - `review` (`review_N6eqFd`)
         - Settings: `cta_text`, `description`, `like_people`, `post_date`, `text_heading`, `title`
       - `review` (`review_zqYAY8`)
         - Settings: `cta_text`, `description`, `like_people`, `post_date`, `text_heading`, `title`
5. [latest-blog](../sections/latest-blog.md) (`latest_blog_WWYdPW` disabled)
   - Name: Latest Blogs
   - Section settings: `button`, `description`, `heading`
6. [become-ambassador](../sections/become-ambassador.md) (`become_ambassador_Cyc9xF`)
   - Name: Become Ambassador
   - Section settings: `description`, `heading`, `qualification_text`
   - Blocks:
       - `qualification_card` (`qualification_card_ttMd8U`)
         - Settings: `cards_description`, `icon_image`, `title`
       - `qualification_card` (`qualification_card_3NT7zC`)
         - Settings: `cards_description`, `icon_image`, `title`
       - `qualification_card` (`qualification_card_Jkty6M`)
         - Settings: `cards_description`, `icon_image`, `title`
       - `qualification_card` (`qualification_card_HEfAGK`)
         - Settings: `cards_description`, `icon_image`, `title`
       - `qualification` (`qualification_BHA3ff`)
         - Settings: `list`
       - `qualification` (`qualification_edEE4y`)
         - Settings: `list`
       - `qualification` (`qualification_wLWdt8`)
         - Settings: `list`
       - `qualification` (`qualification_nW6RwQ`)
         - Settings: `list`
7. [latest-blog](../sections/latest-blog.md) (`latest_blog_UVhMJP` disabled)
   - Name: Latest Blogs
   - Section settings: `button`, `description`, `heading`

## Component Dependencies

Sections: [main-page](../sections/main-page.md), [common-hero](../sections/common-hero.md), [athelete-stories](../sections/athelete-stories.md), [what-atheletes](../sections/what-atheletes.md), [latest-blog](../sections/latest-blog.md), [become-ambassador](../sections/become-ambassador.md), [latest-blog](../sections/latest-blog.md)
Blocks: `page-content`, `qualification`, `qualification_card`, `review`, `stories`, `text`
Snippets: `gap-style`, `layout-panel-style`, `size-style`, `spacing-padding`, `spacing-style`, `text`, `typography-style`
Web Components: `rte-formatter`
