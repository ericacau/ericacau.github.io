---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /cv-json/
  - /resume-json
---

<style>
  .cv-download-only {
    min-height: 45vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2rem 1rem 4rem;
  }

  .cv-download-card {
    display: flex;
    align-items: center;
    gap: 1.25rem;
    width: min(100%, 560px);
    padding: 1.5rem;
    color: var(--global-text-color) !important;
    text-decoration: none !important;
    background: var(--global-bg-color);
    border: 1px solid var(--global-border-color);
    border-radius: 18px;
    box-shadow: 0 12px 35px rgba(0, 0, 0, 0.08);
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  }

  .cv-download-card:hover {
    transform: translateY(-3px);
    border-color: var(--global-link-color);
    box-shadow: 0 18px 45px rgba(0, 0, 0, 0.13);
  }

  .cv-download-card:focus-visible {
    outline: 3px solid var(--global-link-color);
    outline-offset: 4px;
  }

  .cv-download-icon {
    flex: 0 0 72px;
    width: 72px;
    height: 72px;
    display: grid;
    place-items: center;
    color: var(--global-link-color);
    font-size: 2rem;
    background: rgba(82, 173, 200, 0.14);
    border-radius: 16px;
  }

  .cv-download-copy {
    flex: 1;
    min-width: 0;
  }

  .cv-download-copy strong,
  .cv-download-copy small {
    display: block;
  }

  .cv-download-copy strong {
    margin-bottom: 0.25rem;
    font-size: 1.15rem;
  }

  .cv-download-copy small {
    color: var(--global-text-color-light);
  }

  .cv-download-arrow {
    color: var(--global-link-color);
    font-size: 1.15rem;
    transition: transform 0.2s ease;
  }

  .cv-download-card:hover .cv-download-arrow {
    transform: translateX(4px);
  }

  @media (max-width: 480px) {
    .cv-download-only {
      padding-inline: 0;
    }

    .cv-download-card {
      gap: 1rem;
      padding: 1.1rem;
    }

    .cv-download-icon {
      flex-basis: 58px;
      width: 58px;
      height: 58px;
    }
  }
</style>

<div class="cv-download-only">
  <a href="https://drive.google.com/file/d/19xAN4C5jNUzobbMIfhkWTbChZCYcEfWn/view?usp=sharing" class="cv-download-card" target="_blank" rel="noopener noreferrer" aria-label="Open Erica Cau's CV as a PDF">
    <span class="cv-download-icon" aria-hidden="true"><i class="fas fa-file-pdf"></i></span>
    <span class="cv-download-copy">
      <strong>Curriculum Vitae</strong>
      <small>Open the PDF in a new tab</small>
    </span>
    <span class="cv-download-arrow" aria-hidden="true"><i class="fas fa-arrow-right"></i></span>
  </a>
</div>
