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

- block: custom-aboutme
    content:
      title: "About Me"
      button:
        text: "Go to About Me"
        url: /aboutme/
    design:
      css_class: light
      background:
        color: white
      css_style: |
        .custom-aboutme {
          padding: 2rem;
          text-align: center;
        }
        .custom-aboutme a {
          color: #007bff;
        }
        
---
