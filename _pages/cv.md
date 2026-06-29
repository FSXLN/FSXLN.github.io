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
* Ph.D. Student in Computer Science and Technology, Zhejiang University. 2024 - Present
* B.Eng. in Software Engineering, Chongqing University. 2020 – 2024

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Honors and Awards
======
* Finalist Award, Mathematical Contest in Modeling (MCM) (2023)
* National Excellence Award, Lanqiao Cup National Software and Information Technology Professionals Competition, C/C++ Programming, University Group A (2023)
* Chongqing Municipal First Prize, Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM) (2022)
* Provincial Second Prize, Lanqiao Cup National Software and Information Technology Professionals Competition, Java Programming, University Group A (2022)
* Semifinalist, National Undergraduate Software Innovation Competition (2023)
* Campus-Level Silver Award, China International College Students' "Internet+" Innovation and Entrepreneurship Competition (2022)
* Computer Software Copyright Registration, Tizhai (2022)
* Outstanding Student, Chongqing University (2022)
* Comprehensive Scholarship for Outstanding Students, Chongqing University

Projects
======
* Chongqing Municipal Undergraduate Innovation Training Project: Container Load Prediction Based on Multi-Feature Fusion (rated Good)
  * Focused on container load prediction for service clusters. The project used MTGNN to model multivariate effects on container load, graph learning to build pairwise dependencies, lightGCN to capture structural information, and temporal convolutions for forecasting. The RMSE improved by 5.42% over the LSTM baseline.
  * Responsible for data preprocessing and model construction, including the graph learning module, graph convolution module, temporal dilated convolution, and Inception layers. Contributed more than 70% of the project work.
* Lingxin Elder Care (Nov. 2022 - May 2023)
  * Built an intelligent elder-care app addressing population aging and the lack of care for older adults, using ChatGPT, speech recognition, voice cloning, and YOLO-based fall detection.
  * Responsible for Android app development, ChatGPT and speech recognition API integration, YOLO fall-detection model setup, voice-cloning model setup, and remote server deployment and maintenance.
  * Received unanimous praise from OPPO experts in the Software Innovation Competition.
* Tizhai (Sep. 2021 - May 2022)
  * Developed a smart study app with Flutter and Spring Boot to help students organize wrong answers and review efficiently.
  * Used Spring Boot and MyBatis to build and maintain the backend and server.

<!-- Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git -->
  
Skills
======
* Research: Vision-Language Models, World Models, Multimodal Reasoning
* Programming: Python, C/C++, Java
* Tools and Frameworks: PyTorch, Git, Linux

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
