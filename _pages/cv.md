---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **PhD in Computer Science** - University of Bern, 2017-present  
  **_Topics:_** Analysis and design of self-supervised learning methods  
  Advisor: Prof. Paolo Favaro

* **MSc in Computer Science** - University of Bern, 2017  
  With specialization in Advanced Information Processing – *summa cum laude*  
  **_Thesis Title:_** From Cartoons to Real Images: An Approach to Unsupervised Visual Representation Learning
  
* **BSc in Computer Science** - University of Bern, 2015  
  With minors in Mathematics (60 ECTS) and Physics (30 ECTS) – *magna cum laude*  
  **_Thesis Title:_** A Study of 3D Deformable Parts Models for Detection and Pose-Estimation

## Professional Experience

* **Junior Data Analyst** - Philip Morris International, 2016  
  Development of a Matlab tool for the automatic analysis of ciliary beating videos. The tool extracts key features such as tissue activity and main beating frequency with higher accuracy than prior methods.

* **Software Engineering Intern** - AdNovum, 2015  
  I worked on a mobile payment app, implementing several parts of the iOS version in Objective-C.
  
## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Awards

* **Joint Alumni Association in Computer Science (JAACS):**  
  Award for the best Master Thesis in Computer Science (2017)
  
* **P.A.I.S.S. Best Poster Award:**  
  Award for the poster on "Self-Supervised Feature Learning by Learning to Spot Artifacts" (2018)
 
* **Paper Reviewing Recognitions:**  
  CVPR, outstanding reviewer (2019)<br/>
  ECCV, top reviewer (2020)
  
## Skills

* **Programming Languages:**  
  Python, MATLAB/Octave, Java, Objective-C, LaTeX
  
* **Frameworks:**  
  Tensorflow, PyTorch, Caffe, SciPy, Numpy, OpenCV
  
* **Languages:**  
  German (native), English (fluent), French

## Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
