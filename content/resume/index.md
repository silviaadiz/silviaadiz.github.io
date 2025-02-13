---
title: ''
type: markdown
reading_time: false
share: false

---

<style>

  /* Timeline Styling */
  .timeline {
    position: relative;
    max-width: 1200px; /* Increased from 900px to 1200px */
    margin: 0 auto;
    padding: 70px 0;
    font-family: 'Roboto', roboto; 
  color: #4a4e69; 
  }

  .timeline::after {
    content: '';
    position: absolute;
    width: 4px;
    background-color: #4a4e69;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -2px;
  }

  .timeline-item {
    padding: 20px 40px; /* Increased padding */
    position: relative;
    width: 50%;
    background: #ffffff;
    border-radius: 8px;
    margin-bottom: 20px; /* Increased margin */
    font-size: 18px; /* Increased font size */
  }

  .timeline-item.left {
    left: 0;
    margin-top: -100px;
  }

  .timeline-item.right {
    left: 50%;
    margin-top: -120px; /* Pull up right-side items to start earlier */
  }

  .timeline-item::after {
    content: '';
    position: absolute;
    width: 16px;
    height: 16px;
    background-color: #4a4e69;
    border: 3px solid #fff;
    border-radius: 50%;
    top: 15px;
    right: -8px;
    z-index: 1;
  }

  .timeline-item.right::after {
    left: -8px;
  }

  .timeline-item .date {
    font-size: 14px; /* Increased font size */
    color: #4a4e69;
    margin-bottom: 8px;
  }

  .timeline-item .title {
    font-size: 20px; /* Increased font size */
    font-weight: bold;
    color: #4a4e69;
    margin-bottom: 8px;
  }

  .timeline-item .summary {
    font-size: 16px; /* Increased font size */
    color: #4a4e69;
  }

  .timeline-item .responsibilities {
    font-size: 16px; /* Increased font size */
    color: #4a4e69;
    margin-top: 8px;
    margin-left: 15px;
  }

  .timeline-item .responsibilities li {
    margin-bottom: 4px;
  }

  /* Skills Section Styling */
  .skills-section {
    margin-top: 40px;
    font-family: 'Roboto', roboto; 
  color: #4a4e69; 
  }

  .skills-section  {
    font-size: 24px;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 20px;
  }

  .skill {
    margin-bottom: 15px;
  }

  .skill-name {
    font-size: 18px; /* Increased font size */
    color: #4a4e69;
    margin-bottom: 5px;
  }

  .skill-level {
    font-size: 16px; /* Increased font size */
    color: #4a4e69;
    margin-bottom: 5px;
  }

  .skill-bar {
    width: 100%;
    height: 8px;
    background-color: #f2e9e4;
    border-radius: 5px;
    overflow: hidden;
  }

  .skill-progress {
    height: 100%;
    background-color: #0d1b2a;
    border-radius: 5px;
  }

  .skill-progress.r { width: 85%; }
  .skill-progress.python { width: 20%; }
  .skill-progress.bash { width: 30%; }

  /* Horizontal Languages Styling */
  .languages-section {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 40px;
    font-family: 'Roboto', roboto; 
  color: #4a4e69; 
  }

  .language {
    margin: 0 20px;
    text-align: center;
  }

  .language-name {
    font-size: 18px; /* Increased font size */
    color: #4a4e69;
  }

  .language-level {
    font-size: 16px; /* Increased font size */
    color: #4a4e69;
  }

  /* Original Courses and Certifications Layout */
  .courses-certifications-section {
    margin-top: 40px;
    font-family: 'Roboto', roboto; 
  color: #4a4e69; 
  }

  .course-certification {
    margin-bottom: 20px;
  }

  .course-certification-name {
    font-size: 18px; /* Increased font size */
    color: #4a4e69;
  }

  .course-certification-details {
    font-size: 16px; /* Increased font size */
    color: #4a4e69;
  }
</style>

<!-- CV Download Section -->
<div style="text-align: center; margin-top: 30px;">
  <a href="uploads/resume.pdf" download style="padding: 10px 20px; background-color: #4a4e69; color: white; text-decoration: none; border-radius: 5px;">
    Download my CV
  </a>
