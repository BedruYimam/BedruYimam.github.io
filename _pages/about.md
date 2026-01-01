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
  padding: 20px;
  min-height: 100vh;
}

/* Main Container */
.about-main-container {
  display: flex !important;
  max-width: 1400px !important;
  margin: 0 auto !important;
  gap: 40px !important;
  align-items: flex-start !important;
  position: relative;
}

/* Left Column: Photo Section */
.about-left-column {
  flex: 0 0 320px !important;
  width: 320px !important;
  position: sticky !important;
  top: 30px !important;
  text-align: left !important;
  margin-left: -30 !important;
  align-self: flex-start !important;
}

.profile-image-container {
  margin-bottom: 25px !important;
}

.profile-image {
  width: 200px !important;
  height: 200px !important;
  border-radius: 50% !important;
  border: 8px solid #2e8b57 !important;
  object-fit: cover !important;
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15) !important;
}

.profile-header h1 {
  font-size: 32px !important;
  color: #2c3e50 !important;
  margin-bottom: 10px !important;
  font-weight: 700 !important;
  line-height: 1.2 !important;
  text-align: left !important;
}

.profile-header h2 {
  color: #2e8b57 !important;
  font-size: 20px !important;
  margin-bottom: 25px !important;
  font-weight: 600 !important;
  text-align: left !important;
}

.profile-details {
  margin: 25px 0 !important;
}

.profile-detail {
  display: flex !important;
  align-items: flex-start !important;
  gap: 12px !important;
  margin-bottom: 15px !important;
  color: #555 !important;
  font-size: 16px !important;
  text-align: left !important;
}

.profile-detail i {
  color: #2e8b57 !important;
  font-size: 18px !important;
  width: 24px !important;
  flex-shrink: 0 !important;
}

.profile-actions {
  margin-top: 30px !important;
  display: flex !important;
  flex-direction: column !important;
  gap: 15px !important;
  align-items: flex-start !important;
}

.btn {
  display: inline-block !important;
  padding: 14px 25px !important;
  text-align: center !important;
  text-decoration: none !important;
  border-radius: 50px !important;
  font-weight: 600 !important;
  font-size: 16px !important;
  transition: all 0.3s ease !important;
  border: 2px solid transparent !important;
  min-width: 200px !important;
}

.btn-cv {
  background: #2e8b57 !important;
  color: white !important;
}

.btn-cv:hover {
  background: #26734a !important;
  transform: translateY(-3px) !important;
  box-shadow: 0 10px 20px rgba(46, 139, 87, 0.2) !important;
}

.btn-contact {
  background: white !important;
  color: #2e8b57 !important;
  border-color: #2e8b57 !important;
}

.btn-contact:hover {
  background: #2e8b57 !important;
  color: white !important;
  transform: translateY(-3px) !important;
  box-shadow: 0 10px 20px rgba(46, 139, 87, 0.2) !important;
}

/* Middle Column: Biography Content */
.about-middle-column {
  flex: 1 !important;
  min-width: 0 !important;
  max-width: 800px !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
}

.content-section {
  margin-bottom: 50px !important;
}

.section-title {
  color: #2e8b57 !important;
  font-size: 28px !important;
  margin-bottom: 25px !important;
  padding-bottom: 10px !important;
  border-bottom: 3px solid #e8f5e8 !important;
  font-weight: 700 !important;
  text-align: left !important;
}

.biography-text {
  font-size: 18px !important;
  line-height: 1.8 !important;
  color: #444 !important;
  margin-bottom: 20px !important;
  text-align: left !important;
}

.biography-text p {
  margin-bottom: 20px !important;
}

/* Education Cards */
.education-cards {
  display: flex !important;
  flex-direction: column !important;
  gap: 20px !important;
}

.education-card {
  background: #f8f9fa !important;
  padding: 25px !important;
  border-radius: 10px !important;
  border-left: 5px solid !important;
  transition: transform 0.3s ease, box-shadow 0.3s ease !important;
  text-align: left !important;
}

.education-card:hover {
  transform: translateY(-5px) !important;
  box-shadow: 0 10px 20px rgba(0,0,0,0.1) !important;
}

.education-card.masters {
  border-left-color: #3cb371 !important;
}

.education-card.bachelors {
  border-left-color: #2e8b57 !important;
}

.education-degree {
  font-size: 20px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
  text-align: left !important;
}

.education-detail {
  display: flex !important;
  align-items: center !important;
  gap: 10px !important;
  margin-bottom: 8px !important;
  color: #555 !important;
  font-size: 16px !important;
  text-align: left !important;
}

