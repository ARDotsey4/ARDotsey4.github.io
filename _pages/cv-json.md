---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume/
  - /resume-json/
  - /cv-json/
---

<style>
  .archive {
    width: 80%;
    margin: 0 auto;
    float: none;
    padding-right: 5%;
    padding-left: 6.137288136%;
  }
  
  @media (min-width: 80em) {
    .archive {
      width: 70%;
    }
  }

  .cv-container {
  margin-top:-1em;
  }
</style>

{% include base_path %}

{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>
