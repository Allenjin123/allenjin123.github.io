---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-actions {
  display: flex;
  gap: 0.75rem;
  margin-bottom: 1.5rem;
}

.cv-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  padding: 0.6rem 1.2rem;
  font-size: 0.85rem;
  font-weight: 500;
  text-decoration: none;
  border-radius: 5px;
  transition: all 0.15s ease;
}

.cv-btn-primary {
  background: #2d3748;
  color: #fff;
}

.cv-btn-primary:hover {
  background: #1a202c;
  color: #fff;
  text-decoration: none;
}

.cv-btn-secondary {
  background: #fff;
  color: #2d3748;
  border: 1px solid #d1d5db;
}

.cv-btn-secondary:hover {
  background: #f7fafc;
  color: #2d3748;
  text-decoration: none;
}

.cv-btn svg {
  width: 14px;
  height: 14px;
}

.cv-viewer {
  border: 1px solid #e2e8f0;
  border-radius: 6px;
  overflow: hidden;
}

.cv-iframe-container {
  width: 100%;
  height: 80vh;
  min-height: 500px;
}

.cv-iframe-container iframe {
  width: 100%;
  height: 100%;
  border: none;
}

@media (max-width: 600px) {
  .cv-actions {
    flex-direction: column;
  }

  .cv-btn {
    justify-content: center;
  }

  .cv-iframe-container {
    height: 60vh;
    min-height: 400px;
  }
}
</style>

<div class="cv-actions">
  <a href="/files/HaoranJin_CV.pdf" target="_blank" class="cv-btn cv-btn-primary">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
    </svg>
    View PDF
  </a>
  <a href="/files/HaoranJin_CV.pdf" download="HaoranJin_CV.pdf" class="cv-btn cv-btn-secondary">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
    </svg>
    Download
  </a>
</div>

<div class="cv-viewer">
  <div class="cv-iframe-container">
    <iframe src="/files/HaoranJin_CV.pdf" title="Haoran Jin CV">
      <p>Your browser does not support embedded PDFs. <a href="/files/HaoranJin_CV.pdf">Download the CV here</a>.</p>
    </iframe>
  </div>
</div>