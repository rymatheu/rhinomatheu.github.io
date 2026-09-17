---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
---

<div class="cv-pdf">
  <div class="cv-pdf-actions">
    <a
      class="btn btn-sm z-depth-0"
      role="button"
      href="{{ '/assets/pdf/cv.pdf' | relative_url }}"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fa-solid fa-up-right-from-square"></i> Open in new tab
    </a>
    <a class="btn btn-sm z-depth-0" role="button" href="{{ '/assets/pdf/cv.pdf' | relative_url }}" download>
      <i class="fa-solid fa-download"></i> Download PDF
    </a>
  </div>

  <div class="cv-pdf-frame">
    <iframe src="{{ '/assets/pdf/cv.pdf' | relative_url }}" title="Curriculum vitae"></iframe>
  </div>

  <p class="cv-pdf-fallback">
    Mobile browsers can't display PDFs inline — use one of the buttons above to view or download the CV.
  </p>
</div>

<style>
  .cv-pdf-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1rem;
  }

  .cv-pdf-actions .btn {
    color: var(--global-text-color);
    border: 1px solid var(--global-divider-color);
    background-color: var(--global-card-bg-color);
  }

  .cv-pdf-actions .btn:hover {
    color: var(--global-hover-text-color);
    background-color: var(--global-hover-color);
    border-color: var(--global-hover-color);
  }

  .cv-pdf-frame {
    height: 80vh;
    height: 80dvh;
    min-height: 500px;
    border: 1px solid var(--global-divider-color);
    border-radius: 6px;
    overflow: hidden;
  }

  .cv-pdf-frame iframe {
    display: block;
    width: 100%;
    height: 100%;
    border: none;
  }

  .cv-pdf-fallback {
    display: none;
    margin-top: 1rem;
    font-size: 0.9rem;
    color: var(--global-text-color-light);
  }

  /* Mobile browsers (iOS Safari especially) refuse to render PDFs in an
     iframe and leave a blank box, so show the links instead. */
  @media (max-width: 767px) {
    .cv-pdf-frame {
      display: none;
    }

    .cv-pdf-fallback {
      display: block;
    }
  }
</style>
