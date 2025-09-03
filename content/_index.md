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
      image: 
        filename: welcome.jpg
      text: |
        <br>
        <div text-align: justify;">
          The <strong>Utopia Research Group</strong> was founded to explore social dreams and utopian visions through interdisciplinary approaches. We are dedicated to employing cutting-edge quantitative and qualitative research tools to uncover prevailing societal visions and spark discussions that inspire transformative change.
        </div>
  - block: markdown
    content:
      title: |
       Research Focus and Methodological Tools:
      subtitle: '<i>Leveraging state-of-the-art methods to motivate discussion about possible future of society.</i>'
      text: |
        <div id="columnsFrontPage">
          <!-- Left side: Research Questions -->
          <ul>
            <li><strong style="font-size: 30px;">Research Questions</strong></li>
            <li>Research Question 1</li>
            <li>Research Question 2</li>
            <li style="padding-left: 20px;"><span style="font-size: 30px;">&#8594;</span> Interdisciplinary research in Philosophy and Computer Science</li>
          </ul>

          <!-- Right side: Tools -->
          <ul>
            <li><strong style="font-size: 30px;">Tools</strong></li>
            <li><strong>Qualitative:</strong> Developed an interactive mind map tool for large-scale qualitative data collection and analysis (see <a href="https://drawyourminds.de" target="_blank">drawyourminds.de</a>).</li>
            <li><strong>Quantitative:</strong> Expertise in statistical methods (e.g., Psychometrics, Machine Learning, Language Model Analysis).</li>
            <li style="padding-left: 20px;"><span style="font-size: 30px;">&#8594;</span> <strong>Methodological Innovation:</strong> Development of web-based platforms, linked to relational databases, to develop interactive tools for innovative data collection and analysis.</li>
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
