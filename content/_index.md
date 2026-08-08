---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
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
    content:
      title: '👋 Welcome'
      subtitle: ''
      text: |-
        I'm an Information Technology student passionate about full-stack development, machine learning, and building practical, real-world solutions.

        I love picking up new technologies, working on projects that solve real problems, and collaborating with others who are curious about tech.

        Feel free to check out my projects below, or reach out — I'm always open to connecting! 😃
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
---
