---
# Leave the homepage title empty to use the site title
title:
date: 2023-01-23
type: landing

sections:
  - block: hero
    content:
      title: |
        Policy Advocacy in
        Science and Engineering
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **Policy Advocacy in Science and Engineering (PASE)** seeks to bring attention to policy issues in science and engineering and teach students how to practice social responsibility, with a focus on skills and training related to science communication and policy advocacy.

  
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="https://gator-pase.netlify.app/people" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
