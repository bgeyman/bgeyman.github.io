---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* Simple CV styling for work experience cards */
.cv-section {
  margin-bottom: 2rem;
}

.cv-item {
  margin-bottom: 1.25rem;
  padding: 0.75rem 1rem;
  border-left: 3px solid #4b9cd3;
  background-color: #f9fafb;
}

.cv-item-title {
  font-weight: 600;
}

.cv-item-meta {
  font-style: italic;
  font-size: 0.9rem;
  color: #555;
}

.cv-item-org {
  font-weight: 500;
}
</style>

Education
======
* **Harvard University**, Cambridge, MA  
  Ph.D., Environmental Science and Engineering — December 2024  
  A.M., Earth and Planetary Sciences — May 2022  

* **Bowdoin College**, Brunswick, ME  
  A.B., Earth and Oceanographic Science — December 2016  

Professional Experience
======

<div class="cv-section">

  <div class="cv-item">
    <div class="cv-item-title">Senior Biogeochemical Modeler</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">CREW Carbon</span> · May 2025 – Present
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Research Associate</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Harvard University, John A. Paulson School of Engineering and Applied Sciences</span> · May 2025 – Present
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Postdoctoral Fellow</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Harvard University, John A. Paulson School of Engineering and Applied Sciences</span> · January 2025 – April 2025
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Graduate Research Assistant (with Prof. Elsie M. Sunderland)</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Harvard University, Department of Earth and Planetary Sciences</span> · 2018 – 2024
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Climate Data PhD Summer Student Analyst</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Electric Power Research Institute</span> · June 2024 – December 2024
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Energy Analyst</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Competitive Energy Services, Portland, ME</span> · 2017 – 2018
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Summer Student Fellow → Guest Investigator</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Woods Hole Oceanographic Institution, Woods Hole, MA</span> · 2016 – 2017
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">REU Researcher</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">Hubbard Brook Experimental Forest, Woodstock, NH</span> · 2015
    </div>
  </div>

  <div class="cv-item">
    <div class="cv-item-title">Student Hydrologist</div>
    <div class="cv-item-meta">
      <span class="cv-item-org">U.S. Geological Survey, Augusta, ME</span> · 2014
    </div>
  </div>

</div>

Publications
======
<ul>
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>
