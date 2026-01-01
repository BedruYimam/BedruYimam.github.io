---
layout: home
title: "Dr. Bedru Yimam Ahmed"
permalink: /
author_profile: true
header:
  overlay_image: /images/ethiopia-banner.jpg  # Add Ethiopian-themed banner
  overlay_filter: 0.5
  overlay_color: "#1a4d1a"  # Ethiopian green
  cta_label: "<i class='fas fa-graduation-cap'></i> View CV"
  cta_url: "/files/cv.pdf"
  caption: "በድሩ ይማም አህመድ - Lecturer & Researcher"
excerpt: "Department of Computer Science · Wollo University · Dessie, Ethiopia"
feature_row:
  - image_path: /images/research-icon.png
    alt: "Research"
    title: "Research"
    excerpt: "Machine Learning · NLP · Educational Technology · Data Science"
    url: "/research/"
    btn_label: "Research Projects"
    btn_class: "btn--primary"
  - image_path: /images/teaching-icon.png
    alt: "Teaching"
    title: "Teaching"
    excerpt: "CS Courses · Student Supervision · Curriculum Development"
    url: "/teaching/"
    btn_label: "Teaching Portfolio"
    btn_class: "btn--primary"
  - image_path: /images/projects-icon.png
    alt: "Projects"
    title: "Projects"
    excerpt: "Open Source · Community Initiatives · Software Tools"
    url: "/projects/"
    btn_label: "View Projects"
    btn_class: "btn--primary"
---

<div class="ethiopia-flag" style="text-align: center; margin: 2rem 0;">
  <div style="display: inline-block; padding: 0.5rem 1.5rem; background: linear-gradient(to right, #078930, #fadd00, #da121a); border-radius: 5px; color: white; font-weight: bold;">
    🇪🇹 Ethiopian Researcher · Ethiopian Solutions
  </div>
</div>

# Welcome

I am **Bedru Yimam Ahmed** (በድሩ ይማም አህመድ), a dedicated lecturer and researcher in the **Department of Computer Science at Wollo University**, Dessie, Ethiopia. My mission is to advance computational research and education in Ethiopia while developing locally-relevant technological solutions.

## 🔬 Recent Research Highlights

{% assign recent_pubs = site.publications | sort: "year" | reverse %}
{% for pub in recent_pubs limit:3 %}
<div class="publication-highlight">
  <h4>{{ pub.title }}</h4>
  <p><em>{{ pub.authors }}</em><br>
  <strong>{{ pub.venue }}</strong> · {{ pub.year }}</p>
  {% if pub.paperurl %}<a href="{{ pub.paperurl }}" class="btn btn--small">📄 PDF</a>{% endif %}
  {% if pub.code %}<a href="{{ pub.code }}" class="btn btn--small">💻 Code</a>{% endif %}
</div>
{% endfor %}

[View all publications →](/publications/)

## 📚 Current Courses (Wollo University)

- **CSC 101**: Introduction to Computer Science
- **CSC 201**: Data Structures and Algorithms  
- **CSC 301**: Database Systems
- **CSC 401**: Artificial Intelligence
- **CSC 501**: Machine Learning (Graduate)

[Complete teaching portfolio →](/teaching/)

## 🌍 Research Focus Areas

<div class="research-grid">
  <div class="research-area">
    <h3><i class="fas fa-brain"></i> AI/ML for Ethiopia</h3>
    <p>Developing machine learning models tailored to Ethiopian educational and agricultural contexts.</p>
  </div>
  <div class="research-area">
    <h3><i class="fas fa-language"></i> Ethiopian NLP</h3>
    <p>Creating natural language processing tools for Amharic and other Ethiopian languages.</p>
  </div>
  <div class="research-area">
    <h3><i class="fas fa-laptop-code"></i> CS Education</h3>
    <p>Improving computer science education through technology and innovative pedagogy.</p>
  </div>
</div>

## 📢 Latest Updates

{% for post in site.posts limit:3 %}
<div class="news-item">
  <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
  <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
</div>
{% endfor %}

[Read all updates →](/year-archive/)

## 🤝 Collaboration & Contact

I welcome collaborations with:
- **Researchers** in AI, NLP, and educational technology
- **Universities** seeking partnerships in Ethiopia
- **Students** interested in graduate research
- **Industry** applying technology to Ethiopian challenges

**Contact Information:**  
📧 Email: [bedruy4@gmail.com](mailto:bedruy4@gmail.com)  
🏫 Office: Department of Computer Science, Wollo University, Dessie  
📞 Phone: +251-XXX-XXX-XXX  
🔗 LinkedIn: [Your Profile](https://linkedin.com)

---

<div class="quote" style="text-align: center; font-style: italic; margin: 2rem 0; padding: 1rem; background: #f5f5f5; border-left: 4px solid #078930;">
  "የቴክኖሎጂ ልማት ለኢትዮጵያ ልዩ ፍላጎቶች መሟላት አለበት።"<br>
  "Technology development must address Ethiopia's unique needs."
</div>
