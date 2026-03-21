---
title: ''
summary: ''
date: 2022-10-24
type: landing
design:
  spacing: '6rem'
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: circle
  - block: resume-skills
    content:
      title: Навыки
      username: me
    design:
      show_skill_percentage: false
  - block: resume-experience
    content:
      title: Опыт
      username: me
    design:
      date_format: January 2006
  - block: resume-awards
    content:
      title: Достижения
      username: me
  - block: collection
    id: news
    content:
      title: Записи
      subtitle: ''
      text: ''
      page_type: post
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
