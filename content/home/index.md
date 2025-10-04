---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      text: |
        <style>
          /* 内联 CSS：自定义背景图片、文字样式等 */
          .custom-background {
            position: relative; /* 让文字可以覆盖在背景图片上 */
            text-align: center; /* 让标题和正文居中 */
            padding-top: 20%; /* 让标题在纵向1/3的位置开始显示 */
            padding-bottom: 50px; /* 给底部留点空间 */
            color: white; /* 确保文字颜色与背景对比 */
            background-image: url('static/images/front-bg-00.png');
            background-size: cover; /* 背景图片完全覆盖，保证完整显示 */
            background-position: center center; /* 保证图片居中 */
            height: 100vh; /* 使背景图片占满整个视窗高度 */
            background-attachment: fixed; /* 背景固定，不随滚动条滚动 */
          }

          /* 标题的样式 */
          .custom-title {
            font-size: 128px; /* 调整字体大小 */
            font-weight: bold; /* 可选：使标题加粗 */
            color: rgba(255, 255, 255, 1); /* 半透明白色 */
            /* text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6); /* 文字阴影，提高可读性 */
          }

          /* 副标题的样式 */
          .custom-subtitle {
            font-size: 24px; /* 调整副标题的字体大小 */
            font-weight: normal; /* 副标题保持正常字体 */
            color: rgba(255, 255, 255, 1); /* 半透明白色 */
            margin-top: 10px;
          }

          /* 正文的样式 */
          .custom-text {
            font-size: 18px; /* 正文的字体大小 */
            color: rgba(255, 255, 255, 0.9); /* 增加对比度 */
            margin-top: 20px;
            line-height: 1.6; /* 增加行高，改善可读性 */
          }
        </style>

        <div class="custom-background">
          <h1 class="custom-title">NIL</h1>
          <h2 class="custom-subtitle">Neurocognitive Image Lab</h2>
          <br>
          <br>
          <br>
          <p class="custom-text">NIL aims to set up an international and interdisciplinary lab, exploring the anthropological universals and cultural specifics of Image perception, neuroaesthetics, dynamic information processing, temporal and spatial processes to unlock the mysteries of how we experience the world .....</p>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
      background:
        image:
          filename: front-bg-00.png
          position: center
          size: cover
        color: '#333'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
