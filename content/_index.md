---
# Leave the homepage title empty to use the site title
title:
date: 2025-09-03
type: landing

sections:
  - block: hero
    content:
      title: |
        Exploring Utopian Visions
      text: |
        <br>
        The **Utopia Research Group** was founded with the aim of exploring social dreaming and utopian visions, combining interdisciplinary approaches to study societal change. We are committed to leveraging the latest quantitative and qualitative research tools to drive innovation in understanding the dynamics of societal transformation.
        <br>
        <div style="display: flex; justify-content: space-between;">
          <ul style="width: 45%;">
            <li><strong>Research Questions</strong></li>
            <li>Research Question 1</li>
            <li>Research Question 2</li>
            <li>Research Question 3</li>
          </ul>

          <ul style="width: 45%;">
            <li><strong>Tools</strong></li>
            <li>Tool 1</li>
            <li>Tool 2</li>
            <li>Tool 3</li>
          </ul>
        </div>
  - block: collection
    content:
      title: Latest News
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
      view: card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
