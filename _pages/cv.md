---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- PDF Viewer Section -->
<div class="cv-pdf-container" style="max-width: 100%; margin: 1.5rem 0;">
  
  <!-- Embedded PDF Viewer (responsive) -->
  <div style="position: relative; padding-bottom: 120%; height: 0; overflow: hidden; border: 1px solid #ddd; border-radius: 4px; background: #fafafa;">
    <embed 
      src="{{ base_path }}/files/cv_pritom_paul.pdf" 
      type="application/pdf"
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; min-height: 450px;"
      title="Pritom Paul - Curriculum Vitae"
    >
    <!-- Fallback message for browsers that don't support embed -->
    <p style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); text-align: center; color: #666; padding: 2rem;">
      Your browser doesn't support embedded PDFs.<br>
      <a href="{{ base_path }}/files/cv_pritom_paul.pdf" target="_blank" style="color: #0366d6; font-weight: 500;">Click here to view or download your CV</a>.
    </p>
  </div>

  <!-- Download Button -->
  <div style="text-align: center; margin: 1.25rem 0;">
    <a 
      href="{{ base_path }}/files/cv_pritom_paul.pdf" 
      download="Pritom_Paul_CV.pdf"
      class="btn btn--primary"
      style="display: inline-block; padding: 0.75rem 1.5rem; background: #0366d6; color: white; text-decoration: none; border-radius: 4px; font-weight: 500; transition: background 0.2s;"
      onmouseover="this.style.background='#0255b3'"
      onmouseout="this.style.background='#0366d6'"
    >
      📥 Download CV (PDF)
    </a>
  </div>

  <!-- Last Updated Timestamp -->
  <div style="text-align: center; color: #666; font-size: 0.9rem; margin-top: 0.5rem;">
    <em>Last updated: {{ site.time | date: "%B %d, %Y" }}</em>
  </div>
