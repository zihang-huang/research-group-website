---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        清华大学计算机系量子软件中心
      text:
        <br>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras pulvinar dui urna, vel rutrum lectus pretium sit amet. Praesent non eleifend nisi, in porttitor dui. Nunc et augue vestibulum, sollicitudin nulla at, accumsan dui. Integer vestibulum nisl bibendum dapibus aliquam. Etiam lectus velit, interdum sed erat at, viverra cursus metus.

    design:
      background:
        gradient_start: '#8B008B'
        gradient_end: '#4B0082'
        text_color_light: true
          
  
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
