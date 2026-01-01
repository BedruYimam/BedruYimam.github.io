---
layout: single
permalink: /about/
author_profile: false
classes: wide
---

<!-- Social Profiles Sidebar -->
<nav class="social-sidebar">
  <a href="https://github.com/BedruYimam" target="_blank" class="github" title="GitHub">
    <i class="fab fa-github"></i>
  </a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID" target="_blank" class="scholar" title="Google Scholar">
    <i class="ai ai-google-scholar"></i>
  </a>
  <a href="https://linkedin.com/in/yourprofile" target="_blank" class="linkedin" title="LinkedIn">
    <i class="fab fa-linkedin"></i>
  </a>
  <a href="https://orcid.org/YOUR_ORCID" target="_blank" class="orcid" title="ORCID">
    <i class="ai ai-orcid"></i>
  </a>
  <a href="https://www.researchgate.net/profile/YOUR_PROFILE" target="_blank" class="researchgate" title="ResearchGate">
    <i class="ai ai-researchgate"></i>
  </a>
  <a href="mailto:bedruy4@gmail.com" class="email" title="Email">
    <i class="fas fa-envelope"></i>
  </a>
</nav>

<div class="about-layout">
  <!-- Biography and Details (Centered Content) -->
  <div class="right-column">
    
    <!-- Biography Section -->
    <section class="content-section">
      <h2 class="section-title">Biography</h2>
      <div class="biography-content">
        <p>
          I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia, specializing in Artificial Intelligence, Machine Learning, and Computer Vision. My academic journey is driven by a passion for leveraging technology to address local and regional development challenges while contributing to the advancement of information Technology education in Ethiopia.
        </p>
        <p>
          With a strong commitment to both teaching and research, I strive to bridge the gap between theoretical knowledge and practical applications, preparing the next generation of Ethiopian technologists and researchers to tackle complex problems through innovative solutions.
        </p>
      </div>
    </section>

    <!-- Education Section -->
    <section class="content-section">
      <h2 class="section-title">Education</h2>
      
      <div class="education-item">
        <h3 class="education-degree">Master of Science (MSc) in Information Technology</h3>
        <p class="education-info">
          <i class="fas fa-university"></i> 
          BahirDar University, BahirDar, Ethiopia
        </p>
        <p class="education-info">
          <i class="far fa-calendar-alt"></i> 
          2019 - 2021 G.c
        </p>
        <p class="education-info">
          <i class="fas fa-graduation-cap"></i> 
          Thesis: Graph-based dependency parsing for Amharic Language using Deep Learning
        </p>
      </div>
      
      <div class="education-item">
        <h3 class="education-degree">Bachelor of Science (BSc) in Computer Science</h3>
        <p class="education-info">
          <i class="fas fa-university"></i> 
          Woldia University, Woldia, Ethiopia
        </p>
        <p class="education-info">
          <i class="far fa-calendar-alt"></i> 
          2013 - 2017 G.C
        </p>
      </div>
    </section>

    <!-- Research Focus -->
    <section class="content-section">
      <h2 class="section-title">Research Focus</h2>
      
      <div class="research-grid">
        <div class="research-card">
          <h3>
            <i class="fas fa-brain"></i>
            AI for Social Good
          </h3>
          <p>
            Developing AI solutions for agriculture, healthcare, and education in Ethiopian contexts.
          </p>
        </div>
        
        <div class="research-card">
          <h3>
            <i class="fas fa-chart-line"></i>
            Machine Learning
          </h3>
          <p>
            Algorithms for image analysis, predictive modeling, and natural language processing.
          </p>
        </div>
        
        <div class="research-card">
          <h3>
            <i class="fas fa-language"></i>
            NLP for Ethiopian Languages
          </h3>
          <p>
            Computational tools and resources for Amharic and other Ethiopian languages.
          </p>
        </div>
      </div>
    </section>

    <!-- Academic Positions -->
    <section class="content-section">
      <h2 class="section-title">Academic Positions</h2>
      
      <div class="position-card">
        <h3>Lecturer, Department of Computer Science</h3>
        <p class="position-info">
          <i class="fas fa-university"></i> 
          Wollo University, Dessie, Ethiopia
        </p>
        <p class="position-info">
          <i class="far fa-calendar-alt"></i> 
          [Start Year] - Present
        </p>
        
        <h4 class="responsibilities-title">Responsibilities:</h4>
        <ul class="responsibilities-list">
          <li>Teaching undergraduate and graduate courses in computer science</li>
          <li>Supervising student research projects and theses</li>
          <li>Developing curriculum and course materials</li>
          <li>Conducting research in AI and related fields</li>
          <li>Participating in departmental and university committees</li>
        </ul>
      </div>
    </section>

  </div> <!-- End of Right Column -->
