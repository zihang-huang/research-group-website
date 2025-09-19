---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: Hero
    content:
      title: "清华大学计算机系量子软件中心"
      text: "<br>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tincidunt commodo nulla, id faucibus erat rutrum id. Sed nibh nisi, commodo sit amet lacus in, congue scelerisque augue. Nullam lectus tortor, ornare eu aliquam non, malesuada ac odio.
      "

    design:
      background:
        gradient_start: '#8B008B'
        gradient_end: '#4B0082'
        text_color_light: true
      css_class: "hero-text-small"

          
  
  - block: collection
    content:
      title: 新闻动态
      subtitle:
      text:
      count: 5
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
      columns: '2'

  - block: collection
    content:
      title: 论文发表
      text: 
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '2'
---
