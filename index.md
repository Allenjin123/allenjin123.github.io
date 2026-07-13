---
layout: homepage
---

## About Me

I am a Ph.D. candidate in Computer Engineering at the University of Michigan, specializing in Computer Architecture and Electronic Design Automation (EDA). I am advised by [Prof. Nathaniel Bleier](https://crucible.eecs.umich.edu/person.html?id=nathan-bleier), with previous mentorship from [Prof. George Tzimpragos](https://www.georgetzimpragos.com/). I am a proud member of the [CCG research lab](https://crucible.eecs.umich.edu/index.html).

I received my B.Eng. in Electrical and Computer Engineering from Shanghai Jiao Tong University in 2023. During my undergraduate studies, I was fortunate to collaborate with [Prof. Weikang Qian (SJTU)](https://umji.sjtu.edu.cn/~wkqian/people/weikang-qian.html) on stochastic computing and mixed circuits, and with [Prof. Jieru Zhao (SJTU)](https://zjru.github.io/) on machine learning for high-level synthesis.

Feel free to reach out at *allenjin@umich.edu* for research collaborations or discussions.

## Research Interests

My research focuses on **computer architecture** and **electronic design automation (EDA)**, with an emphasis on **hardware–software co-design for machine learning**. I am currently working on composing chiplet-based neural network accelerators and on hardware–software co-design for application-specific processors.

## News

- **[May 2026]** Started my internship as an Architecture Intern at **Tenstorrent**.
- **[2026]** Four papers accepted in 2026: **ISCA** (*æSIP*), **MICRO** (*Fengshui*), **ICCAD** (*TensorLift*), and **DAC** (*Duplication-Aware Retiming*).
- **[Jan. 2026]** Served as a **Graduate Student Instructor** for EECS 598: Computer Architecture for the Post-Moore Era.
- **[2026]** Received the **SIGARCH/ISCA Student Travel Grant** and the **Rackham Conference Travel Grant**.

{% include_relative _includes/publications.md %}

## Selected Projects

**æSIP: µArch-aware ASIP-ISA Co-Design via Program Synthesis, Equality Saturation, and External Don't Cares**  
*Prof. Nathaniel Bleier, University of Michigan · Jul. 2025 – Nov. 2025*

- Proposed æSIP, the first µArch-aware ASIP-ISA co-design framework that leverages hardware-aware program rewriting to automatically generate an optimized ASIP–program pair.
- Built a program synthesis framework leveraging a neuro-symbolic approach to automatically discover correctness-preserving rewrites that maximize hardware-removal opportunities.

**Mozart: An Ecosystem-Accelerator Codesign Framework for Composable, Heterogeneous Chiplet-based Neural Network Accelerators**  
*Prof. Nathaniel Bleier, University of Michigan · Jan. 2025 – Aug. 2025 · published as* Fengshui *at MICRO 2026*

- Developed a chiplet ecosystem-accelerator codesign framework to increase chiplet reuse and reduce non-recurring engineering costs.
- Built a hierarchical design-space-exploration methodology to systematically compose heterogeneous chiplet-based bespoke ASICs, leveraging operator-level disaggregation insights.

**Minimum-Area Retiming for xSFQ Logic**  
*Prof. George Tzimpragos, University of Michigan · Aug. 2024 – Dec. 2024*

- Developed a linear-programming formulation to simultaneously minimize the number of registers and duplication logic in xSFQ circuits, achieving optimal area reduction while maintaining clock-period constraints.

**Mixed Circuits of Binary & Stochastic Computing**  
*Prof. Weikang Qian, SJTU · Jan. 2022 – Sep. 2023*

- Defined a domain-specific language (DSL) for agile mixed-circuit development.
- Evaluated mixed binary–stochastic circuits for image-processing applications.

## Honors & Awards

- **2026** SIGARCH/ISCA Conference Student Travel Grant
- **2026** Rackham Conference Travel Grant
- **2019 – 2022** John Wu & Jane Sun Sunshine Scholarship
- **2020 – 2022** SJTU Undergraduate Excellence Scholarship
