---
title: "Contact"
date: 2025-10-02
type: landing

sections:
  # ===== 顶部实验室照片 =====
  - block: markdown
    content:
      title: ""
      subtitle: ""
      text: |
        ![Neurocognitive Image Lab](/images/lab-outside.jpg)
    design:
      columns: "1"
      background:
        color: "#ffffff"
      spacing:
        padding: ["0", "0", "20px", "0"]

  # ===== 联系方式 =====
  - block: contact
    content:
      title: "Get in Touch"
      text: |
        For general inquiries or collaboration opportunities, please feel free to reach out to us.

        **Administrative Office – Neurocognitive Image Lab (NIL)**  
        Shanghai International Studies University (SISU)

      email: "NIL <nil@shisu.edu.cn>"
      address:
        street: 1550 Wenxiang Road, Building 27
        city: Shanghai
        region: Songjiang
        postcode: '201600'
        country: China
        country_code: CN
      autolink: true
      form:
        provider: netlify
        netlify:
          captcha: false
    design:
      columns: "1"

  # ===== 校园地图 =====
  - block: markdown
    content:
      title: "Campus Map"
      subtitle: ""
      text: |
        ![Campus Map](/images/campus-map.png)
    design:
      columns: "1"
      background:
        color: "#f8f9fa"
      spacing:
        padding: ["20px", "0", "20px", "0"]
---