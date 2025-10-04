---
title: Team
date: 2025-10-03
type: landing
show_recent_posts: false    # 设置为 false 可隐藏最新文章摘要

sections:
  # ===== director's card =====      
  - block: people
    content:
      title: "Directors"
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
  # ===== researcher's card =====      
  - block: people
    content:
      title: "Researchers"
      user_groups:
        - Researchers
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false    # 不显示兴趣标签
      show_role: true          # 显示职位/角色
      show_social: true        # 显示社交媒体图标
      card_style: standard     # 使用主题默认卡片样式
      columns: 2   
  # ===== Visitors's card =====      
  - block: people
    content:
      title: "Visitors"
      user_groups:
        - Visitors
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false    # 不显示兴趣标签
      show_role: true          # 显示职位/角色
      show_social: true        # 显示社交媒体图标
      card_style: standard     # 使用主题默认卡片样式
      columns: 2     
  # ===== Students's card =====      
  - block: people
    content:
      title: "Students"
      user_groups:
        - Students
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false    # 不显示兴趣标签
      show_role: true          # 显示职位/角色
      show_social: true        # 显示社交媒体图标
      card_style: standard     # 使用主题默认卡片样式
      columns: 2           
  - block: markdown
    content:
      title: "Join Our Team"
      text: |
            We are actively seeking outstanding candidates for the following positions:
            
            - **Faculty Position** (Assistant/Associate Professor)  
              in Cognitive Neuroscience, Computational Perception, or Neuroaesthetics.  
              Candidates should have a PhD, a strong publication record, and potential for independent research.

            - **Postdoctoral Researcher**  
              to work on projects involving fMRI/EEG, computational modeling, or cross-cultural aesthetic experiments.  
              Applicants should have recently completed a PhD and experience in neuroimaging or behavioral research.

            We offer competitive salaries, research support, and a collaborative, interdisciplinary environment.

            > **To apply**, please send your CV, research statement, and contact information for three references to **nil-hr@university.edu**  
            > with subject line: `[Position] - Your Name - Institution`.
    design:
      columns: 1

---
