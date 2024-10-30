---
title: PrincipalInvestigators
date: 2022-10-24

type: landing
sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: dongchuan road
        city: Shanghai
        region: minghang
        postcode: '124000'
        country: China
        country_code: CNA
      coordinates:
        latitude: '31.023754'
        longitude: '121.426156'
      directions: Enter Building and take the stairs to the thrid floor
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
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
# 中文信息

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="width: 30%;">
    <img src="featured.jpg" alt="Featured Image" style="width: 100%;">
  </div>
  <div style="width: 70%;">
    ## 工作经历
    - **2023-至今** 上海交通大学溥渊未来技术学院 副教授
    - **2020-2022** 英国牛津大学材料系 博士后
    - **2018-2020** 美国德克萨斯大学奥斯汀分校 博士后

    ## 所获荣誉
    - 2018年度美国电化学协会K.M. Abraham奖
    - 2018年度国家优秀自费留学生奖

    ## 科研项目
    - 2024-2026,国家自然科学基金青年基金项目,锂氧气电池气体扩散还原动力学机制及其调控探究,主持,负责人

    ## 学术兼职
    - 《Material Today Energy》,《SusMat》青年编委
  </div>
</div>
