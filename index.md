---
layout: home
title: "Bedru Yimam"
permalink: /
author_profile: true
header:
  overlay_image: /images/header-bg.jpg
  overlay_filter: 0.3
  overlay_color: "#5e616c"
  caption: "Academic Portfolio"
  actions:
    - label: "View Publications"
      url: "/publications/"
    - label: "Download CV"
      url: "/files/cv.pdf"
excerpt: "Lecturer and Researcher | Computer Science | Wollo University"
feature_row:
  - title: "Research"
    excerpt: "Machine Learning, NLP, Educational Technology, Data Science"
    url: "/research/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - title: "Teaching"
    excerpt: "Computer Science courses, Student supervision, Curriculum development"
    url: "/teaching/"
    btn_class: "btn--primary"
    btn_label: "View Courses"
  - title: "Projects"
    excerpt: "Open source tools, Research software, Community initiatives"
    url: "/projects/"
    btn_class: "btn--primary"
    btn_label: "See Projects"
---

# Welcome

I am **Bedru Yimam**, a lecturer and researcher in the Department of Computer Science at Wollo University in Dessie, Ethiopia. My work focuses on applying computational methods to address educational challenges and advance technology adoption in Ethiopian higher education.

## Recent Updates

{% for post in site.posts limit:3 %}
- **{{ post.date | date: "%B %d, %Y" }}**: [{{ post.title }}]({{ post.url }})
{% endfor %}

[View all posts →](/year-archive/)

## Featured Publications

{% assign featured_pubs = site.publications | where: "featured", true %}
{% if featured_pubs.size > 0 %}
  {% for pub in featured_pubs limit:3 %}
  - **{{ pub.title }}**  
    *{{ pub.authors }}*  
    {{ pub.venue }}, {{ pub.year }}  
    [{% if pub.paperurl %}PDF{% endif %}]({{ pub.paperurl }}){% if pub.code %} | [Code]({{ pub.code }}){% endif %}
  {% endfor %}
{% else %}
  *Publications will appear here soon*
{% endif %}

[View all publications →](/publications/)

## Research Interests

- **Machine Learning & AI**: Applications in education and local contexts
- **Natural Language Processing**: Tools for Ethiopian languages
- **Educational Technology**: Improving learning outcomes through technology
- **Data Science**: Analytics for decision-making in higher education
- **Open Source Software**: Building tools for researchers and educators

## Contact

**Email**: [bedruy4@gmail.com](mailto:bedruy4@gmail.com)  
**Location**: Dessie, Ethiopia  
**Institution**: Wollo University  
**Department**: Computer Science  

---

*"Education is the most powerful weapon which you can use to change the world."*  
*— Nelson Mandela*
