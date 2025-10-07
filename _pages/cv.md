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
* Ph.D in Computer Engineering, University of Michigan, Sep. 2023 - present
  * Focus: Computer Architecture & EDA
  * Advisor: Prof. Nathaniel Bleier & Previous Advisor: Prof. George Tzimpragos
* B.Eng in Electrical and Computer Engineering, Shanghai Jiao Tong University, Sep. 2019 - Aug. 2023

Honors and Awards
======
* 2020, 2021, 2022 National Encouragement Scholarship
* 2019, 2020, 2021, 2022 John Wu & Jane Sun Sunshine Scholarship
* 2020, 2021, 2022 SJTU Undergraduate Excellence Scholarship


Research experience
======
* Mozart: An Ecosystem-Accelerator Codesign Framework        *Jan. 2025 – Aug. 2025*
  * Prof. Nathaniel Bleier at University of Michigan
  * Developed a chiplet ecosystem-accelerator codesign framework to increase chiplet reuse and reduce non-recurring engineering costs
  * Built hierarchical design space exploration methodology to systematically compose heterogeneous chiplet-based bespoke ASIC leveraging operator-level disaggregation insights
  * Implemented constraint-aware optimization for datacenter LLM serving and autonomous vehicle case studies

* Minimum Area Retiming for xSFQ logic        *Aug. 2024 – Dec. 2024*
  * Prof. George Tzimpragos at University of Michigan
  * Developed a linear programming formulation to simultaneously minimize the number of registers and duplication logic in xSFQ circuits for optimal area reduction while maintaining clock period constraints

* Mixed Circuit of Binary & Stochastic Computing          *Jan. 2022 – Sep. 2023*
  * Prof. Weikang Qian at SJTU
  * Defined a domain-specific language (DSL) for agile mixed circuit development
  * Implemented a Verilog code generation backend for the DSL to facilitate hardware synthesis
  * Evaluated mixed binary-stochastic circuits for image processing applications


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
  

