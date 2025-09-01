---
# Leave the homepage title empty to use the site title
title: OpticsSnacks
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        OpticsSnacks
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Dr. Simon Spelthann is a **physicist** working at the interface of photonics and nanotechnology.
  
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
