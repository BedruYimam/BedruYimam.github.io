---
title: "Home"
layout: splash
header:
  overlay_color: "#2e8b57"
  overlay_filter: "0.5"
  overlay_image: /assets/images/banner.jpg
  actions:
    - label: "View My CV"
      url: "/assets/documents/cv.pdf"
      btn_class: "btn--primary"
    - label: "Contact Me"
      url: "/contact/"
      btn_class: "btn--primary"
  caption: "Lecturer & Researcher in Computer Science"
excerpt: "Bridging technology and education in Ethiopia"
feature_row:
  - title: "Research"
    excerpt: "Exploring AI, Machine Learning, and Computer Vision applications"
    url: "/research/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - title: "Teaching"
    excerpt: "Computer Science courses and curriculum development"
    url: "/teaching/"
    btn_class: "btn--primary"
    btn_label: "View Courses"
  - title: "Publications"
    excerpt: "Academic papers and research publications"
    url: "/publications/"
    btn_class: "btn--primary"
    btn_label: "Browse Publications"
---

<!-- Custom Navigation Menu -->
<nav class="custom-nav">
  <div class="nav-container">
    <ul class="nav-menu">
      <li><a href="/">Home</a></li>
      <li><a href="/about/">About</a></li>
      <li><a href="/research/">Research</a></li>
      <li><a href="/publications/">Publications</a></li>
      <li><a href="/teaching/">Teaching</a></li>
      <li><a href="/talks/">Talks</a></li>
      <li><a href="/portfolio/">Portfolio</a></li>
      <li><a href="/blog/">Blog</a></li>
      <li><a href="/contact/">Contact</a></li>
    </ul>
  </div>
</nav>

<div class="author__avatar" style="text-align: center; margin: 2rem auto;">
  <img src="/assets/images/bedru.jpg" alt="Bedru Yimam Ahmed" class="profile-image">
</div>

<div style="text-align: center; margin: 2rem 0;">
  <h1>Bedru Yimam Ahmed</h1>
  <h3>Lecturer & Researcher in Computer Science</h3>
  <p>Wollo University, Dessie, Ethiopia</p>
</div>

{% include feature_row %}
