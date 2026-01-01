---
layout: home
title: "Dr. Bedru Yimam Ahmed"
permalink: /
author_profile: true
classes: wide
sidebar:
  - title: "Quick Links"
    nav: "sidebar-nav"
  - title: "Research Focus"
    text: "AI/ML · Ethiopian NLP · CS Education · Data Science"
  - title: "Contact"
    text: |
      📧 bedruy4@gmail.com  
      🏛️ Wollo University  
      📍 Dessie, Ethiopia  
      🔗 [LinkedIn](https://linkedin.com)  
      👨‍💻 [GitHub](https://github.com/BedruYimam)
header:
  overlay_image: /images/ethiopia-tech-banner.jpg
  overlay_filter: linear-gradient(135deg, rgba(7, 137, 48, 0.7), rgba(218, 18, 26, 0.7))
  overlay_color: "#1a4d1a"
  cta_label: "<i class='fas fa-download'></i> Download CV"
  cta_url: "/files/cv.pdf"
  caption: |
    <span style="font-size: 1.2em; font-weight: bold;">በድሩ ይማም አህመድ</span><br>
    <span style="font-size: 0.9em;">Computer Science · Research · Innovation</span>
excerpt: |
  <div class="excerpt-highlight">
    <div class="eth-tag">🇪🇹 Ethiopian Researcher</div>
    <div class="eth-tag">👨‍🏫 University Lecturer</div>
    <div class="eth-tag">🤖 AI Specialist</div>
  </div>
feature_row:
  - icon: "fas fa-brain"
    title: "Research"
    excerpt: "AI, NLP, Educational Technology"
    url: "/research/"
    btn_class: "btn--eth-green"
    btn_label: "Explore Research"
  - icon: "fas fa-chalkboard-teacher"
    title: "Teaching"
    excerpt: "CS Courses & Student Supervision"
    url: "/teaching/"
    btn_class: "btn--eth-yellow"
    btn_label: "View Courses"
  - icon: "fas fa-code"
    title: "Projects"
    excerpt: "Open Source & Software Tools"
    url: "/projects/"
    btn_class: "btn--eth-red"
    btn_label: "See Projects"
---

<style>
/* Modern Grid Layout */
.main-content {
  display: grid;
  grid-template-columns: 1fr 300px;
  gap: 2rem;
  margin-top: 2rem;
}

@media (max-width: 768px) {
  .main-content {
    grid-template-columns: 1fr;
  }
}

/* Ethiopian Color Scheme */
:root {
  --eth-green: #078930;
  --eth-yellow: #fadd00;
  --eth-red: #da121a;
  --eth-dark: #0a2914;
  --eth-light: #f0f8f2;
}

/* Modern Cards */
.modern-card {
  background: white;
  border-radius: 12px;
  padding: 1.5rem;
  margin: 1rem 0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  border-left: 4px solid var(--eth-green);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.modern-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
}

/* Ethiopian Tags */
.eth-tag {
  display: inline-block;
  padding: 0.4rem 1rem;
  margin: 0.2rem;
  background: linear-gradient(135deg, var(--eth-green), var(--eth-yellow));
  color: white;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
  box-shadow: 0 2px 5px rgba(7, 137, 48, 0.3);
}

/* Feature Cards */
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.feature-item {
  background: linear-gradient(135deg, #ffffff, #f8f9fa);
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
  border: 1px solid #e9ecef;
  transition: all 0.3s ease;
}

.feature-item:hover {
  border-color: var(--eth-green);
  box-shadow: 0 6px 15px rgba(7, 137, 48, 0.1);
}

.feature-item i {
  font-size: 2.5rem;
  color: var(--eth-green);
  margin-bottom: 1rem;
}

/* Publication Highlights */
.pub-highlight {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  padding: 1.2rem;
  margin: 1rem 0;
  background: var(--eth-light);
  border-radius: 8px;
  border-left: 4px solid var(--eth-red);
}

.pub-year {
  background: var(--eth-red);
  color: white;
  padding: 0.3rem 0.8rem;
  border-radius: 4px;
  font-weight: bold;
  min-width: 60px;
  text-align: center;
}

/* Sidebar Navigation */
.sidebar-nav ul {
  list-style: none;
  padding: 0;
}

.sidebar-nav li {
  margin: 0.5rem 0;
}

.sidebar-nav a {
  display: flex;
  align-items: center;
  padding: 0.8rem 1rem;
  background: #f8f9fa;
  border-radius: 8px;
  color: #333;
  text-decoration: none;
  transition: all 0.3s ease;
  border-left: 3px solid transparent;
}

.sidebar-nav a:hover {
  background: var(--eth-light);
  border-left-color: var(--eth-green);
  transform: translateX(5px);
}

.sidebar-nav i {
  margin-right: 0.8rem;
  color: var(--eth-green);
}

/* Stats Counter */
.stats-counter {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin: 2rem 0;
}

.stat-item {
  text-align: center;
  padding: 1rem;
  background: white;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.05);
}

.stat-number {
  font-size: 2rem;
  font-weight: bold;
  color: var(--eth-green);
  display: block;
}

/* Timeline */
.timeline {
  position: relative;
  padding-left: 2rem;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 10px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: var(--eth-green);
}

.timeline-item {
  position: relative;
  margin-bottom: 1.5rem;
  padding-left: 1.5rem;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: -6px;
  top: 5px;
  width: 14px;
  height: 14px;
  border-radius: 50%;
  background: var(--eth-red);
  border: 3px solid white;
  box-shadow: 0 0 0 2px var(--eth-green);
}

/* Button Styles */
.btn--eth-green {
  background: linear-gradient(135deg, var(--eth-green), #0a6b2c);
  color: white !important;
  border: none;
}

.btn--eth-yellow {
  background: linear-gradient(135deg, var(--eth-yellow), #d4b800);
  color: #333 !important;
  border: none;
}

.btn--eth-red {
  background: linear-gradient(135deg, var(--eth-red), #b0151d);
  color: white !important;
  border: none;
}
</style>

<div class="main-content">
  <div class="content-left">
    <!-- Welcome Section -->
    <div class="modern-card">
      <h2 style="margin-top: 0; color: var(--eth-dark);">
        <i class="fas fa-handshake" style="color: var(--eth-green); margin-right: 10px;"></i>
        Welcome
      </h2>
      <p style="font-size: 1.1rem; line-height: 1.6;">
        I am <strong>Bedru Yimam Ahmed</strong> (በድሩ ይማም አህመድ), a passionate educator and researcher dedicated to advancing <strong>computer science education</strong> and <strong>technology innovation</strong> in Ethiopia. At <strong>Wollo University</strong>, I combine teaching with cutting-edge research to develop solutions tailored to our local context.
      </p>
    </div>

    <!-- Quick Stats -->
    <div class="stats-counter">
      <div class="stat-item">
        <span class="stat-number">5+</span>
        <span>Years Teaching</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">10+</span>
        <span>Publications</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">50+</span>
        <span>Students Mentored</span>
      </div>
    </div>

    <!-- Featured Research -->
    <div class="modern-card">
      <h3 style="color: var(--eth-dark); border-bottom: 2px solid var(--eth-yellow); padding-bottom: 0.5rem;">
        <i class="fas fa-star" style="color: var(--eth-yellow); margin-right: 10px;"></i>
        Featured Research
      </h3>
      
      <div class="pub-highlight">
        <div class="pub-year">2024</div>
        <div>
          <h4 style="margin: 0 0 0.5rem 0;">Machine Learning for Ethiopian Student Performance Prediction</h4>
          <p style="margin: 0; color: #666;">Developing predictive models using local student data to improve educational outcomes.</p>
          <div style="margin-top: 0.5rem;">
            <a href="#" class="btn btn--small btn--eth-green">Read Paper</a>
            <a href="#" class="btn btn--small">View Code</a>
          </div>
        </div>
      </div>

      <div class="pub-highlight">
        <div class="pub-year">2023</div>
        <div>
          <h4 style="margin: 0 0 0.5rem 0;">Amharic Natural Language Processing Toolkit</h4>
          <p style="margin: 0; color: #666;">Open-source tools for processing Ethiopian languages using state-of-the-art NLP techniques.</p>
          <div style="margin-top: 0.5rem;">
            <a href="#" class="btn btn--small btn--eth-green">Read Paper</a>
            <a href="#" class="btn btn--small">View Project</a>
          </div>
        </div>
      </div>
    </div>

    <!-- Current Courses -->
    <div class="modern-card">
      <h3 style="color: var(--eth-dark);">
        <i class="fas fa-book-open" style="color: var(--eth-green); margin-right: 10px;"></i>
        Current Courses at Wollo University
      </h3>
      
      <div class="feature-grid">
        <div class="feature-item">
          <i class="fas fa-laptop-code"></i>
          <h4>CSC 101</h4>
          <p>Introduction to Computer Science</p>
          <small>Fall 2024 · 120 Students</small>
        </div>
        
        <div class="feature-item">
          <i class="fas fa-project-diagram"></i>
          <h4>CSC 201</h4>
          <p>Data Structures & Algorithms</p>
          <small>Fall 2024 · 80 Students</small>
        </div>
        
        <div class="feature-item">
          <i class="fas fa-robot"></i>
          <h4>CSC 501</h4>
          <p>Machine Learning</p>
          <small>Graduate Course · 25 Students</small>
        </div>
      </div>
    </div>
  </div>

  <!-- Sidebar -->
  <div class="sidebar-right">
    <!-- Navigation -->
    <div class="modern-card">
      <h4 style="margin-top: 0; color: var(--eth-dark);">
        <i class="fas fa-compass" style="color: var(--eth-green); margin-right: 10px;"></i>
        Quick Navigation
      </h4>
      <nav class="sidebar-nav">
        <ul>
          <li><a href="/research/"><i class="fas fa-flask"></i> Research</a></li>
          <li><a href="/publications/"><i class="fas fa-file-alt"></i> Publications</a></li>
          <li><a href="/teaching/"><i class="fas fa-chalkboard-teacher"></i> Teaching</a></li>
          <li><a href="/projects/"><i class="fas fa-code-branch"></i> Projects</a></li>
          <li><a href="/talks/"><i class="fas fa-microphone"></i> Talks</a></li>
          <li><a href="/files/cv.pdf"><i class="fas fa-download"></i> Download CV</a></li>
          <li><a href="/about/#contact"><i class="fas fa-envelope"></i> Contact</a></li>
        </ul>
      </nav>
    </div>

    <!-- Research Timeline -->
    <div class="modern-card">
      <h4 style="margin-top: 0; color: var(--eth-dark);">
        <i class="fas fa-history" style="color: var(--eth-green); margin-right: 10px;"></i>
        Research Timeline
      </h4>
      <div class="timeline">
        <div class="timeline-item">
          <strong>2024</strong>
          <p>AI in Education Project Launch</p>
        </div>
        <div class="timeline-item">
          <strong>2023</strong>
          <p>Amharic NLP Toolkit v1.0</p>
        </div>
        <div class="timeline-item">
          <strong>2022</strong>
          <p>Joined Wollo University</p>
        </div>
        <div class="timeline-item">
          <strong>2021</strong>
          <p>PhD Research Begins</p>
        </div>
      </div>
    </div>

    <!-- Latest Updates -->
    <div class="modern-card">
      <h4 style="margin-top: 0; color: var(--eth-dark);">
        <i class="fas fa-bullhorn" style="color: var(--eth-green); margin-right: 10px;"></i>
        Latest Updates
      </h4>
      <div style="margin-top: 1rem;">
        {% for post in site.posts limit:3 %}
        <div style="margin-bottom: 1rem; padding-bottom: 1rem; border-bottom: 1px solid #eee;">
          <a href="{{ post.url }}" style="font-weight: 500; display: block;">{{ post.title }}</a>
          <small style="color: #666;">{{ post.date | date: "%b %d, %Y" }}</small>
        </div>
        {% endfor %}
      </div>
      <a href="/year-archive/" class="btn btn--small btn--eth-green" style="width: 100%; text-align: center;">
        View All Updates
      </a>
    </div>

    <!-- Collaboration Callout -->
    <div class="modern-card" style="background: linear-gradient(135deg, var(--eth-light), white); border-left-color: var(--eth-red);">
      <h4 style="margin-top: 0; color: var(--eth-dark);">
        <i class="fas fa-handshake" style="color: var(--eth-red); margin-right: 10px;"></i>
        Open to Collaboration
      </h4>
      <p style="font-size: 0.95rem;">
        I welcome partnerships with:
      </p>
      <ul style="font-size: 0.9rem; padding-left: 1.2rem;">
        <li>Researchers in AI/ML</li>
        <li>Ethiopian universities</li>
        <li>Industry partners</li>
        <li>International collaborators</li>
      </ul>
      <a href="/about/#contact" class="btn btn--small btn--eth-red" style="width: 100%; text-align: center; margin-top: 1rem;">
        <i class="fas fa-envelope"></i> Get in Touch
      </a>
    </div>
  </div>
</div>

<!-- JavaScript for Interactive Elements -->
<script>
// Add animation to stats counter
document.addEventListener('DOMContentLoaded', function() {
  // Animate stats counter
  const stats = document.querySelectorAll('.stat-number');
  stats.forEach(stat => {
    const target = parseInt(stat.textContent);
    let current = 0;
    const increment = target / 50;
    const timer = setInterval(() => {
      current += increment;
      if (current >= target) {
        current = target;
        clearInterval(timer);
      }
      stat.textContent = Math.floor(current) + '+';
    }, 30);
  });

  // Add smooth scrolling to sidebar links
  document.querySelectorAll('.sidebar-nav a').forEach(link => {
    link.addEventListener('click', function(e) {
      const href = this.getAttribute('href');
      if (href.startsWith('/') && !href.startsWith('/#')) {
        // Allow normal navigation
        return;
      }
    });
  });

  // Add hover effect to feature items
  document.querySelectorAll('.feature-item').forEach(item => {
    item.addEventListener('mouseenter', function() {
      this.style.transform = 'translateY(-5px)';
    });
    item.addEventListener('mouseleave', function() {
      this.style.transform = 'translateY(0)';
    });
  });
});
</script>

<!-- Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
