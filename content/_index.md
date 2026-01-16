---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 关注小红书
        url: https://xhslink.com/m/ADHojEmfGuL
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: winotd
    content:
      title: '🚀 WINOTD运动'
      subtitle: 'What I\'m Not Doing Today'
      text: |-
        WINOTD是一个关于坚持与改变的运动。每一天，我们都在选择不做什么，从而为真正重要的事情腾出空间。
        
        戒porn马拉松运动员，正在用每一天的坚持，重新定义自己。如果你也在寻找改变，欢迎加入我们！
        
        WINOTD is a movement about persistence and change. Every day, we choose what not to do, making room for what truly matters.
    design:
      columns: '1'
  - block: collection
    id: flow
    content:
      title: 随笔Flow
      subtitle: '随性而写，记录生活'
      text: '分享日常思考、生活感悟、旅行见闻'
      page_type: blog
      count: 6
      filters:
        tag: flow
        exclude_featured: false
    design:
      view: card
      columns: 2
  - block: collection
    id: reaction
    content:
      title: 读后感Reaction
      subtitle: '读书心得与思考'
      text: '分享阅读后的感受与启发'
      page_type: blog
      count: 6
      filters:
        tag: reaction
        exclude_featured: false
    design:
      view: card
      columns: 2
  - block: collection
    id: products
    content:
      title: 产品Products
      subtitle: 'AI产品与课程'
      text: '未来这里将展示AI付费产品和课程'
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: news
    content:
      title: 最新内容
      subtitle: 'Latest Content'
      text: '最新发布的博客内容'
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
