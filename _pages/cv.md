---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.S. in Biotechnology**, Universitat Autonòma de Barcelona (UAB), 2019
* **M.S. in Omics Data Analysis**, Universitat de Barcelona-Universitat de Vic (UB-UVIC-UCC), 2020
* **Ph.D in Biomedicine**, Universitat Pompeu Fabra (UPF), 2025 (expected)

Relevant work experience
======
* **February 2021-Present: Bioinformatics Scientist**
  * Flomics Biotech S.L.
  * Duties include: Data analysis, pipeline development, use of machine learning algorithms, bioinformatics platform management, training new pipeline developers.
  * Carrying out my [Industrial Ph.D](https://doctoratsindustrials.gencat.cat/en/) project, with the title: "Early detection of colorectal cancer with an RNA-Seq-based liquid biopsy test".

* **October 2019-February 2021: Manager and instructor**
  * Codelearn Eixample Dret
  * Duties included: Managing the center (enrollments, communication with parents, scheduling, etc) and teaching.

* **April 2020-September 2020: Master's Thesis Internship**
  * IRB; Ribas Lab
  * Participated in an ongoing project developing `tRNAstudio` (more info in "Publications")
  * Thesis title: "Development of an tRNA analysis pipeline."
  
* **October 2018-June 2019: Final Degree Thesis Internship**
  * IMIM; MARgenomics
  * Carried on benchmarking of several RNA-seq aligners and found optimal parameters for the work that was being done.
  * Thesis title: "Genomic data analysis and its implications on biology and biotechnology: Benchmarking of RNA-seq alignment tools."

Skills
======
* Knowledgeable in the following languages:
  * R: data analysis, machine learning algorithms, and appealing interactive visualizations with packages such as `DT`, `plotly`, `ggplot` and `htmldashboard`.
  * Phython: data analysis, machine learning algorithms, and visualization with packages such as `pandas` and `matplotlib`.
  * Nextflow: creation of DSL2 analysis pipelines, with special interest in reproducibility and user-friendliness.
  * Perl, Bash, and COBOL scripting.
  * HTML, CSS, and Javascript for web and markdown design.
* Omic-data analysis, specially:
  * Transcriptomics
  * Metagenomics
  * Genomics
  * General and applied statistics to biological and life sciences.
* Machine Learning:
  * Knowledgeable in supervised and unsupervised machine learning algorithms applied to life sciences in general, and biomarker discovery in particular.
* AWS
* Docker, Singularity, Conda, Git, CLI, and other helper tools for Bioinformatics
* Aside from hard skills, I consider myself someone eager to learn, solve problems, and overcome obstacles by finding creative and inventive solutions while being a team-player.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul> -->
  

Teaching & Mentoring
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Active member of `nf-core` and `Nextflow` projects and Slack spaces, contributing to `viralrecon`, `rnaseq`, `ampliseq`, and `differentialabundance` pipelines.
* Safety officer for `nf-core` Hackathons and member of the nf-core's Outreach team since 2021. 