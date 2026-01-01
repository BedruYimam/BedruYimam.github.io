---
layout: single
permalink: /about/
author_profile: false
classes: wide
---

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<style>
/* RESET AND OVERRIDE ANY CONFLICTING STYLES */
.about-page-wrapper * {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.about-page-wrapper {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

/* Main Container - Force Layout */
.about-main-container {
  display: flex !important;
  max-width: 1400px !important;
  margin: 0 auto !important;
  padding: 40px 20px !important;
  gap: 60px !important;
  min-height: 100vh;
  position: relative;
}

/* Left Sidebar - Social Icons */
.social-left-sidebar {
  position: fixed !important;
  left: 20px !important;
  top: 50% !important;
  transform: translateY(-50%) !important;
  z-index: 1000 !important;
  display: flex !important;
  flex-direction: column !important;
  gap: 12px !important;
  background: white !important;
  padding: 15px !important;
  border-radius: 15px !important;
  box-shadow: 0 5px 20px rgba(0,0,0,0.1) !important;
  border: 1px solid #eaeaea !important;
}

.social-link {
  width: 50px !important;
  height: 50px !important;
  display: flex !important;
  align-items: center !important;
  justify-content: center !important;
  border-radius: 50% !important;
  color: white !important;
  font-size: 20px !important;
  text-decoration: none !important;
  transition: all 0.3s ease !important;
}

.social-link:hover {
  transform: scale(1.1) !important;
  box-shadow: 0 5px 15px rgba(0,0,0,0.2) !important;
}

/* Photo Section - Clean without card */
.about-photo-section {
  flex: 0 0 320px !important;
  width: 320px !important;
  position: sticky !important;
  top: 40px !important;
  height: fit-content !important;
  text-align: center !important;
  padding: 20px !important;
}

.profile-image {
  width: 250px !important;
  height: 250px !important;
  border-radius: 50% !important;
  border: 6px solid #2e8b57 !important;
  margin: 0 auto 25px !important;
  display: block !important;
  object-fit: cover !important;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1) !important;
}

.profile-name {
  font-size: 28px !important;
  color: #2c3e50 !important;
  margin-bottom: 10px !important;
  font-weight: 700 !important;
  line-height: 1.2 !important;
}

.profile-title {
  color: #2e8b57 !important;
  font-size: 18px !important;
  margin-bottom: 20px !important;
  font-weight: 600 !important;
}

.profile-detail {
  display: flex !important;
  align-items: center !important;
  justify-content: center !important;
  gap: 10px !important;
  margin-bottom: 15px !important;
  color: #555 !important;
  font-size: 16px !important;
}

.profile-detail i {
  color: #2e8b57 !important;
  width: 20px !important;
}

.contact-buttons {
  display: flex !important;
  flex-direction: column !important;
  gap: 15px !important;
  margin-top: 25px !important;
}

.btn {
  display: block !important;
  padding: 14px !important;
  text-align: center !important;
  text-decoration: none !important;
  border-radius: 50px !important;
  font-weight: 600 !important;
  font-size: 16px !important;
  transition: all 0.3s ease !important;
  border: 2px solid transparent !important;
}

.btn-cv {
  background: #2e8b57 !important;
  color: white !important;
}

.btn-contact {
  background: white !important;
  color: #2e8b57 !important;
  border-color: #2e8b57 !important;
}

.btn:hover {
  transform: translateY(-3px) !important;
  box-shadow: 0 10px 20px rgba(46, 139, 87, 0.2) !important;
}

/* Content Area - Middle */
.about-content-area {
  flex: 1 !important;
  min-width: 0 !important;
  max-width: 800px !important;
  margin: 0 auto !important;
}

.section {
  margin-bottom: 50px !important;
}

.section-title {
  color: #2e8b57 !important;
  font-size: 28px !important;
  margin-bottom: 25px !important;
  padding-bottom: 10px !important;
  border-bottom: 3px solid #e8f5e8 !important;
  font-weight: 700 !important;
}

/* Biography Text */
.biography-text {
  font-size: 18px !important;
  line-height: 1.8 !important;
  color: #444 !important;
  text-align: justify !important;
  margin-bottom: 20px !important;
}

.biography-text p {
  margin-bottom: 20px !important;
}

/* Education Cards */
.education-card {
  background: #f8f9fa !important;
  padding: 25px !important;
  border-radius: 10px !important;
  margin-bottom: 20px !important;
  border-left: 5px solid !important;
}

.education-degree {
  font-size: 20px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
}

.education-detail {
  display: flex !important;
  align-items: center !important;
  gap: 10px !important;
  margin-bottom: 8px !important;
  color: #555 !important;
  font-size: 16px !important;
}

/* Research Grid */
.research-grid {
  display: grid !important;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)) !important;
  gap: 20px !important;
  margin-top: 20px !important;
}

.research-card {
  background: white !important;
  padding: 25px !important;
  border-radius: 10px !important;
  box-shadow: 0 5px 15px rgba(0,0,0,0.05) !important;
  border-top: 4px solid !important;
  transition: transform 0.3s ease !important;
}