</div>

<!-- Work Experience Timeline -->
<h2>Work Experience</h2>
<div class="timeline">
  <div class="timeline-item left">
    <div class="date">July 2020 - June 2024</div>
    <div class="title">Research Technician</div>
    <div class="summary">Genomic Medicine Lab - Genomics & Bioinformatics</div>
    <ul class="responsibilities">
      <li>Supported the biostatistics and statistical genetics unit.</li>
      <li>Designed and performed analyses for different research projects.</li>
      <li>Implemented and automated R analysis pipelines. </li>
      <li>Mentored PhD students, interns and high school students in R programming and statistics.</li>
      <li>Participated in the elaboration of reports and manuscripts.</li>
    </ul>
  </div>

  <div class="timeline-item right">
    <div class="date">March 2021 - June 2024</div>
    <div class="title">PhD Student</div>
    <div class="summary">Genomic Medicine Lab - Genomics & Bioinformatics</div>
    <ul class="responsibilities">
      <li>Led the main analyses for the SCOURGE consortium in COVID-19 host genetics.</li>
  </div>
    </ul>

  <div class="timeline-item left">
    <div class="date">March 2020 - July 2020</div>
    <div class="title">Intern</div>
    <ul class="responsibilities">
      <li>Assisted in statistical data analysis and data cleansing.</li>
      <li>Learnt and applied research methodologies</li>
    </ul>
  </div>
</div>

<!-- Education Timeline -->
<h2>Education</h2>
<div class="timeline">
  <div class="timeline-item left">
    <div class="date">2021 - 2024</div>
    <div class="title">PhD in Molecular Medicine (Statistical Genetics)</div>
    <div class="summary">Thesis research on the genetic basis of COVID-19 severity.</div>
  </div>

  <div class="timeline-item right">
    <div class="date">2019 - 2021</div>
    <div class="title">MSc in Statistical Techniques</div>
    <div class="summary">Relevant courses: Probability models, mixed models, parametric and non-parametric regression modelling, survival analysis, multivariate analysis, spatial analysis, exploratory data analysis, time series.</div>
  </div>

  <div class="timeline-item left">
    <div class="date">2015 - 2019</div>
    <div class="title">BSc in Biology</div>
  </div>
</div>

<!-- Skills Section -->
<div class="skills-section">
  <h2>Skills</h2>
  <div class="skill">
    <div class="skill-name">R</div>
    <div class="skill-level">Advanced</div>
    <div class="skill-bar">
      <div class="skill-progress r"></div>
    </div>
  </div>
  <div class="skill">
    <div class="skill-name">Python</div>
    <div class="skill-level">Beginner</div>
    <div class="skill-bar">
      <div class="skill-progress python"></div>
    </div>
  </div>
  <div class="skill">
    <div class="skill-name">Bash</div>
    <div class="skill-level">Intermediate</div>
    <div class="skill-bar">
      <div class="skill-progress bash"></div>
    </div>
  </div>
</div>

<!-- Languages Section (Horizontal Layout) -->
<h2>Languages</h2>
<div class="languages-section">
  <div class="language">
    <div class="language-name">English</div>
    <div class="language-level">Fluent-C2</div>
  </div>
  <div class="language">
    <div class="language-name">Spanish</div>
    <div class="language-level">Native</div>
  </div>
  <div class="language">
    <div class="language-name">Galician</div>
    <div class="language-level">Native</div>
  </div>
</div>

<!-- Courses & Certifications Section (Original Layout) -->
<h2>Courses & Certifications</h2>
<div class="courses-certifications-section">
  <div class="course-certification">
    <div class="course-certification-name">A crash course in causality</div>
    <div class="course-certification-details">University of Pensylvannia - Coursera, 2024</div>
  </div>
  <div class="course-certification">
    <div class="course-certification-name">Hands on Clinical Reporting with R</div>
    <div class="course-certification-details">Genentech - Coursera, 2024</div>
  </div>
</div>