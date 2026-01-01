---
layout: home
title: "Bedru Yimam"
permalink: /
author_profile: true
header:
  overlay_image: /images/header-bg.jpg
  overlay_filter: 0.3
  overlay_color: "#078930"
excerpt: "Computer Science Lecturer & Researcher<br>Wollo University, Ethiopia"
---

# Welcome

I'm **Bedru Yimam**, a lecturer and researcher in Computer Science at **Wollo University** in Dessie, Ethiopia. My work focuses on applying technology to address educational challenges and advance research in the Ethiopian context.

## Research Areas

**Artificial Intelligence & Machine Learning**  
Developing ML models for education and local applications

**Natural Language Processing**  
Building tools for Ethiopian languages

**Computer Science Education**  
Improving teaching and learning in Ethiopian universities

**Data Science**  
Applying data analytics to local challenges

## Current Projects

### 1. Ethiopian Student Analytics Platform
A dashboard for tracking and predicting student performance in Ethiopian universities.

### 2. Amharic NLP Toolkit
Open-source tools for processing Amharic text using modern NLP techniques.

### 3. CS Curriculum Development
Creating computer science curriculum tailored for Ethiopian universities.

## Recent Publications

{% assign recent_pubs = site.publications | sort: "year" | reverse %}
{% for pub in recent_pubs limit:3 %}
- **{{ pub.title }}**  
  *{{ pub.venue }}, {{ pub.year }}*  
  {% if pub.paperurl %}[PDF]({{ pub.paperurl }}){% endif %}
{% endfor %}

[View all publications →](/publications/)

## Teaching

**Current Courses at Wollo University:**
- CSC 101: Introduction to Computer Science
- CSC 201: Data Structures and Algorithms
- CSC 301: Database Systems
- CSC 501: Machine Learning (Graduate)

[Teaching portfolio →](/teaching/)

## Contact

**Email:** [bedruy4@gmail.com](mailto:bedruy4@gmail.com)  
**Location:** Dessie, Ethiopia  
**University:** Wollo University  
**Department:** Computer Science

[Download CV](/files/cv.pdf) | [View Projects](/projects/)
