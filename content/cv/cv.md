---
type: landing
title: "Curriculum Vitae"
date: "2025-02-04"
layout: "landing"
---

<style>
  /* Estilos para la cuadrícula de habilidades */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    gap: 20px;
    text-align: center;
  }
  .skills-grid img {
    width: 50px;
    height: 50px;
  }
  /* Estilos para secciones colapsables */
  .collapsible {
    cursor: pointer;
    padding: 10px;
    border: none;
    text-align: left;
    outline: none;
    font-size: 1.2em;
    background-color: #f9f9f9;
    margin-top: 10px;
  }
  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
  }
</style>

## Education

<button class="collapsible">PhD in Molecular Medicine (Statistical genetics)</button>
<div class="content">
  <p><strong>Universidad de Santiago de Compostela</strong><br>
  2021 – 2024</p>
</div>

<button class="collapsible">MSc in Statistical Techniques</button>
<div class="content">
  <p><strong>Universidad de Santiago de Compostela</strong><br>
  2019 – 2021</p>
  <p><strong>Relevant courses taken:</strong> Parametric regression modelling, mixed models, non-parametric regression modelling, survival analysis, multivariate analysis, time series, spatial analyisis, probability models, inference, exploratory data analysis. </p>
</div>

<button class="collapsible">BSc in Biology</button>
<div class="content">
  <p><strong>Universidad de Santiago de Compostela</strong><br>
  2015 – 2019</p>
</div>

## Experience

<button class="collapsible">Research technician</button>
<div class="content">
  <p><strong>Center for Research in Molecular Medicine and Chronic Diseases </strong><br>
  2020 – 2024</p>
  <ul>
    <li>Desarrollo de modelos estadísticos para el análisis de datos genómicos.</li>
    <li>Colaboración con equipos multidisciplinarios en proyectos de investigación.</li>
    <li>Publicación de resultados en revistas científicas de alto impacto.</li>
  </ul>
</div>
<button class="collapsible">PhD student</button>
<div class="content">
  <p><strong>Center for Research in Molecular Medicine and Chronic Diseases </strong><br>
  2021 – 2024</p>
  <ul>
    <li>Desarrollo de modelos estadísticos para el análisis de datos genómicos.</li>
    <li>Colaboración con equipos multidisciplinarios en proyectos de investigación.</li>
    <li>Publicación de resultados en revistas científicas de alto impacto.</li>
  </ul>
</div>
<button class="collapsible">Intern</button>
<div class="content">
  <p><strong>Center for Research in Molecular Medicine and Chronic Diseases </strong><br>
  2020 – 2020</p>
  <ul>
    <li>Desarrollo de modelos estadísticos para el análisis de datos genómicos.</li>
    <li>Colaboración con equipos multidisciplinarios en proyectos de investigación.</li>
    <li>Publicación de resultados en revistas científicas de alto impacto.</li>
  </ul>
</div>

## 🛠️ Habilidades

  </div>
  <div>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/r/r-original.svg" alt="R">
    <p>R</p>
    <p><strong>Advanced</strong></p>

<div class="skills-grid">
  <div>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux">
    <p>Linux</p>
    <p><strong>Intermediate</strong></p>

  </div>
  <div>
    <img src="https://raw.githubusercontent.com/rstudio/hex-stickers/master/PNG/rmarkdown.png" alt="RMarkdown">
    <p>RMarkdown</p>
    <p><strong>Begginer</strong></p>

  </div>
  <div>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
    <p>Python</p>
    <p><strong>Begginer</strong></p>

  </div>
</div>

## 📚 Cursos

<button class="collapsible">Análisis de Datos Genéticos</button>
<div class="content">
  <p><strong>Instituto de Genética Aplicada</strong><br>
  2023</p>
</div>

<button class="collapsible">Machine Learning Aplicado</button>
<div class="content">
  <p><strong>Universidad de la Ciencia de Datos</strong><br>
  2022</p>
</div>

## 🎤 Charlas

<button class="collapsible">"Innovaciones en Genómica Computacional"</button>
<div class="content">
  <p><strong>Conferencia Internacional de Genética</strong><br>
  2024</p>
</div>

<button class="collapsible">"Aplicaciones de Machine Learning en Biología"</button>
<div class="content">
  <p><strong>Simposio de Bioinformática</strong><br>
  2023</p>
</div>

## 🌍 Idiomas

- Español (Nativo)
- Inglés (Avanzado - C1)
- Francés (Intermedio - B2)

<script>
  // Script para secciones colapsables
  var coll = document.getElementsByClassName("collapsible");
  for (var i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var content = this.nextElementSibling;
      if (content.style.display === "block") {
        content.style.display = "none";
      } else {
        content.style.display = "block";
      }
    });
  }
</script>