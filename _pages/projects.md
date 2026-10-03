---
layout: page
title: projects
permalink: /projects/
description: Selected engineering and research projects.
nav: true
nav_order: 3
---

<style>
  .project-showcase {
    display: grid;
    gap: 4rem;
    margin-top: 2.25rem;
  }

  .project-showcase-row {
    display: grid;
    grid-template-columns: minmax(330px, 420px) minmax(0, 1fr);
    gap: 3rem;
    align-items: center;
  }

  .project-showcase-preview {
    display: block;
    width: 100%;
  }

  .project-showcase-preview img {
    display: block;
    width: 100%;
    aspect-ratio: 16 / 9;
    object-fit: contain;
    background: #fff;
    border: 1px solid var(--global-divider-color);
    border-radius: 0.4rem;
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.14);
  }

  .project-showcase-copy h2 {
    margin: 0 0 1rem;
    font-size: clamp(1.8rem, 3vw, 2.5rem);
    line-height: 1.18;
  }

  .project-showcase-copy p {
    margin: 0;
    font-size: 1.2rem;
    line-height: 1.65;
  }

  .project-showcase-link {
    margin-top: 1.25rem !important;
    font-size: 1rem !important;
    font-weight: 600;
  }

  @media (max-width: 767px) {
    .project-showcase {
      gap: 3rem;
    }

    .project-showcase-row {
      grid-template-columns: 1fr;
      gap: 1.5rem;
    }

    .project-showcase-preview {
      max-width: 560px;
    }
  }
</style>

<div class="project-showcase">
  <article class="project-showcase-row">
    <a class="project-showcase-preview" href="{{ '/projects/1_project/' | relative_url }}" aria-label="Learn more about the Inflatable Magnetic Soft Tactile Sensor project">
      <img src="{{ '/assets/img/inflatable-magnetic-soft-tactile-sensor.png' | relative_url }}" alt="Full title slide for the Inflatable Magnetic Soft Tactile Sensor project">
    </a>
    <div class="project-showcase-copy">
      <h2><a href="{{ '/projects/1_project/' | relative_url }}">Inflatable Magnetic Soft Tactile Sensor</a></h2>
      <p>Soft tactile sensing for force, orientation, and contact-state estimation. Publication aimed for later this year.</p>
      <p class="project-showcase-link"><a href="{{ '/assets/pdf/inflatable-magnetic-soft-tactile-sensor-presentation.pdf' | relative_url }}">View full presentation &rarr;</a></p>
    </div>
  </article>

  <article class="project-showcase-row">
    <a class="project-showcase-preview" href="{{ '/assets/pptx/hypotree-overview.pptx' | relative_url }}" aria-label="Open the complete HypoTree presentation">
      <img src="{{ '/assets/img/hypotree-overview.png' | relative_url }}" alt="Full title slide for the HypoTree project">
    </a>
    <div class="project-showcase-copy">
      <h2><a href="{{ '/assets/pptx/hypotree-overview.pptx' | relative_url }}">HypoTree</a></h2>
      <p>An AI-assisted tree workspace that helps scientists structure multi-experiment research and decide what to test next.</p>
      <p class="project-showcase-link"><a href="{{ '/assets/pptx/hypotree-overview.pptx' | relative_url }}">View full presentation &rarr;</a></p>
    </div>
  </article>
</div>
