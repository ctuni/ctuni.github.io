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
* **Ph.D in Biomedicine**, Universitat Pompeu Fabra (UPF), expected October 2026
* **M.S. in Bioinformatics & Omics Data Analysis**, Universitat de Barcelona–Universitat de Vic (UB-UVIC-UCC), 2020
* **B.S. in Biotechnology**, Universitat Autònoma de Barcelona (UAB), 2019

Relevant work experience
======
* **February 2021–Present: Bioinformatics Scientist**
  * Flomics Biotech S.L.

  *Stratus Platform Development & Customer Engagement*
  * Led the end-to-end development and maintenance of [Stratus](https://stratus.flomics.com), a customer-facing bioinformatics platform used to submit, monitor, and retrieve NGS analysis results.
  * Served as the primary technical contact for customers: gathered requirements, translated user needs into platform features, and iterated on solutions across front-end (UI/UX), back-end (API, data management), and the underlying Nextflow pipeline layer.
  * Troubleshot and resolved technical issues spanning infrastructure, pipeline execution, and output interpretation.
  * Produced and maintained user-facing and internal technical documentation.

  *Nextflow Pipeline Development & Infrastructure*
  * Designed, implemented, validated, and maintained reproducible Nextflow analysis pipelines for cloud-based (AWS) and HPC (SLURM) execution; active contributor to nf-core pipelines (`rnaseq`, `scrnaseq`, `sarek`, `rnafusion`, `viralrecon`, `ampliseq`, `seqinspector`).
  * Analysed large-scale NGS datasets including RNA-Seq alignment (STAR), differential expression (DESeq2), and QC workflows (samtools, FastQC, MultiQC).
  * Managed cloud bioinformatics infrastructure and coordinated multi-cohort data management.
  * Trained and mentored new pipeline developers; collaborated with Guigó's Lab (CRG) and cross-functional internal teams.

  *Machine Learning & Data Science*
  * Applied supervised and unsupervised machine learning algorithms (R and Python) for biomarker discovery and diagnostic model development on large multi-cohort biomedical datasets.
  * [Industrial Ph.D.](https://doctoratsindustrials.gencat.cat/en/) project: *"Systematic Evaluation of Plasma Cell-Free RNA Sequencing and Analysis Workflows"* (UPF, expected October 2026).

* **November 2024: Lecturer**
  * Universitat Pompeu Fabra
  * Taught the Chemistry Laboratory module for the Medicine Bachelor's Degree at UPF.

* **October 2019–February 2021: Manager and instructor**
  * Codelearn Eixample Dret
  * Managed the centre (enrolments, communication with parents, scheduling) and taught programming and robotics to students aged 7–18.

* **April 2020–September 2020: Master's Thesis Internship**
  * IRB; Ribas Lab
  * Contributed to the development of `tRNAstudio`, a bioinformatics pipeline for tRNA analysis from deep sequencing data (see Publications).

* **October 2018–June 2019: Final Degree Thesis Internship**
  * IMIM; MARgenomics
  * Benchmarked RNA-seq alignment tools and established optimal parameters for ongoing genomic research.

Skills
======
* **Workflow development:** Nextflow (custom and nf-core pipelines); pipeline design, testing, validation, and maintenance for cloud and HPC environments.
* **Programming:** R (statistical analysis, ML, visualisation: `ggplot2`, `plotly`); Python (`pandas`, `matplotlib`, `scikit-learn`); Bash/Perl scripting; HTML, CSS, JavaScript.
* **Infrastructure & DevOps:** AWS, Docker, Singularity, Conda, Git/GitHub, Linux CLI; SLURM (HPC) and cloud batch systems.
* **Bioinformatics tools:** STAR, DESeq2, samtools, MACS2, FastQC, MultiQC, Picard, Bowtie2.
* **Omics data analysis:** Transcriptomics (bulk RNA-Seq, cell-free RNA), metagenomics, genomics.
* **Machine learning & statistics:** Supervised/unsupervised algorithms for biomarker discovery and diagnostic modelling; applied statistics for life sciences.
* **Communication & documentation:** Experienced at explaining technical concepts to both scientific and non-technical audiences.

Languages
======
* **English:** C1 — Cambridge English: Advanced (CAE)
* **Catalan:** native
* **Spanish:** native

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching & Mentoring
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* [Nextflow Ambassador](https://www.nextflow.io/ambassadors.html): official ambassador for the Nextflow community and ecosystem.
* Active contributor to `nf-core` pipelines: `rnaseq`, `scrnaseq`, `sarek`, `rnafusion`, `viralrecon`, `ampliseq`, `seqinspector`, `differentialabundance`.
* nf-core Mentor (CZI Mentorship Programme, Round 3).
* Safety officer for `nf-core` Hackathons and member of the nf-core Outreach team since 2021.