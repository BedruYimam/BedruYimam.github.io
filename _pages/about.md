---
layout: single
permalink: /about/
author_profile: false  # Changed to false to customize layout
classes: wide
---

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<!-- Add Academicons for academic icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

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

<div class="about-container">
  <!-- Left Column: Photo and Basic Info -->
  <div class="about-photo-column">
    <div class="photo-sticky-wrapper">
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
        <a href="/assets/documents/cv.pdf" class="btn btn--primary btn--cv">
          <i class="fas fa-download"></i> Download CV
        </a>
        <a href="/contact/" class="btn btn--primary btn--contact">
          <i class="fas fa-envelope"></i> Contact Me
        </a>
      </div>
    </div>
  </div>

  <!-- Middle Column: Biography and Details -->
  <div class="about-content-column">
    
    <section class="content-section">
      <h2 class="section-title">Biography</h2>
      <p class="biography-text">
        I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia, specializing in Artificial Intelligence, Machine Learning, and Computer Vision. My academic journey is driven by a passion for leveraging technology to address local and regional development challenges while contributing to the advancement of information Technology education in Ethiopia.
      </p>
      <p class="biography-text">
        With a strong commitment to both teaching and research, I strive to bridge the gap between theoretical knowledge and practical applications, preparing the next generation of Ethiopian technologists and researchers to tackle complex problems through innovative solutions.
      </p>
    </section>

    <!-- Education Section -->
    <section class="content-section">
      <h2 class="section-title">Education</h2>
      
      <div class="education-card card--masters">
        <h3 class="education-degree">Master of Science (MSc) in Information Technology</h3>
        <p class="education-detail">
          <i class="fas fa-university"></i> 
          BahirDar University, BahirDar, Ethiopia
        </p>
        <p class="education-detail">
          <i class="far fa-calendar-alt"></i> 
          2019 - 2021 G.c
        </p>
        <p class="education-detail">
          <i class="fas fa-graduation-cap"></i> 
          Thesis: Graph-based dependency parsing for Amharic Language using Deep Learning
        </p>
      </div>
      
      <div class="education-card card--bachelors">
        <h3 class="education-degree">Bachelor of Science (BSc) in Computer Science</h3>
        <p class="education-detail">
          <i class="fas fa-university"></i> 
          Woldia University, Woldia, Ethiopia
        </p>
        <p class="education-detail">
          <i class="far fa-calendar-alt"></i> 
          2013 - 2017 G.C
        </p>
      </div>
    </section>

    <!-- Research Focus -->
    <section class="content-section">
      <h2 class="section-title">Research Focus</h2>
      
      <div class="research-grid">
        <div class="research-card card--ai">
          <h3 class="research-title">
            <i class="fas fa-brain"></i>
            AI for Social Good
          </h3>
          <p class="research-description">
            Developing AI solutions for agriculture, healthcare, and education in Ethiopian contexts.
          </p>
        </div>
        
        <div class="research-card card--ml">
          <h3 class="research-title">
            <i class="fas fa-chart-line"></i>
            Machine Learning
          </h3>
          <p class="research-description">
            Algorithms for image analysis, predictive modeling, and natural language processing.
          </p>
        </div>
        
        <div class="research-card card--nlp">
          <h3 class="research-title">
            <i class="fas fa-language"></i>
            NLP for Ethiopian Languages
          </h3>
          <p class="research-description">
            Computational tools and resources for Amharic and other Ethiopian languages.
          </p>
        </div>
      </div>
    </section>

    <!-- Academic Positions -->
    <section class="content-section">
      <h2 class="section-title">Academic Positions</h2>
      
      <div class="position-card">
        <h3 class="position-title">
          Lecturer, Department of Computer Science
        </h3>
        <p class="position-detail">
          <i class="fas fa-university"></i> 
          Wollo University, Dessie, Ethiopia
        </p>
        <p class="position-detail">
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
  </div> <!-- End of Middle Column -->

  <!-- Right empty space for balance -->
  <div class="about-space-column"></div>
</div> <!-- End of Container -->

<style>
/* Main Container */
.about-container {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  flex-wrap: nowrap;
  gap: 4rem;
}

/* Left Photo Column */
.about-photo-column {
  flex: 0 0 300px;
  min-width: 300px;
}

.photo-sticky-wrapper {
  position: sticky;
  top: 2rem;
  text-align: center;
  padding: 1.5rem;
  background: white;
  border-radius: 15px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
}

.profile-photo {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  border: 5px solid #2e8b57;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
  margin-bottom: 1.5rem;
  object-fit: cover;
}

