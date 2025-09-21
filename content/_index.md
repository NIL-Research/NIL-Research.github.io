---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Neurocognitive

        Image Lab
      image:
        filename: brain-welcome.jpg
      text: |
        <br>
        
        The **Neurocognitive Image Lab** is an interdisciplinary research hub at the forefront of brain science, neuroaesthetics, and visual cognition. Bridging disciplines across time and space, the lab explores how the brain encodes perception, aesthetics, and temporal experience, advancing innovative theories and applications in neuroscience, art, and intelligent interaction.
  
  - block: markdown
    content:
      title: Research Community
      subtitle: Learn more about our academic environment and partners
      text: |
        <div style="display:flex; gap:20px; flex-wrap:wrap;">
          <a href="/conference/introductions/introducing-sisu" style="text-decoration:none; color:black; width:30%;">
            <div style="border:1px solid #ccc; padding:10px; text-align:center;">
              <img src="/images/SISU-logo.png" style="max-width:100%;height:150px; object-fit:contain;display:block; margin:0 auto;">
              <h3>SISU</h3>
              <p>Our University</p>
            </div>
          </a>
          <a href="/conference/introductions/introducing-nil" style="text-decoration:none; color:black; width:30%;">
            <div style="border:1px solid #ccc; padding:10px; text-align:center;">
              <img src="/images/NIL-logo.png" style="max-width:100%;height:150px; object-fit:contain;display:block; margin:0 auto;">
              <h3>NIL</h3>
              <p>Neurocognitive Image Lab</p>
            </div>
          </a>
          <a href="/conference/introductions/introducing-wai" style="text-decoration:none; color:black; width:30%;">
            <div style="border:1px solid #ccc; padding:10px; text-align:center;">
              <img src="/images/WAI-logo.jpg" style="max-width:100%;height:150px; object-fit:contain;display:block; margin:0 auto;">
              <h3>WAI</h3>
              <p>World Arthistory Institute</p>
            </div>
          </a>
        </div>
    #   count: 0 # all in folders
    #   filters:
    #     folders:
    #       - conference/introductions
    #   offset: 0
    #   order: asc
    # design:
    #   view: card
    #   columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