.education-detail i {
  width: 20px !important;
  color: inherit !important;
  flex-shrink: 0 !important;
}

.education-card.masters .education-detail i {
  color: #3cb371 !important;
}

.education-card.bachelors .education-detail i {
  color: #2e8b57 !important;
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
  transition: transform 0.3s ease, box-shadow 0.3s ease !important;
  text-align: left !important;
}

.research-card:hover {
  transform: translateY(-5px) !important;
  box-shadow: 0 10px 25px rgba(0,0,0,0.1) !important;
}

.research-card.ai {
  border-top-color: #2e8b57 !important;
}

.research-card.ml {
  border-top-color: #3cb371 !important;
}

.research-card.nlp {
  border-top-color: #2e8b57 !important;
}

.research-title {
  display: flex !important;
  align-items: center !important;
  gap: 12px !important;
  font-size: 18px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
  text-align: left !important;
}

.research-title i {
  font-size: 22px !important;
  flex-shrink: 0 !important;
}

.research-card.ai .research-title i {
  color: #2e8b57 !important;
}

.research-card.ml .research-title i {
  color: #3cb371 !important;
}

.research-card.nlp .research-title i {
  color: #2e8b57 !important;
}

.research-description {
  color: #555 !important;
  line-height: 1.6 !important;
  font-size: 16px !important;
  margin: 0 !important;
  text-align: left !important;
}

/* Academic Position */
.position-card {
  background: #f8f9fa !important;
  padding: 25px !important;
  border-radius: 10px !important;
  text-align: left !important;
}

.position-title {
  font-size: 20px !important;
  color: #2c3e50 !important;
  margin-bottom: 15px !important;
  font-weight: 600 !important;
  text-align: left !important;
}

.responsibilities-title {
  color: #3cb371 !important;
  margin-top: 20px !important;
  margin-bottom: 10px !important;
  font-size: 18px !important;
  font-weight: 600 !important;
  text-align: left !important;
}

.responsibilities-list {
  padding-left: 20px !important;
  margin-top: 15px !important;
}

.responsibilities-list li {
  margin-bottom: 10px !important;
  color: #555 !important;
  line-height: 1.6 !important;
  text-align: left !important;
}

