---
# Leave the homepage title empty to use the site title
title: home
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the Gao group
        content: We are dedicating to the next generation energy conversion material
        align: center
        background:
          image:
            filename: peter_group.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        
        The **Gao lab** has been a center of excellence for next generation battery research, teaching, and practice since its founding in 2023.
  
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
      flip_alt_rows: false
  

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: list
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
