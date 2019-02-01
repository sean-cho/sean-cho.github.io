---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a PDF version of my resume [here](/files/SCho_Resume.pdf).

Education
======
* B.Sc. in Biotechnology, California State Polytechnic University, Pomona (2008)
* Ph.D. in Cellular and Molecular Medicine, Johns Hopkins University School of Medicine (2016)

Skills
======
* Programming
  * R & Shiny; Python; Bash
  * SQL; Git & Github
  * CWL; Snakemake
* Platforms
  * Sun Grid Engine; Slurm; Docker
  * Amazon Web Services; Seven Bridges Genomics
* Data analysis
  * Biostatistics; microarray & NGS;
  * Genomics, epigenomics, transcriptomics
  * Machine learning

Professional experience
======
* Post-doctoral Fellow (Dec 2016 - Current)
  * Kennedy Krieger Institute & Johns Hopkins University
  * PI: Dr. Jonathan Pevsner
  * Characterization of somatic mosaicism in neurobehavioral disorders
    * Analyzed NGS (genomic, transcriptomic, 10X Genomics) datasets to identify somatic variants associated with disease
    * Designed phase-aware computational methods for somatic variant discovery and prioritization that led to increased specificity in variant calling.
    * Developed and maintained Dockerfiles and bioinformatics pipelines for high performance cluster or cloud computing to enable efficient genomic analysis and promote reproducibility.
    * Generated a 14TB public resource of genomic variant call format (GVCF) files from 1000 Genomes to increase variant calling sensitivity using the Seven Bridges Genomics cloud computing platform.

* PhD Candidate (Sep 2010 - Nov 2016)
  * Johns Hopkins University School of Medicine
  * PIs: Drs. Saraswati Sukumar, Christopher Umbricht, Leslie Cope
  * Multi-omics analysis of archival tissue for biomarker discovery in breast and thyroid cancer
    * Designed statistical framework & computational tools for integrative genomic & epigenomic analysis.
    * Developed the Epicopy program for estimating copy number variation from methylation microarrays, effectively increasing the amount of data obtained from methylation microarray experiments.
    * Optimized protocols for DNA/RNA extraction from archival tissue and microarray analysis leading to greater yield and microarray quality.
    * Actively collaborated on interdisciplinary teams to make decisions and discoveries for grants and research projects, resulting in thirteen publications.
    * Led the development of bioinformatics research strategy, generated pilot data, and successfully co-wrote two competitively funded grants totaling $300,000.

* Graduate Intern, Computational Biology (Aug  2015 - Oct 2015)
  * Pfizer
  * Multi-omics analysis of breast cancer
    * Led the analysis of genomic and transcriptomic data of a unique breast cancer cohort, resulting in a peer-reviewed publication in Nature Communications.

* Research Associate (June 2008 - May 2010)
  * City of Hope National Cancer Center
  * PI: Dr. Michael Jensen
  * Immuno-oncology research in chimeric antigen receptor (CAR) T-cells
    * Designed and constructed lentiviral vectors of CARs for T-cell therapy research as an active member of a translational research team.

* Undergraduate Researcher (Oct 2007 - June 2008)
  * California State Polytechnic University, Pomona
  * PI: Dr. Weijen Lin
  * Development of a transposon system for gene delivery in Gram-positive bacteria
    * Modified and optimized the use of transposon Tn5 for large gene delivery through electroporation.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks & Posters
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Journal reviewer:
  * Cancer Epidemiology, Biomarkers and Prevention
  * Cancer Research
  * Clinical Cancer Research
  * Frontiers in Oncology
  * Molecular Cancer Research
  * Molecular Carcinogenesis
  * Oncogene