.research-card:hover {
  transform: translateY(-5px) !important;
}

.research-title {
  display: flex !important;
  align-items: center !important;
  gap: 12px !important;
  font-size: 18px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
}

.research-title i {
  font-size: 22px !important;
}

/* Academic Position */
.position-card {
  background: #f8f9fa !important;
  padding: 25px !important;
  border-radius: 10px !important;
}

.position-title {
  font-size: 20px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
}

.responsibilities-list {
  padding-left: 20px !important;
  margin-top: 15px !important;
}

.responsibilities-list li {
  margin-bottom: 10px !important;
  color: #555 !important;
}

/* Color classes for social icons */
.github { background: #333 !important; }
.scholar { background: #4285f4 !important; }
.linkedin { background: #0077b5 !important; }
.orcid { background: #a6ce39 !important; }
.researchgate { background: #00d0af !important; }
.email { background: #2e8b57 !important; }

/* Right Space Column */
.about-space-column {
  flex: 0 0 320px !important;
  min-width: 320px !important;
}

/* Responsive Design */
@media (max-width: 1400px) {
  .about-space-column {
    display: none !important;
  }
  
  .about-main-container {
    gap: 40px !important;
  }
}

@media (max-width: 1200px) {
  .about-main-container {
    flex-direction: column !important;
    gap: 40px !important;
    padding-top: 80px !important;
  }
  
  .about-photo-section {
    position: static !important;
    width: 100% !important;
    max-width: 500px !important;
    margin: 0 auto !important;
    order: 1 !important;
  }
  
  .social-left-sidebar {
    position: fixed !important;
    top: 20px !important;
    left: 50% !important;
    transform: translateX(-50%) !important;
    flex-direction: row !important;
    width: auto !important;
    background: rgba(255, 255, 255, 0.95) !important;
    backdrop-filter: blur(10px) !important;
  }
  
  .about-content-area {
    order: 2 !important;
  }
}

@media (max-width: 768px) {
  .about-main-container {
    padding: 20px 15px !important;
    padding-top: 100px !important;
  }
  
  .social-left-sidebar {
    padding: 10px !important;
    gap: 8px !important;
  }
  
  .social-link {
    width: 40px !important;
    height: 40px !important;
    font-size: 16px !important;
  }
  
  .profile-image {
    width: 200px !important;
    height: 200px !important;
  }
  
  .profile-name {
    font-size: 24px !important;
  }
  
  .section-title {
    font-size: 24px !important;
  }
  
  .biography-text {
    font-size: 16px !important;
    text-align: left !important;
  }
  
  .research-grid {
    grid-template-columns: 1fr !important;
  }
  
  .contact-buttons {
    flex-direction: column !important;
  }
  
  .btn {
    width: 100% !important;
  }
}

/* Force text to flow properly */
p, h1, h2, h3, h4, h5, h6, div, span {
  white-space: normal !important;
  word-break: normal !important;
  overflow-wrap: normal !important;
}
</style>

<div class="about-page-wrapper">
  <!-- Social Sidebar - LEFT SIDE -->
  <nav class="social-left-sidebar">
    <a href="https://github.com/BedruYimam" target="_blank" class="social-link github" title="GitHub">
      <i class="fab fa-github"></i>
    </a>
    <a href="https://scholar.google.com/citations?user=YOUR_ID" target="_blank" class="social-link scholar" title="Google Scholar">
      <i class="ai ai-google-scholar"></i>
    </a>
    <a href="https://linkedin.com/in/yourprofile" target="_blank" class="social-link linkedin" title="LinkedIn">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://orcid.org/YOUR_ORCID" target="_blank" class="social-link orcid" title="ORCID">
      <i class="ai ai-orcid"></i>
    </a>
    <a href="https://www.researchgate.net/profile/YOUR_PROFILE" target="_blank" class="social-link researchgate" title="ResearchGate">
      <i class="ai ai-researchgate"></i>
    </a>
    <a href="mailto:bedruy4@gmail.com" class="social-link email" title="Email">
      <i class="fas fa-envelope"></i>
    </a>
  </nav>

  <div class="about-main-container">
    <!-- Left Column: Photo Section (no card) -->
    <div class="about-photo-section">
      <img src="/images/bedru.jpg" alt="Bedru Yimam Ahmed" class="profile-image">
      
      <h1 class="profile-name">Bedru Yimam Ahmed</h1>
      <h3 class="profile-title">Lecturer & Researcher in Information Technology</h3>
      
      <div class="profile-detail">
        <i class="fas fa-university"></i>
        <span>Wollo University, Dessie, Ethiopia</span>
      </div>
      
      <div class="profile-detail">
        <i class="fas fa-envelope"></i>
        <span>bedruy4@gmail.com</span>
      </div>
      
      <!-- Quick Contact Buttons -->
      <div class="contact-buttons">
        <a href="/assets/documents/cv.pdf" class="btn btn-cv">
          <i class="fas fa-download"></i> Download CV
        </a>
        <a href="/contact/" class="btn btn-contact">
          <i class="fas fa-envelope"></i> Contact Me
        </a>
      </div>
    </div>

    <!-- Middle Column: Biography and Details -->
    <div class="about-content-area">
      
      <section class="section">
        <h2 class="section-title">Biography</h2>
        <div class="biography-text">
          <p>I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia, specializing in Artificial Intelligence, Machine Learning, and Computer Vision. My academic journey is driven by a passion for leveraging technology to address local and regional development challenges while contributing to the advancement of information Technology education in Ethiopia.</p>
          <p>With a strong commitment to both teaching and research, I strive to bridge the gap between theoretical knowledge and practical applications, preparing the next generation of Ethiopian technologists and researchers to tackle complex problems through innovative solutions.</p>
        </div>
      </section>

      <!-- Education Section -->
      <section class="section">
        <h2 class="section-title">Education</h2>
        
        <div class="education-card" style="border-left-color: #3cb371;">
          <h3 class="education-degree">Master of Science (MSc) in Information Technology</h3>
          <div class="education-detail">
            <i class="fas fa-university"></i>
            <span>BahirDar University, BahirDar, Ethiopia</span>
          </div>
          <div class="education-detail">
            <i class="far fa-calendar-alt"></i>
            <span>2019 - 2021 G.c</span>
          </div>
          <div class="education-detail">
            <i class="fas fa-graduation-cap"></i>
            <span>Thesis: Graph-based dependency parsing for Amharic Language using Deep Learning</span>
          </div>
        </div>
        
        <div class="education-card" style="border-left-color: #2e8b57;">
          <h3 class="education-degree">Bachelor of Science (BSc) in Computer Science</h3>
          <div class="education-detail">
            <i class="fas fa-university"></i>
            <span>Woldia University, Woldia, Ethiopia</span>
          </div>
          <div class="education-detail">
            <i class="far fa-calendar-alt"></i>
            <span>2013 - 2017 G.C</span>
          </div>
        </div>
      </section>

      <!-- Research Focus -->
      <section class="section">
        <h2 class="section-title">Research Focus</h2>
        
        <div class="research-grid">
          <div class="research-card" style="border-top-color: #2e8b57;">
            <h3 class="research-title">
              <i class="fas fa-brain"></i>
              AI for Social Good
            </h3>
            <p class="biography-text" style="font-size: 16px; margin: 0;">
              Developing AI solutions for agriculture, healthcare, and education in Ethiopian contexts.
            </p>
          </div>
          
          <div class="research-card" style="border-top-color: #3cb371;">
            <h3 class="research-title">
              <i class="fas fa-chart-line"></i>
              Machine Learning
            </h3>
            <p class="biography-text" style="font-size: 16px; margin: 0;">
              Algorithms for image analysis, predictive modeling, and natural language processing.
            </p>
          </div>
          
          <div class="research-card" style="border-top-color: #2e8b57;">
            <h3 class="research-title">
              <i class="fas fa-language"></i>
              NLP for Ethiopian Languages
            </h3>
            <p class="biography-text" style="font-size: 16px; margin: 0;">
              Computational tools and resources for Amharic and other Ethiopian languages.
            </p>
          </div>
        </div>
      </section>

      <!-- Academic Positions -->
      <section class="section">
        <h2 class="section-title">Academic Positions</h2>
        
        <div class="position-card">
          <h3 class="position-title">
            Lecturer, Department of Computer Science
          </h3>
          <div class="education-detail">
            <i class="fas fa-university"></i>
            <span>Wollo University, Dessie, Ethiopia</span>
          </div>
          <div class="education-detail">
            <i class="far fa-calendar-alt"></i>
            <span>[Start Year] - Present</span>
          </div>
          
          <h4 style="color: #3cb371; margin-top: 20px; margin-bottom: 10px; font-size: 18px;">Responsibilities:</h4>
          <ul class="responsibilities-list">
            <li>Teaching undergraduate and graduate courses in computer science</li>
            <li>Supervising student research projects and theses</li>
            <li>Developing curriculum and course materials</li>
            <li>Conducting research in AI and related fields</li>
            <li>Participating in departmental and university committees</li>
          </ul>
        </div>
      </section>
    </div>
    
    <!-- Right Space Column for balance -->
    <div class="about-space-column"></div>
  </div>
</div>

<script>
// Force layout recalculation on load
document.addEventListener('DOMContentLoaded', function() {
  // Force reflow to fix any layout issues
  document.body.style.display = 'none';
  document.body.offsetHeight; // Trigger reflow
  document.body.style.display = '';
  
  // Ensure text flows properly
  const textElements = document.querySelectorAll('p, h1, h2, h3, h4, h5, h6, div, span');
  textElements.forEach(el => {
    el.style.whiteSpace = 'normal';
    el.style.wordBreak = 'normal';
    el.style.overflowWrap = 'normal';
  });
});
</script>
