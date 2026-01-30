---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Shenzhen University (SZU) is a comprehensive university located in Shenzhen, China's first Special Economic Zone. It is known for its innovative education, strong research capabilities, and close ties to the Greater Bay Area's tech and innovation ecosystem. We welcome collaborations, visits, and inquiries.
      email: international@szu.edu.cn  # 或你的实验室/学院邮箱，例如你的组邮箱
      phone: +86 755 26536177         # 研究生招生通用电话，可换成具体部门电话如 0755-26536198（电子信息学院示例）
      address:
        street: 3688 Nanhai Avenue
        city: Nanshan District, Shenzhen
        region: Guangdong
        postcode: '518060'
        country: China
        country_code: CN
      coordinates:
        latitude: '22.5393'
        longitude: '113.9337'
      directions: Enter Yuehai Campus (粤海校区) via the main gate on Nanhai Avenue. Head to Huiyuan Building (汇元楼) for most administrative offices.
      office_hours:
        - 'Monday to Friday 08:30 to 12:00'
        - 'Monday to Friday 14:00 to 17:30'
      appointment_url: 'https://calendly.com'  # 可替换成你的预约链接，如微信小程序或学校系统
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
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
        # image: 
        #   # filename: contact.jpg          # 你可以替换成深圳大学的校园照片，如粤海校区或丽湖校区图片
        #   filters:
        #     brightness: 1
        #   parallax: false
        #   position: center
        #   size: cover
        #   text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---