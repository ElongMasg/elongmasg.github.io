---
# Leave the homepage title empty to use the site title
title: home
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Future technology of energy and material
        Research Group
      image:
        filename: peter_group.jpg
      text: |
        <br>
        
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
        publication_type: 'article'
    design:
      view: citation
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
