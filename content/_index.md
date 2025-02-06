---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block:  resume-biography
    content:
      username: admin
      text: ""
    design:
      background:
        color: white
      size: L
      spacing:
        padding: ["20px", "0", "10px", "0"]  # Reduced padding to reduce spacing


  - block: markdown
    id: aboutme
    weight: 2
    content:
      title: ""
      text: |
        <div style="text-align: center; font-size: 15px;">
          <span style="font-family: 'Arial Black', sans-serif; font-size: 38px; color: #4a4e69;">Hi, I'm Silvia!</span>
          <br><br>
          You can know more about me <a href="aboutme/" style="color: #4a4e69; text-decoration: underline;">here</a>, and you can also give a look to my <a href="resume/" style="color: #4a4e69; text-decoration: underline;">CV</a>, <a href="publications/" style="color: #4a4e69; text-decoration: underline;">publications</a>, and <a href="projects/" style="color: #4a4e69; text-decoration: underline;">projects</a>.
        </div>

  - block: markdown
    content:
      title: ""
      text: |
        <div style="text-align: center; margin-top: 10px;">  <!-- Reduced margin-top -->
          <!-- Social Media Icons -->
          <a href="https://twitter.com/yourusername" target="_blank" style="margin: 0 10px; font-size: 24px; color: #1DA1F2;"><i class="fab fa-twitter"></i></a>
          <a href="https://linkedin.com/in/yourusername" target="_blank" style="margin: 0 10px; font-size: 24px; color: #0077B5;"><i class="fab fa-linkedin"></i></a>
          <a href="https://github.com/yourusername" target="_blank" style="margin: 0 10px; font-size: 24px; color: #333;"><i class="fab fa-github"></i></a>
          <a href="https://instagram.com/yourusername" target="_blank" style="margin: 0 10px; font-size: 24px; color: #E1306C;"><i class="fab fa-instagram"></i></a>

          <!-- Download CV Button -->
          <br>  <!-- Line break to place the button below the icons -->
          <a href="uploads/resume.pdf" download style="margin-top: 3px; font-size: 16px; padding: 10px 20px; background-color: #4a4e69; color: white; text-decoration: none; border-radius: 5px;">
            Download My CV
          </a>
        </div>
    design:
      background:
        color: white
      spacing:
        padding: ["0px", "0", "10px", "0"]  
        

---