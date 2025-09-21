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
        <div style="display:flex; flex-direction:column; align-items:center; gap:20px;">
          
          <a href="/conference/introductions/introducing-sisu" style="text-decoration:none; color:black; width:100%; max-width:600px;">
            <div style="border:1px solid #ccc; padding:10px; display:flex; align-items:flex-start; gap:15px;">
              <img src="/images/SISU-logo.png" style="width:120px; height:120px; object-fit:contain; flex-shrink:0;">
              <div style="display:flex; flex-direction:column; justify-content:flex-start;">
                <h3 style="margin:0;">SISU</h3>
                <p style="margin:5px 0 0 0;">Our University</p>
              </div>
            </div>
          </a>

          <a href="/conference/introductions/introducing-nil" style="text-decoration:none; color:black; width:100%; max-width:600px;">
            <div style="border:1px solid #ccc; padding:10px; display:flex; align-items:flex-start; gap:15px;">
              <img src="/images/NIL-logo.png" style="width:120px; height:120px; object-fit:contain; flex-shrink:0;">
              <div style="display:flex; flex-direction:column; justify-content:flex-start;">
                <h3 style="margin:0;">NIL</h3>
                <p style="margin:5px 0 0 0;">Neurocognitive Image Lab</p>
              </div>
            </div>
          </a>

          <a href="/conference/introductions/introducing-wai" style="text-decoration:none; color:black; width:100%; max-width:600px;">
            <div style="border:1px solid #ccc; padding:10px; display:flex; align-items:flex-start; gap:15px;">
              <img src="/images/WAI-logo.jpg" style="width:120px; height:120px; object-fit:contain; flex-shrink:0;">
              <div style="display:flex; flex-direction:column; justify-content:flex-start;">
                <h3 style="margin:0;">WAI</h3>
                <p style="margin:5px 0 0 0;">World Arthistory Institute</p>
              </div>
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
