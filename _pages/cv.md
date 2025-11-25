---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-container {
  max-width: 100%;
  margin: 0 auto;
}

.cv-header {
  text-align: center;
  padding: 2.5rem 1rem;
  margin-bottom: 2rem;
  border-bottom: 1px solid #e8e8e8;
}

.cv-header h2 {
  font-size: 1.75rem;
  font-weight: 300;
  color: #333;
  margin: 0 0 0.5rem 0;
  letter-spacing: 0.5px;
  border-bottom: none;
  padding-bottom: 0;
}

.cv-subtitle {
  font-size: 0.95rem;
  color: #888;
  font-weight: 400;
  margin-bottom: 1.75rem;
}

.cv-actions {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.cv-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.75rem 1.5rem;
  font-size: 0.875rem;
  font-weight: 500;
  text-decoration: none;
  border-radius: 6px;
  transition: all 0.2s ease;
}

.cv-btn-primary {
  background-color: #2d3748;
  color: #fff;
}

.cv-btn-primary:hover {
  background-color: #1a202c;
  color: #fff;
  text-decoration: none;
  transform: translateY(-1px);
}

.cv-btn-secondary {
  background-color: transparent;
  color: #2d3748;
  border: 1px solid #d1d5db;
}

.cv-btn-secondary:hover {
  background-color: #f7fafc;
  border-color: #9ca3af;
  color: #2d3748;
  text-decoration: none;
}

.cv-btn svg {
  width: 16px;
  height: 16px;
}

.cv-viewer {
  background: #fafafa;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08);
}

.cv-viewer-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.75rem 1rem;
  background: #fff;
  border-bottom: 1px solid #e8e8e8;
}

.cv-viewer-title {
  font-size: 0.8rem;
  color: #666;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.cv-viewer-actions a {
  color: #666;
  text-decoration: none;
  font-size: 0.8rem;
  transition: color 0.2s ease;
}

.cv-viewer-actions a:hover {
  color: #333;
}

.cv-iframe-container {
  width: 100%;
  height: 85vh;
  min-height: 600px;
  max-height: 1000px;
}

.cv-iframe-container iframe {
  width: 100%;
  height: 100%;
  border: none;
}

.cv-fallback {
  padding: 3rem;
  text-align: center;
  color: #666;
}

.cv-fallback a {
  color: #2d3748;
  text-decoration: underline;
}

@media (max-width: 600px) {
  .cv-header {
    padding: 1.5rem 1rem;
  }

  .cv-header h2 {
    font-size: 1.4rem;
  }

  .cv-actions {
    flex-direction: column;
    align-items: center;
  }

  .cv-btn {
    width: 100%;
    max-width: 200px;
    justify-content: center;
  }

  .cv-iframe-container {
    height: 70vh;
    min-height: 400px;
  }
}
</style>

<div class="cv-container">
  <div class="cv-header">
    <h2>Curriculum Vitae</h2>
    <p class="cv-subtitle">Last updated November 2024</p>
    <div class="cv-actions">
      <a href="/files/HaoranJin_CV.pdf" target="_blank" class="cv-btn cv-btn-primary">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z" />
        </svg>
        View Full PDF
      </a>
      <a href="/files/HaoranJin_CV.pdf" download="HaoranJin_CV.pdf" class="cv-btn cv-btn-secondary">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
        </svg>
        Download
      </a>
    </div>
  </div>

  <div class="cv-viewer">
    <div class="cv-viewer-header">
      <span class="cv-viewer-title">Document Preview</span>
      <div class="cv-viewer-actions">
        <a href="/files/HaoranJin_CV.pdf" target="_blank">Open in new tab</a>
      </div>
    </div>
    <div class="cv-iframe-container">
      <iframe src="/files/HaoranJin_CV.pdf" title="Haoran Jin CV">
        <div class="cv-fallback">
          <p>Your browser does not support embedded PDFs.</p>
          <p><a href="/files/HaoranJin_CV.pdf">Click here to download the CV</a></p>
        </div>
      </iframe>
    </div>
  </div>
</div>