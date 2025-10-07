---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div style="text-align: center; margin: 2rem 0;">
  <h2>Haoran Jin - Curriculum Vitae</h2>

  <div style="margin: 1.5rem 0;">
    <a href="/files/HaoranJin_CV.pdf" target="_blank" style="display: inline-block; background-color: #007cba; color: white; padding: 12px 24px; text-decoration: none; border-radius: 5px; margin: 0 10px; font-weight: bold;">
      📄 View PDF
    </a>
    <a href="/files/HaoranJin_CV.pdf" download="HaoranJin_CV.pdf" style="display: inline-block; background-color: #28a745; color: white; padding: 12px 24px; text-decoration: none; border-radius: 5px; margin: 0 10px; font-weight: bold;">
      ⬇️ Download PDF
    </a>
  </div>
</div>

<!-- Embedded PDF Viewer -->
<div style="width: 100%; height: 800px; border: 1px solid #ddd; margin: 2rem 0;">
  <iframe src="/files/HaoranJin_CV.pdf" width="100%" height="100%" style="border: none;">
    <p>Your browser does not support PDFs. <a href="/files/HaoranJin_CV.pdf">Download the PDF</a>.</p>
  </iframe>
</div>

<!-- Alternative text-based CV for SEO and accessibility -->
<div style="margin-top: 3rem; padding-top: 2rem; border-top: 2px solid #eee;">
  <h3>CV Summary (Text Version)</h3>

  <h4>Education</h4>
  <ul>
    <li><strong>Ph.D in Computer Engineering</strong>, University of Michigan, Sep. 2023 - present
      <ul>
        <li>Focus: Computer Architecture & EDA</li>
        <li>Advisor: Prof. Nathaniel Bleier & Previous Advisor: Prof. George Tzimpragos</li>
      </ul>
    </li>
    <li><strong>B.Eng in Electrical and Computer Engineering</strong>, Shanghai Jiao Tong University, Sep. 2019 - Aug. 2023</li>
  </ul>

  <h4>Selected Publications</h4>
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  <p style="margin-top: 2rem; text-align: center; color: #666; font-style: italic;">
    For complete details, please view or download the PDF version above.
  </p>
</div>
  

