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
  
  <!-- Left Column: Photo and Basic Info (Fixed Position) -->
  <div class="left-column">
    <div class="profile-card">
      <img src="/images/bedru.jpg" alt="Bedru Yimam Ahmed" class="profile-photo">
      
      <h1 class="profile-name">Bedru Yimam Ahmed</h1>
      <h3 class="profile-title">Lecturer & Researcher in Information Technology</h3>
      
      <p class="profile-info">
        <i class="fas fa-university"></i> Wollo University, Dessie, Ethiopia
      </p>
      <p class="profile-info">
        <i class="fas fa-envelope"></i> bedruy4@gmail.com
      </p>
      
      <!-- Quick Contact Buttons -->
      <div class="profile-buttons">
        <a href="/assets/documents/cv.pdf" class="btn btn--primary cv-btn">
          <i class="fas fa-download"></i> Download CV
        </a>
        <a href="/contact/" class="btn btn--primary contact-btn">
          <i class="fas fa-envelope"></i> Contact Me
        </a>
      </div>
    </div>
  </div>

  <!-- Right Column: Biography and Details (Centered Content) -->
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
/* Main Layout Structure */
.about-layout {
  display: grid;
  grid-template-columns: 350px 1fr;
  gap: 3rem;
  max-width: 1400px;
  margin: 2rem auto;
  padding: 0 2rem;
}

/* Left Column - Photo Section */
.left-column {
  position: sticky;
  top: 2rem;
  height: fit-content;
  align-self: start;
}

.profile-card {
  background: white;
  padding: 2rem;
  border-radius: 15px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
  text-align: center;
  border: 1px solid #e8f5e8;
}

.profile-photo {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  border: 5px solid #2e8b57;
  object-fit: cover;
  margin-bottom: 1.5rem;
  box-shadow: 0 4px 15px rgba(46, 139, 87, 0.15);
}

.profile-name {
  margin-bottom: 0.5rem;
  color: #2c3e50;
  font-size: 1.8rem;
}

.profile-title {
  color: #2e8b57;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.1rem;
  font-weight: 600;
}

.profile-info {
  font-size: 1rem;
  color: #555;
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
}

.profile-info i {
  color: #2e8b57;
  min-width: 20px;
}

.profile-buttons {
  margin: 1.5rem 0;
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
}

.btn--primary {
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  display: block;
  transition: all 0.3s ease;
  text-align: center;
}

.cv-btn {
  background: #2e8b57;
  color: white;
}

.contact-btn {
  background: white;
  color: #2e8b57;
  border: 2px solid #2e8b57;
}

.btn--primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(46, 139, 87, 0.3);
}

/* Right Column - Centered Content */
.right-column {
  max-width: 800px;
  margin: 0 auto;
}

.content-section {
  margin-bottom: 3rem;
}

.section-title {
  color: #2e8b57;
  margin-bottom: 1.5rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #e8f5e8;
  font-size: 1.8rem;
}

/* Biography Styling */
.biography-content {
  background: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 3px 15px rgba(0, 0, 0, 0.05);
}

.biography-content p {
  line-height: 1.7;
  color: #555;
  margin-bottom: 1rem;
  text-align: justify;
}

/* Education Styling */
.education-item {
  background: #f8f9fa;
  padding: 1.5rem;
  border-left: 4px solid #2e8b57;
  border-radius: 0 8px 8px 0;
  margin-bottom: 1.5rem;
}

.education-item:first-child {
  border-left-color: #3cb371;
}

.education-degree {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 0.8rem;
  font-size: 1.2rem;
}

.education-info {
  color: #555;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.education-info i {
  color: #2e8b57;
  min-width: 20px;
}

/* Research Focus */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 1rem;
}

.research-card {
  background: white;
  padding: 1.8rem;
  border-radius: 10px;
  box-shadow: 0 3px 15px rgba(0, 0, 0, 0.05);
  border-top: 4px solid #2e8b57;
  transition: transform 0.3s ease;
}

.research-card:nth-child(2) {
  border-top-color: #3cb371;
}

.research-card:hover {
  transform: translateY(-5px);
}

.research-card h3 {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.1rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.research-card i {
  color: #2e8b57;
}

.research-card:nth-child(2) i {
  color: #3cb371;
}

.research-card p {
  color: #555;
  line-height: 1.6;
  font-size: 0.95rem;
  margin: 0;
}

/* Academic Positions */
.position-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 10px;
}

.position-card h3 {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.position-info {
  color: #555;
  margin-bottom: 0.8rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.position-info i {
  color: #2e8b57;
  min-width: 20px;
}

.responsibilities-title {
  color: #3cb371;
  margin-top: 1.5rem;
  margin-bottom: 0.8rem;
  font-size: 1.1rem;
}

.responsibilities-list {
  color: #555;
  padding-left: 1.5rem;
  margin: 0;
}

.responsibilities-list li {
  margin-bottom: 0.5rem;
  line-height: 1.5;
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
  gap: 10px;
  background: rgba(255, 255, 255, 0.95);
  padding: 15px 10px;
  border-radius: 15px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(46, 139, 87, 0.2);
}

.social-sidebar a {
  width: 45px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  color: white;
  font-size: 1.2rem;
  transition: all 0.3s ease;
  text-decoration: none;
  position: relative;
}

.social-sidebar a:hover {
  transform: translateY(-3px) scale(1.1);
}

.social-sidebar a:hover::after {
  content: attr(title);
  position: absolute;
  right: 100%;
  top: 50%;
  transform: translateY(-50%);
  background: #2e8b57;
  color: white;
  padding: 5px 10px;
  border-radius: 4px;
  font-size: 0.8rem;
  white-space: nowrap;
  margin-right: 10px;
  opacity: 0.9;
}

.social-sidebar .github { background: #333; }
.social-sidebar .scholar { background: #4285f4; }
.social-sidebar .linkedin { background: #0077b5; }
.social-sidebar .orcid { background: #a6ce39; }
.social-sidebar .researchgate { background: #00d0af; }
.social-sidebar .email { background: #2e8b57; }

/* Responsive Design */
@media (max-width: 1100px) {
  .about-layout {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .left-column {
    position: static;
    max-width: 500px;
    margin: 0 auto;
  }
  
  .social-sidebar {
    position: static;
    transform: none;
    flex-direction: row;
    justify-content: center;
    margin: 2rem auto;
    width: 90%;
    max-width: 500px;
    padding: 15px;
  }
  
  .social-sidebar a {
    flex: 1;
    max-width: 45px;
  }
}

@media (max-width: 768px) {
  .about-layout {
    padding: 0 1rem;
  }
  
  .profile-photo {
    width: 200px;
    height: 200px;
  }
  
  .research-grid {
    grid-template-columns: 1fr;
  }
  
  .profile-buttons {
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .btn--primary {
    min-width: 200px;
  }
}

@media (max-width: 480px) {
  .profile-card {
    padding: 1.5rem;
  }
  
  .profile-name {
    font-size: 1.5rem;
  }
  
  .section-title {
    font-size: 1.5rem;
  }
  
  .biography-content,
  .education-item,
  .position-card {
    padding: 1.2rem;
  }
}
</style>
