---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng in Electrical and Computer Engineering, Shanghai Jiao Tong University, Sep. 2019 - present

Coursework
======
GPA:3.81 Ranking: 14/255 (Top 5%)

Logic Design($A^{+}$) Computer Organization($A$) Programming & Data Structure($A^{+}$)


Research experience
======
* Secure Non-volatile Memory Based on Out-of-place Update        *Jul. 2022 – present*
  * Prof. Jian Huang at UIUC
  * Implemented MAC and Merkle Tree essential for integrity and confidentiality.    
  * Utilized Out-of-place updates to improve performanceDuties included: Tagging issues
  
* Mixed Circuit Design of Binary & Stochastic Computing          *Jan. 2022 – present*
  * Prof. Weikang Qian at SJTU
  * Implemented Tiled Gaussian Blur, Convolution and Sobel Operator in mixed circuit
  * Accelerated estimation of error rate through table lookup
  * Built Desgin Space Exploration to search for Pareto Solution regarding error rate and power
  * Defined domain-specific language to facilitate mixed circuit developing

* Machine Learning for High Level Synthesis       *Mar. 2021 – Oct. 2021*
  * Prof. Jieru Zhao at SJTU
  * Used Graph Neural Network to provide accurate and fast prediction of metrics
  * Built a program that extracts features from HLS reports and intermediate files
  * Planned to use Neural Architecture Search to get model parameter and transfer learning for big graph.


Project
=====
* Recommendation System for Big Data
  * Implemented Breadth-First-Search on 4 node Hadoop cluster using Spark and MapReduce.

* Multi-threaded SQL Database
  * Wrote a multi-threaded database supporting SQL-like syntax
  * Implemented thread pool and parallel reducer for acceleration


* Scheduling Algorithm in Minix 3.2.1
  *Implemented Earliest Deadline First and Lottery Algorithm in the kernel space


Skills
======
* Programing: C, C++, Java, Python, Verilog HDL, SQL, LLVM IR, ELM 
* Tools: MatLab, PyTorch, Mathematica, Vitis HLS, Spark, Drill, MapReduce, Hadoop, Pin, Pintool, Pspice
* Language: TOEFL:107 GRE: 322 + 4.0

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

