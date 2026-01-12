---
title: 联系方式
date: 2026-01-12

type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |-
        欢迎联系我们！我们的研究团队专注于前沿技术研究，如有任何问题或合作意向，请随时与我们联系。
      email: xionghanqing@ecjtu.edu.cn
      phone: 138 8888 8888
      address:
        street: 江西省南昌市青山湖区双港东大街808号
        city: 南昌市
        region: 青山湖区
        postcode: '330013'
        country: 中国
        country_code: CN
      coordinates:
        latitude: '28.7509175'
        longitude: '115.8669716'
      directions: 乘坐地铁1号线到双港站，2号口出，步行约800米即到；或乘坐210路、223路、232路公交车到华东交通大学站
      office_hours:
        - '周一 09:00 至 17:00'
        - '周五 09:00 至 17:00'
      # appointment_url: 'https://calendly.com' # 预约链接
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: 在论坛讨论
      #    link: 'https://discourse.gohugo.io'
    
      # 自动链接邮箱和电话，或显示为纯文本？
      autolink: true
    
      # 邮箱表单提供商 - 隐藏表单
      form:
        provider: 
        formspree:
          id:
        netlify:
          # 启用验证码挑战以减少垃圾邮件？
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