.profile-name {
  margin-bottom: 0.5rem;
  color: #2c3e50;
  font-size: 1.8rem;
}

.profile-title {
  color: #2e8b57;
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
  font-weight: 600;
}

.profile-info {
  font-size: 1.1rem;
  color: #555;
  margin-bottom: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
}

.profile-info i {
  color: #2e8b57;
  width: 20px;
}

.profile-buttons {
  margin: 1.5rem 0;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.btn {
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  display: inline-block;
  text-align: center;
  transition: all 0.3s ease;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.btn--cv {
  background: #2e8b57;
  color: white;
  border: 2px solid #2e8b57;
}

.btn--contact {
  background: white;
  color: #2e8b57;
  border: 2px solid #2e8b57;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(46, 139, 87, 0.3);
}

/* Middle Content Column */
.about-content-column {
  flex: 1;
  min-width: 0;
  max-width: 800px;
  margin: 0 auto;
}

.content-section {
  margin-bottom: 2.5rem;
}

.section-title {
  color: #2e8b57;
  margin-bottom: 1.5rem;
  border-bottom: 2px solid #e8f5e8;
  padding-bottom: 0.5rem;
}

.biography-text {
  line-height: 1.6;
  color: #555;
  text-align: justify;
  margin-bottom: 1rem;
}

/* Education Cards */
.education-card {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 0 8px 8px 0;
  margin-bottom: 1rem;
}

.card--masters {
  border-left: 4px solid #3cb371;
}

.card--bachelors {
  border-left: 4px solid #2e8b57;
}

.education-degree {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.3rem;
}

.education-detail {
  color: #555;
  margin-bottom: 0.3rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.education-detail i {
  width: 20px;
}

.card--masters .education-detail i {
  color: #3cb371;
}

.card--bachelors .education-detail i {
  color: #2e8b57;
}

/* Research Grid */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin-top: 1rem;
}

.research-card {
  background: white;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}

.research-card:hover {
  transform: translateY(-5px);
}

.card--ai {
  border-top: 4px solid #2e8b57;
}

.card--ml {
  border-top: 4px solid #3cb371;
}

.card--nlp {
  border-top: 4px solid #2e8b57;
}

.research-title {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 1.2rem;
}

.research-title i {
  font-size: 1.3rem;
}

.card--ai .research-title i {
  color: #2e8b57;
}

.card--ml .research-title i {
  color: #3cb371;
}

.card--nlp .research-title i {
  color: #2e8b57;
}

.research-description {
  color: #555;
  line-height: 1.5;
  font-size: 0.95rem;
  margin: 0;
}

/* Academic Position */
.position-card {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
}

.position-title {
  color: #2c3e50;
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.3rem;
}

.position-detail {
  color: #555;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.position-detail i {
  color: #2e8b57;
  width: 20px;
}

.responsibilities-title {
  color: #3cb371;
  margin-top: 1rem;
  margin-bottom: 0.5rem;
}

.responsibilities-list {
  color: #555;
  padding-left: 1.5rem;
  margin: 0;
}

.responsibilities-list li {
  margin-bottom: 0.5rem;
}

/* Right Space Column */
.about-space-column {
  flex: 0 0 300px;
  min-width: 300px;
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
@media (max-width: 1400px) {
  .about-container {
    gap: 3rem;
  }
}

@media (max-width: 1200px) {
  .about-container {
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .about-photo-column {
    flex: 0 0 100%;
    margin-bottom: 2rem;
  }
  
  .about-content-column {
    flex: 1;
    min-width: 100%;
  }
  
  .about-space-column {
    display: none;
  }
  
  .photo-sticky-wrapper {
    position: static;
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 500px;
    margin: 0 auto;
  }
  
  .profile-photo {
    width: 200px;
    height: 200px;
  }
  
  .profile-buttons {
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
  }
}

@media (max-width: 1100px) {
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
  .about-container {
    padding: 0 1rem;
    gap: 2rem;
  }
  
  .profile-photo {
    width: 180px;
    height: 180px;
  }
  
  .profile-name {
    font-size: 1.5rem;
  }
  
  .profile-title {
    font-size: 1.1rem;
  }
  
  .profile-buttons {
    flex-direction: column;
    width: 100%;
  }
  
  .btn {
    width: 100%;
    margin-bottom: 0.5rem;
  }
  
  .research-grid {
    grid-template-columns: 1fr;
  }
  
  .section-title {
    font-size: 1.5rem;
  }
}
</style>
