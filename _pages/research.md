---
title: "Research"
permalink: /research/
layout: single
author_profile: true
header:
  overlay_image: /images/research-header.jpg
  overlay_filter: 0.3
---

# Research Program

## Overview

My research at Wollo University focuses on developing computational solutions for Ethiopian challenges. I bridge international research methods with local context to create impactful work.

## Current Projects

### 1. **Machine Learning for Ethiopian Education**
**Duration:** 2023-2025 | **Funding:** Wollo University Research Grant

**Objectives:**
- Predict student academic performance using local data
- Develop early warning systems for at-risk students
- Create personalized learning recommendations

**Technologies:** Python, Scikit-learn, TensorFlow, PostgreSQL

### 2. **Amharic Natural Language Processing Toolkit**
**Duration:** 2022-Present | **Collaboration:** Addis Ababa University

**Components:**
- Amharic text corpus (10M+ words)
- Pretrained BERT models for Amharic
- Named entity recognition system
- Sentiment analysis for Ethiopian social media

### 3. **Digital Literacy in Ethiopian Universities**
**Duration:** 2024-Present | **Partners:** Multiple Ethiopian Universities

**Goals:**
- Assess digital skills among university students
- Develop targeted training programs
- Create open educational resources in Amharic

## Research Areas

### Artificial Intelligence & Machine Learning
- Educational data mining
- Predictive analytics
- Computer vision for agriculture
- Ethical AI for developing contexts

### Natural Language Processing
- Low-resource language processing
- Ethiopian language technologies
- Multilingual models
- Speech recognition for Ethiopian languages

### Computer Science Education
- Curriculum development for Ethiopian context
- Teaching methodologies for CS
- Student engagement strategies
- Assessment and evaluation

### Data Science Applications
- Data-driven policy making
- Open data initiatives
- Visualization for Ethiopian datasets
- Statistical methods for social sciences

## Publications

{% for pub in site.publications %}
- **{{ pub.title }}**  
  *{{ pub.authors }}*  
  {{ pub.venue }}, {{ pub.year }}  
  {% if pub.paperurl %}[PDF]({{ pub.paperurl }}){% endif %}
{% endfor %}

## Research Team

### Graduate Students
- **MSc Student 1**: Topic on ML for Education
- **MSc Student 2**: Topic on Ethiopian NLP
- **BSc Honors Students**: 3 students working on various projects

### Undergraduate Researchers
Multiple students involved in semester projects and research assistantships.

## Collaborations

- **Addis Ababa University** (NLP research)
- **Bahir Dar University** (Educational technology)
- **Jimma University** (Data science applications)
- **International Partners** (Various research projects)

## Funding & Grants

1. **Wollo University Internal Research Grant** (2023-2024)
2. **Ethiopian Ministry of Education Research Award** (2022)
3. **African AI Research Collaboration Grant** (2021-2023)

## Research Philosophy

I believe in:
- **Contextual Relevance**: Research should address local Ethiopian challenges
- **Open Science**: Making research accessible and reproducible
- **Capacity Building**: Training Ethiopian researchers
- **Practical Impact**: Creating solutions that can be implemented

---

**Interested in research collaboration?**  
[Contact me](/about/#contact) to discuss potential projects.