</div> <!-- End of Layout -->

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<!-- Add Academicons for academic icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<style>
/* CSS Variables for Consistent Styling */
:root {
  --primary-color: #2e8b57;
  --secondary-color: #3cb371;
  --dark-color: #2c3e50;
  --text-color: #555;
  --light-bg: #f8f9fa;
  --white: #ffffff;
  --shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
  --shadow-light: 0 3px 15px rgba(0, 0, 0, 0.05);
  --border-radius: 10px;
  --transition: all 0.3s ease;
}

/* Main Layout Structure */
.about-layout {
  max-width: 1000px;
  margin: 2rem auto;
  padding: 0 2rem;
}

/* Centered Content Column */
.right-column {
  width: 100%;
}

.content-section {
  margin-bottom: 3rem;
  animation: fadeIn 0.5s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Section Titles */
.section-title {
  color: var(--primary-color);
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e8f5e8;
  font-size: 1.8rem;
  font-weight: 600;
  position: relative;
}

.section-title::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 60px;
  height: 2px;
  background: var(--secondary-color);
}

/* Biography Styling */
.biography-content {
  background: var(--white);
  padding: 2rem;
  border-radius: var(--border-radius);
  box-shadow: var(--shadow-light);
  border-left: 4px solid var(--primary-color);
}

.biography-content p {
  line-height: 1.7;
  color: var(--text-color);
  margin-bottom: 1rem;
  text-align: justify;
  font-size: 1.05rem;
}

.biography-content p:last-child {
  margin-bottom: 0;
}

/* Education Styling */
.education-item {
  background: var(--light-bg);
  padding: 1.8rem;
  border-left: 4px solid var(--primary-color);
  border-radius: 0 var(--border-radius) var(--border-radius) 0;
  margin-bottom: 1.5rem;
  transition: var(--transition);
}

.education-item:hover {
  transform: translateX(5px);
  box-shadow: var(--shadow);
}

.education-item:first-child {
  border-left-color: var(--secondary-color);
}

.education-degree {
  color: var(--dark-color);
  margin-top: 0;
  margin-bottom: 0.8rem;
  font-size: 1.2rem;
  font-weight: 600;
}

.education-info {
  color: var(--text-color);
  margin-bottom: 0.5rem;
  display: flex;
  align-items: flex-start;
  gap: 0.5rem;
  font-size: 1rem;
}

.education-info i {
  color: var(--primary-color);
  min-width: 20px;
  margin-top: 0.2rem;
}

/* Research Focus */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 1rem;
}

.research-card {
  background: var(--white);
  padding: 2rem;
  border-radius: var(--border-radius);
  box-shadow: var(--shadow-light);
  border-top: 4px solid var(--primary-color);
  transition: var(--transition);
  display: flex;
  flex-direction: column;
  height: 100%;
}

.research-card:nth-child(2) {
  border-top-color: var(--secondary-color);
}

.research-card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow);
}

.research-card h3 {
  color: var(--dark-color);
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.2rem;
  display: flex;
  align-items: center;
  gap: 0.8rem;
  font-weight: 600;
}

.research-card i {
  color: var(--primary-color);
  font-size: 1.3rem;
}

.research-card:nth-child(2) i {
  color: var(--secondary-color);
}

.research-card p {
  color: var(--text-color);
  line-height: 1.6;
  font-size: 1rem;
  margin: 0;
  flex-grow: 1;
}

/* Academic Positions */
.position-card {
  background: var(--light-bg);
  padding: 2rem;
  border-radius: var(--border-radius);
  border: 1px solid rgba(46, 139, 87, 0.1);
}

.position-card h3 {
  color: var(--dark-color);
  margin-top: 0;
  margin-bottom: 1.2rem;
  font-size: 1.4rem;
  font-weight: 600;
}

