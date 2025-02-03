---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
      css_style: |
        .avatar {
          filter: grayscale(100%);
        }
        body {
          color: #808080;
        }
        a {
          color: #808080;
        }
  

  # Bloque nuevo para About Me
  - block: page
    content:
      page: About Me
    design:
      css_class: light
      background:
        color: white
      css_style: |
        h2 {
          font-size: 2rem;
          color: #333333;
        }
        p {
          font-size: 1.2rem;
          color: #666666;
        }
---