/* Social Icons - Fixed on RIGHT side */
.social-right-sidebar {
  position: fixed !important;
  right: 20px !important;
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

.github { background: #333 !important; }
.scholar { background: #4285f4 !important; }
.linkedin { background: #0077b5 !important; }
.orcid { background: #a6ce39 !important; }
.researchgate { background: #00d0af !important; }
.email { background: #2e8b57 !important; }

/* Responsive Design */
@media (max-width: 1400px) {
  .about-main-container {
    max-width: 1200px !important;
    gap: 40px !important;
  }
}

@media (max-width: 1200px) {
  .about-main-container {
    gap: 40px !important;
  }
  
  .about-left-column {
    flex: 0 0 280px !important;
    width: 280px !important;
  }
  
  .profile-image {
    width: 240px !important;
    height: 240px !important;
  }
  
  .btn {
    min-width: 180px !important;
  }
}

@media (max-width: 992px) {
  .about-main-container {
    flex-direction: column !important;
    gap: 40px !important;
  }
  
  .about-left-column {
    position: static !important;
    width: 100% !important;
    max-width: 500px !important;
    margin: 0 auto !important;
    text-align: center !important;
  }
  
  .profile-header h1,
  .profile-header h2,
  .profile-detail,
  .biography-text,
  .section-title,
  .education-degree,
  .research-title,
  .position-title,
  .responsibilities-title,
  .responsibilities-list li {
    text-align: center !important;
  }
  
  .profile-detail {
    justify-content: center !important;
  }
  
  .profile-actions {
    align-items: center !important;
  }
  
  .education-detail {
    justify-content: center !important;
  }
  
  .research-title {
    justify-content: center !important;
  }
  
  .profile-image {
    width: 250px !important;
    height: 250px !important;
  }
  
  .social-right-sidebar {
    position: fixed !important;
    top: 20px !important;
    left: 50% !important;
    right: auto !important;
    transform: translateX(-50%) !important;
    flex-direction: row !important;
    width: auto !important;
    background: rgba(255, 255, 255, 0.95) !important;
    backdrop-filter: blur(10px) !important;
  }
}

@media (max-width: 768px) {
  .about-page-wrapper {
    padding: 15px !important;
  }
  
  .profile-image {
    width: 220px !important;
    height: 220px !important;
  }
  
  .profile-header h1 {
    font-size: 28px !important;
  }
  
  .profile-header h2 {
    font-size: 18px !important;
  }
  
  .section-title {
    font-size: 24px !important;
  }
  
  .biography-text {
    font-size: 16px !important;
  }
  
  .research-grid {
    grid-template-columns: 1fr !important;
  }
  
  .social-right-sidebar {
    padding: 10px !important;
    gap: 8px !important;
  }
  
  .social-link {
    width: 40px !important;
    height: 40px !important;
    font-size: 16px !important;
  }
  
  .profile-actions {
    flex-direction: row !important;
    justify-content: center !important;
    flex-wrap: wrap !important;
    gap: 10px !important;
  }
  
  .btn {
    padding: 12px 20px !important;
    font-size: 14px !important;
    min-width: 160px !important;
  }
}

@media (max-width: 480px) {
  .profile-image {
    width: 200px !important;
    height: 200px !important;
  }
  
  .education-card,
  .research-card,
  .position-card {
    padding: 20px !important;
  }
  
  .profile-actions {
    flex-direction: column !important;
    width: 100% !important;
  }
  
  .btn {
    width: 100% !important;
    min-width: unset !important;
  }
  
  .social-right-sidebar {
    gap: 6px !important;
    padding: 8px !important;
  }
  
  .social-link {
    width: 35px !important;
    height: 35px !important;
    font-size: 14px !important;
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
  <!-- Social Sidebar - Fixed on RIGHT side -->
  <nav class="social-right-sidebar">
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
    <!-- Left Column: Photo Section -->
    <div class="about-left-column">
      <div class="profile-image-container">
        <img src="/images/bedru.jpg" alt="Bedru Yimam Ahmed" class="profile-image">
      </div>
      
      <div class="profile-header">
        <h1>Bedru Yimam Ahmed</h1>
        <h2>Lecturer & Researcher in Information Technology</h2>
      </div>
      
      <div class="profile-details">
        <div class="profile-detail">
          <i class="fas fa-university"></i>
          <span>Wollo University, Dessie, Ethiopia</span>
        </div>
        
        <div class="profile-detail">
          <i class="fas fa-envelope"></i>
          <span>bedruy4@gmail.com</span>
        </div>
      </div>
      
      <!-- Quick Contact Buttons -->
      <div class="profile-actions">
        <a href="/assets/documents/cv.pdf" class="btn btn-cv">
          <i class="fas fa-download"></i> Download CV
        </a>
        <a href="/contact/" class="btn btn-contact">
          <i class="fas fa-envelope"></i> Contact Me
        </a>
      </div>
    </div>

    <!-- Middle Column: Biography and Details -->
    <div class="about-middle-column">
      
      <!-- Biography Section -->
      <section class="content-section">
        <h2 class="section-title">Biography</h2>
        <div class="biography-text">
          <p>I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia, specializing in Artificial Intelligence, Machine Learning, and Computer Vision. My academic journey is driven by a passion for leveraging technology to address local and regional development challenges while contributing to the advancement of information Technology education in Ethiopia.</p>
          <p>With a strong commitment to both teaching and research, I strive to bridge the gap between theoretical knowledge and practical applications, preparing the next generation of Ethiopian technologists and researchers to tackle complex problems through innovative solutions.</p>
        </div>
      </section>

      <!-- Education Section -->
      <section class="content-section">
        <h2 class="section-title">Education</h2>
        
        <div class="education-cards">
          <div class="education-card masters">
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
          
          <div class="education-card bachelors">
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
        </div>
      </section>

      <!-- Research Focus -->
      <section class="content-section">
        <h2 class="section-title">Research Focus</h2>
        
        <div class="research-grid">
          <div class="research-card ai">
            <h3 class="research-title">
              <i class="fas fa-brain"></i>
              AI for Social Good
            </h3>
            <p class="research-description">
              Developing AI solutions for agriculture, healthcare, and education in Ethiopian contexts.
            </p>
          </div>
          
          <div class="research-card ml">
            <h3 class="research-title">
              <i class="fas fa-chart-line"></i>
              Machine Learning
            </h3>
            <p class="research-description">
              Algorithms for image analysis, predictive modeling, and natural language processing.
            </p>
          </div>
          
          <div class="research-card nlp">
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
          <div class="education-detail">
            <i class="fas fa-university"></i>
            <span>Wollo University, Dessie, Ethiopia</span>
          </div>
          <div class="education-detail">
            <i class="far fa-calendar-alt"></i>
            <span>[Start Year] - Present</span>
          </div>
          
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
    </div>
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