.position-info {
  color: var(--text-color);
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
  gap: 0.8rem;
  font-size: 1.05rem;
}

.position-info i {
  color: var(--primary-color);
  min-width: 24px;
  text-align: center;
}

.responsibilities-title {
  color: var(--secondary-color);
  margin-top: 1.8rem;
  margin-bottom: 1rem;
  font-size: 1.2rem;
  font-weight: 600;
}

.responsibilities-list {
  color: var(--text-color);
  padding-left: 1.5rem;
  margin: 0;
}

.responsibilities-list li {
  margin-bottom: 0.8rem;
  line-height: 1.6;
  position: relative;
  padding-left: 0.5rem;
}

.responsibilities-list li::before {
  content: '▸';
  color: var(--primary-color);
  position: absolute;
  left: -1.2rem;
  font-weight: bold;
}

/* Social Profiles Sidebar */
.social-sidebar {
  position: fixed;
  right: 20px;
  top: 50%;
  transform: translateY(-50%);
  z-index: 100;
  display: flex;
  flex-direction: column;
  gap: 12px;
  background: rgba(255, 255, 255, 0.95);
  padding: 15px 12px;
  border-radius: 15px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(46, 139, 87, 0.2);
}

.social-sidebar a {
  width: 48px;
  height: 48px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  color: white;
  font-size: 1.3rem;
  transition: var(--transition);
  text-decoration: none;
  position: relative;
}

.social-sidebar a:hover {
  transform: translateY(-3px) scale(1.1);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

.social-sidebar a:hover::after {
  content: attr(title);
  position: absolute;
  right: 100%;
  top: 50%;
  transform: translateY(-50%);
  background: var(--primary-color);
  color: white;
  padding: 6px 12px;
  border-radius: 6px;
  font-size: 0.85rem;
  white-space: nowrap;
  margin-right: 12px;
  opacity: 0.95;
  font-weight: 500;
  z-index: 101;
}

.social-sidebar a:hover::before {
  content: '';
  position: absolute;
  right: 100%;
  top: 50%;
  transform: translateY(-50%);
  border-left: 6px solid var(--primary-color);
  border-top: 6px solid transparent;
  border-bottom: 6px solid transparent;
  margin-right: 6px;
  z-index: 101;
}

.social-sidebar .github { background: #333; }
.social-sidebar .scholar { background: #4285f4; }
.social-sidebar .linkedin { background: #0077b5; }
.social-sidebar .orcid { background: #a6ce39; }
.social-sidebar .researchgate { background: #00d0af; }
.social-sidebar .email { background: var(--primary-color); }

/* Responsive Design */
@media (max-width: 1100px) {
  .about-layout {
    padding: 0 1.5rem;
  }
  
  .social-sidebar {
    position: static;
    transform: none;
    flex-direction: row;
    justify-content: center;
    margin: 2rem auto;
    width: 90%;
    max-width: 600px;
    padding: 15px;
    border-radius: 50px;
  }
  
  .social-sidebar a {
    width: 45px;
    height: 45px;
    font-size: 1.2rem;
  }
}

@media (max-width: 768px) {
  .about-layout {
    padding: 0 1rem;
    margin: 1rem auto;
  }
  
  .section-title {
    font-size: 1.6rem;
  }
  
  .research-grid {
    grid-template-columns: 1fr;
    gap: 1rem;
  }
  
  .biography-content,
  .education-item,
  .position-card,
  .research-card {
    padding: 1.5rem;
  }
  
  .social-sidebar {
    border-radius: 25px;
    padding: 12px;
    gap: 8px;
  }
  
  .social-sidebar a {
    width: 40px;
    height: 40px;
    font-size: 1.1rem;
  }
}

@media (max-width: 480px) {
  .about-layout {
    padding: 0 0.8rem;
  }
  
  .section-title {
    font-size: 1.4rem;
  }
  
  .biography-content,
  .education-item,
  .position-card {
    padding: 1.2rem;
  }
  
  .education-degree {
    font-size: 1.1rem;
  }
  
  .education-info,
  .position-info {
    font-size: 0.95rem;
  }
  
  .research-card h3 {
    font-size: 1.1rem;
  }
  
  .research-card p {
    font-size: 0.95rem;
  }
}
</style>
