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
* Ph.D in Bioinformatics, WEHI, The University of Melbourne, 2020-2024
* M.S. in Bioinformatics, Shanghai Jiao Tong University, 2015-2018
* B.S. in Bioinformatics, Huazhong University of Science and Technology, 2011-2015

Work Experience
======
* 2019.07-2020.05: Intern
  * CAS-MPG Partner Institute for Computational Biology, Shanghai, China
  * Duties includes: Analyzing WGS and RNA-seq data of pancreatic cancer
  * Supervisor and collaborators: Dr Liyun Yuan, Prof Guoqing Zhang and Prof [Wu Wei](https://scholar.google.com/citations?hl=en&user=HaPNtVAAAAAJ).  

* 2018.08-2019.05: Scientific Visitor
  * European Molecular Biology Laboratory, Heidelberg, Germany
  * Duties includes: Exploring factors influencing editing efficiency of CRISPR-Cas9 sgRNA
  * Supervisor and collaborators: Prof [Lars Steinmetz](https://scholar.google.com/citations?user=mP_NR74AAAAJ&hl=en), Dr Shengdi Li, Dr [Sibylle Vonesch](https://scholar.google.de/citations?user=zY8I5PcAAAAJ&hl=en)

  
Skills
======
* Bioinformatics
* Gene Expression
* Single Cell Sequencing
* DNA Methylation
* Shell, R and Rmarkdown

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  