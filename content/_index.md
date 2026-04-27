---
# 首页配置
title: ""
summary: ""
date: 2026-04-26
type: landing

sections:
  # 1. 个人简介与教育背景 (必须保留)
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      avatar:
        size: medium
        shape: circle

  # 2. 研究方向描述 (把原先那个 Moonshot 的例子改掉)
  - block: markdown
    content:
      title: '📊 Research Focus'
      subtitle: ''
      text: |
        My current research employs microeconometric methods to investigate structural issues in the labor market. Specifically, I am analyzing **labor mismatch** and **youth unemployment** using the China Household Income Project (CHIP) database to provide evidence-based policy evaluations.
    design:
      columns: '1'

  # 3. 论文展示 (保留，以后你有论文了会自动显示在这里)
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
