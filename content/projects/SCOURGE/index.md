---
title: SCOURGE project
reading_time: false
share: false
---

<span style="font-family: 'Roboto', sans-serif; font-size: 16px; text-align: justify;">

The SCOURGE Consortium was established as a collaboration between Spain and some countries in Latin-America, aimed to find genetic variants associated with COVID-19 infection and severity. It was a major effort that went on for 4 years, with two main research lines and several sub-projects, that was also part of the COVID-19 Host Genetics Initiative (HGI Consortium). I joined this project as a research technician while finishing my MSc, and then developed a PhD thesis based on it. 

The two main investigations focused on [Spanish]({{< ref "publication/cruz-2022/index.md" >}}) and [Latin-American]({{< ref "publication/diz-de-almeida-2024/index.md" >}}) patients, sharing first authorship with Dr. Cruz in both of them ([Github of the project](https://github.com/CIBERER/Scourge-COVID19).

### Spanish cohort study
In the first part of the research, we recruited over ~12.000 patients infected with the virus around 25 cities in Spain, obtaining their clinical information (comorbidities, COVID-19 outcomes, complications...) and genetic information. Then, we conducted a genome-wide association study (GWAS), which sweeps the entire genome in search of variants associated with the tested phenotype (case/control study). One of the **key findings** was a positive association between a variant in the gene codifying for the Aquaporin 3 (_AQP3_) and hospitalization due to COVID, suggesting a potential therapeutic target for the disease. We also conducted sex-stratified analyses, which revealed an absence of genetic associations in females, likely driven by lower effect sizes. In fact, after meta-analyzing several studies, the widely replicated signal in chromosome 3 emerged in this group. Lastly, we built a genetic risk score using the main associated variants and fit a multinomial regression for a COVID-19 severity scale, obtaining a significant differentiation (in terms of genetic risk) between classes asymptomatic/mild, moderate+severe disease, and critical disease.

### Latin-American cohort study
We recruited more data in collaboration with Brazil, Colombia, Ecuador, Mexico and Paraguay. Then, we retrieved the patients recruited in Spain with a strong evidence of origin in Latin-America, resulting in over ~3.500 patients and conforming the largest Latin-American cohort to study the genetics of the disease. A meta-analysis was conducted with all data available from other studies. **Two interesting associations** emerged, one within the gene _DDIAS_, which was mostly absent in other population groups, and another one within the gene _BAZ2B_. Following our previous research, we built a genetic score with the variants associated with COVID-19 severity and tested its performance in this novel cohort.


### Polygenic scores

In the final phase of my PhD thesis, I focused on constructing more sophisticated polygenic risk scores (PRS) and evaluating their performance and clinical utility across two distinct cohorts. I developed a total of 130 unique polygenic risk scores for each cohort, leveraging various combinations of genetic data, and identified the top-performing models based on their improvement in pseudo-R2 values. Contrary to what's tipically observed when applying polygenic risk scores to diverse population groups, the COVID-19 PRS showed similar performance in both cohorts, highlighting its potential generalizability.

Following this finding, I imagined a clinical scenario where an individual wanted to understand their position within the genetic risk distribution for COVID-19. To address this, I developed a single PRS and evaluated three distinct training models for risk prediction, using a new cohort of Spanish individuals as the test set. The three approaches included: (1) training the PRS regression model exclusively on the Spanish cohort, (2) training it on the entire combined cohort, and (3) a novel approach where the training cohort was selected based on the Euclidean distance between the principal genetic components (PCs) of the test set and those of the training set (best-fit model). 

Lastly, I explored the behaviour of the genetic score in relation to key clinical variables, such as age, sex, and relevant comorbidities, and its association with other COVID-19-related complications. I also assessed the utility of incorporating the score into a prediction model for COVID-19 hospitalization, particularly when pre-existing comorbidities were included, by utilizing decision curve analysis (DCA) and net reclassification improvement (NRI) metrics.

This research was not published beyond my thesis dissertation, but [here](/uploads/Slides_PRS_SILVIADIZ_IDIS.pdf) you can download the slides for a presentation I gave at the Health Research Institute of Santiago de Compostela (IDIS) (research was not finished yet).