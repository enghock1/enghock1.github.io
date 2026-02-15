---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="margin-bottom: 3em;"></div>

Education
======
* Ph.D in Electrical Engineering, University of Minnesota - Twin Cities, 2024  
  * Minor in Computer Science
* B.S. in Physics, University of Minnesota - Twin Cities, 2016

<div style="margin-bottom: 3em;"></div>

Skills
======
* Core Skills
  * Machine Learning, Deep Learning, Contrastive Learning, Scientific Machine Learning (Physics/Biology-Informed), Computer Vision, Anomaly Detection, Optimization, Density Functional Theory (DFT), Exploratory Data Analysis, Design of Experiments, MLOps, Signal Processing
* Software
  * Python (PyTorch, Scikit-Learn, Numpy, Pandas, Scipy, Matplotlib, Seaborn, Pymatgen), MatLab, Git/Github, LaTeX, Datalad, Docker, Bash/Unix, Google Cloud Platform (Vertex AI)
* Hardware
  * Fourier Transform Infrared Spectroscopy (FTIR)

<div style="margin-bottom: 3em;"></div>

Work experience
======
* <span style="font-size: 1.1em;"><b>Machine Learning Engineer</b></span>  
  *Oncodea*, October 2024 - Current
  * Develop AI-driven diagnostic solutions to make early-stage cancer screening accessible to the masses.  
<br>
* <span style="font-size: 1.1em;"><b>Research Assistant</b></span>  
  *University of Minnesota - Twin Cities*, April 2015 - November 2024
    * Introduced a Learning Using Privileged Information (LUPI) framework for materials property prediction, achieving a 32.5% accuracy improvement over standard supervised methods.
    * Developed a machine learning-guided framework that iteratively refine the physics equations of band alignment in vdW heterostructures, boosting predictive accuracy on test materials from 30% to 90%.
    * Performed analysis using unsupervised learning techniques on a large, noisy materials database to extract hidden insights, and leveraged these discoveries to enhance materials properties predictions accuracy by 38%.
    * Formulated a theoretical framework based on Statistical Learning Theory to explain the double descent phenomenon, providing theoretical insights on model complexity in both under- and over-parameterized regimes.
    * Developed a biologically-constrained deep learning model that improves robustness to occlusion, resulting in a 32% decrease in 3D pose error when estimating 3D hand pose from 2D images. 
    * Investigated analytical reasoning capabilities of Large Language Models (LLMs) through prompt engineering and proposed strategies for integrating LLM tools into mathematics and machine learning education.
    * Facilitated interdisciplinary technical collaboration between machine learning and materials science experts across multiple research projects.  
<br>
* <span style="font-size: 1.1em;"><b>Research Intern</b></span>  
  *Astrin Biosciences*, May 2023 - August 2023
    * Optimized a deep learning-based real-time cancer cell detection model from holographic images by incorporating physics constraints based on cell morphology and optics, achieving a 10x improvement in specificity while maintaining high sensitivity.
    * Designed experiments to uncover crucial cell features and integrated these new insights to enhance the deep learning model.
    * Developed and deployed a deep learning model for autofocus in holographic cameras, significantly enhancing cell image resolution and removing the need for manual tuning, thereby increasing experiment workflow efficiency by 30%.  
<br>
* <span style="font-size: 1.1em;"><b>Research Intern</b></span>  
  *Taiwan Semiconductor Manufacturing Company (TSMC)*, June 2020 - September 2020
    *  Secured a patent and trade secrets for inventing computational techniques that enhance multilayer mirror reflectivity in EUV lithography, potentially doubling manufacturing yield.

<div style="margin-bottom: 3em;"></div>

Fellowships and Awards
======
* Data Science Initiative (DSI) Fellowship Award, 2023-2024
* Best Poster Award, Midwest Machine Learning Symposium (MMLS), 2024 
* Dean's List, UMN College of Science and Engineering, 2015-2016

<div style="margin-bottom: 3em;"></div>

Service and Outreach
======
* <b>Technical Committee</b>, Nanophotonics of 2D Materials Conference, 2020
* <b>Editor</b>, 2D Materials: Properties and Devices Textbook, 2017

<div style="margin-bottom: 3em;"></div>

Journal Publications
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'manuscripts' %}
    <p>{{ post.citation }}</p>
    {% endif %}
  {% endfor %}</ul>
  
<div style="margin-bottom: 3em;"></div>

Book Chapters
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'book_chapters' %}
    <p>{{ post.citation }}</p>
    {% endif %}
  {% endfor %}</ul>
  
<div style="margin-bottom: 3em;"></div>

Patents
======
  <ul>{% for post in site.publications reversed %}
    {% if post.category == 'patents' %}
    <p>{{ post.citation }}</p>
    {% endif %}
  {% endfor %}</ul>

<div style="margin-bottom: 3em;"></div>

Posters
======
<ul>{% for post in site.publications reversed %}
    {% if post.category == 'posters' %}
    <p>{{ post.citation }}</p>
    {% endif %}
  {% endfor %}</ul>

<div style="margin-bottom: 3em;"></div>

Teaching Assistant
======
  <ul>{% for post in site.teaching reversed %}
    <p style="display: flex; justify-content: space-between;">
      <span>{{ post.title }}</span>
      <span>{% if post.years %}{{ post.years }}{% else %}{{ post.date | date: "%Y" }}{% endif %}</span>
    </p>
  {% endfor %}</ul>
