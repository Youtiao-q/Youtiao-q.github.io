---
title: 示例活动

event: Wowchemy 会议
event_url: https://example.org

location: Wowchemy 总部
address:
  street: 450 Serra Mall
  city: 斯坦福
  region: CA
  postcode: '94305'
  country: 美国

summary: 一个示例活动。
abstract: '这是一个示例活动的抽象描述。在这里可以介绍活动的主要内容和亮点，吸引读者的兴趣。'

# 活动开始和结束时间。
#   结束时间可以通过在前面添加 `#` 来隐藏。
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# 日程页面发布日期（不是活动日期）。
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# 这是一个特色活动吗？（true/false）
featured: false

image:
  caption: '图片来源: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown 幻灯片（可选）。
#   将此活动与 Markdown 幻灯片关联。
#   只需输入幻灯片文件的文件名（不带扩展名）。
#   例如，`slides = "example-slides"` 引用 `content/slides/example-slides.md`。
#   否则，设置 `slides = "".
slides:

# 项目（可选）。
#   将此帖子与一个或多个项目关联。
#   只需输入项目的文件夹或文件名（不带扩展名）。
#   例如，`projects = ["internal-project"]` 引用 `content/project/deep-learning/index.md`。
#   否则，设置 `projects = [].
projects:
share: false # 是否隐藏分享功能
profile: false # 是否隐藏作者个人信息
# authors: ["admin"]  # 明确指定作者

# 图片画廊项目（可选）
#   为画廊中的图片添加说明
gallery_item:
  - album: event-gallery
    image: city-smart.webp
    caption: "智慧城市展示"
  - album: event-gallery
    image: contact.jpg
    caption: "活动现场交流"
  - album: event-gallery
    image: data-governance.webp
    caption: "数据治理研讨"
  - album: event-gallery
    image: knowledge-engineering.webp
    caption: "知识工程展示"
  - album: event-gallery
    image: multi-modal.webp
    caption: "多模态智能演示"
---

幻灯片可以通过以下几种方式添加：

- **创建** 使用 Wowchemy 的 [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) 功能创建幻灯片，并在活动文件的前端 matter 中使用 `slides` 参数链接
- **上传** 将现有的幻灯片 deck 上传到 `static/` 文件夹，并在活动文件的前端 matter 中使用 `url_slides` 参数链接
- **嵌入** 使用 [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/) 在本页面嵌入您的幻灯片（如 Google Slides）或演示视频。

更多活动详情，包括图片画廊等页面元素，可以添加到本页面的正文部分。

## 图片画廊

以下是活动现场的精彩瞬间：

{{< gallery album="event-gallery" layout="single" page_bundle="true" >}}
