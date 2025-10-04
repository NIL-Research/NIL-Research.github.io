---
title: Directors' Remark
date: 2025-10-03
type: landing
show_recent_posts: false    # 设置为 false 可隐藏最新文章摘要

sections:
  # ===== remark text =====
  - block: markdown
    content:
      title: Directors' Remark
      text: |
         At the **Neurocognitive Image Lab (NIL)**, our mission is to bridge neuroscience, 
         psychology, philosophy, and the arts. We aim to explore the neural foundations of image 
         perception, neuroaesthetics, and the temporal and spatial dynamics of cognition.
    
         Our rationale is rooted in an interdisciplinary vision: combining cognitive neuroscience, 
         philosophy, and artistic practice, we study how the brain shapes human experience of images, 
         beauty, and time.
    
         NIL is founded with the belief that science and humanities must converge to fully capture 
         the richness of human cognition. We invite scholars, artists, and students alike to 
         contribute to this journey.
      form:
        provider: netlify
        netlify:
          captcha: false
    design:
      columns: "1"

  # ===== director's card =====      
  - block: people
    content:
      title: 
      user_groups:
        - Directors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false    # 不显示兴趣标签
      show_role: true          # 显示职位/角色
      show_social: true        # 显示社交媒体图标
      card_style: standard     # 使用主题默认卡片样式
      columns: 2             

---
