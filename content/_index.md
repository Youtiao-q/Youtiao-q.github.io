---
# Leave the homepage title empty to use the site title
title: 主页
date: 2026-01-12
type: landing

sections:
  - block: hero
    content:
      title: 
        “AI花椒”
        <br>
        人工智能创新团队
      image:
        filename: welcome.jpg
      text: |
        <br>

        **“AI花椒”人工智能创新团队**成立于2022年，是华东交通大学中的一个人工智能创新团队。团队致力于推动人工智能技术的发展。实验室主要从事大语言模型、知识图谱、数据工程与知识工程、数据治理、自然语言处理、多模态智能等方面的研究工作。
  
  # - block: collection
  #   content:
  #     title: 近期通知
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: news
  #   design:
  #     view: card
  #     columns: '1'
  
  - block: slider
    content:
      slides:
      - title: 👋 欢迎来到 "AI花椒" 团队
        content: 看看我们正在进行的工作...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: 午餐与学习 ☕️
        content: 与团队分享您的知识，一起探索令人兴奋的新话题！
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 人工智能实验室
        content: 专注于大语言模型、知识图谱、数据工程与知识工程、数据治理、自然语言处理、多模态智能等方面的研究！
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: 加入我们
          url: ./contact/
    design:
      slide_height: ''
      is_fullscreen: true
      loop: false
      interval: 2000

  - block: features
    content:
      title: 研究方向
      subtitle: Research Directions
      items:
        - name: 智慧治理与行业智能
          description: 致力于将大模型与知识图谱应用于智慧治理，提升行业智能化水平，实现数据驱动的决策支持。
          image: city-smart.webp
          image_position: left
        - name: 大模型与数据治理
          description: 专注于大规模语言模型的开发和优化，研究数据治理技术以确保数据的准确性、安全性和可用性。
          image: data-governance.webp
          image_position: right
        - name: 多模态智能
          description: 探索图像、文本、音频等多种数据模态的融合与分析，构建跨模态的智能应用系统。
          image: multi-modal.webp
          image_position: left
        - name: 知识工程
          description: 研究知识表示、知识获取和知识推理技术，构建高效的知识库和知识图谱系统。
          image: knowledge-engineering.webp
          image_position: right
    design:
      columns: '1'

  # - block: collection
  #   content:
  #     title: 近期论文
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - papers
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./contact/" cta_text="加入我们 →" %}}
  #   design:
  #     columns: '1'
---
