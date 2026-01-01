---
layout: splash
header:
  actions:
    - label: "View My CV"
      url: "/assets/documents/cv.pdf"
      btn_class: "btn--primary"
    - label: "Contact Me"
      url: "/contact/"
      btn_class: "btn--primary"
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

<div class="author__avatar" style="text-align: center; margin: 2rem auto;">
  <img src="images/bedru.jpg" alt="Bedru Yimam Ahmed" class="profile-image" style="width: 250px; height: 250px; border-radius: 50%; border: 5px solid #2e8b57; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);">
</div>

<div style="text-align: center; margin: 2rem 0; padding: 0 1rem;">
  <h1 style="margin-bottom: 0.5rem; color: #2c3e50;">Bedru Yimam Ahmed</h1>
  <h3 style="color: #2e8b57; margin-top: 0; margin-bottom: 0.5rem;">Lecturer & Researcher in Information Technology</h3>
  <p style="font-size: 1.1rem; color: #555;">
    <i class="fas fa-university" style="color: #2e8b57;"></i> Wollo University, Dessie, Ethiopia<br>
    <i class="fas fa-envelope" style="color: #2e8b57;"></i> bedruy4@gmail.com
  </p>
  
  <!-- Social Links (Inline) -->

  </div>

  <!-- About Me Section -->
  <section style="margin: 3rem 0 2rem 0; max-width: 800px; margin-left: auto; margin-right: auto;">
    <h2 style="color: #2e8b57; margin-bottom: 1.5rem; text-align: center;">About Me</h2>
    <p style="line-height: 1.6; color: #555; text-align: center;">
      I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia. 
      My research focuses on Artificial Intelligence, Machine Learning, and Computer Vision, 
      with applications addressing local and regional challenges. I am passionate about 
      technology education and research that contributes to sustainable development in Africa.
    </p>
  </section>

  <!-- Research Interests Section -->
  <section style="margin: 3rem 0;">
    <h2 style="color: #2e8b57; margin-bottom: 1.5rem; text-align: center;">Research Interests</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 0.8rem; margin: 1rem 0;">
      <span style="background: #e8f5e8; padding: 0.5rem 1rem; border-radius: 20px; color: #2e8b57; font-weight: 500;">
        <i class="fas fa-brain"></i> Artificial Intelligence
      </span>
      <span style="background: #e8f5e8; padding: 0.5rem 1rem; border-radius: 20px; color: #2e8b57; font-weight: 500;">
        <i class="fas fa-chart-line"></i> Machine Learning
      </span>
      <span style="background: #e8f5e8; padding: 0.5rem 1rem; border-radius: 20px; color: #2e8b57; font-weight: 500;">
        <i class="fas fa-eye"></i> Computer Vision
      </span>
      <span style="background: #e8f5e8; padding: 0.5rem 1rem; border-radius: 20px; color: #2e8b57; font-weight: 500;">
        <i class="fas fa-language"></i> Natural Language Processing
      </span>
      <span style="background: #e8f5e8; padding: 0.5rem 1rem; border-radius: 20px; color: #2e8b57; font-weight: 500;">
        <i class="fas fa-seedling"></i> AI for Development
      </span>
    </div>
  </section>
</div>

<!-- Call to Action Section -->
<div style="background:#e8f5e8; color: #2e8b57; padding: 3rem 1rem; text-align: center; margin-top: 3rem;">
  <h2 style="margin-top: 0; margin-bottom: 1rem;">Interested in Collaboration?</h2>
  <p style="max-width: 600px; margin: 0 auto 1.5rem auto; opacity: 0.9;">
    I welcome collaboration opportunities for research projects, student supervision, 
    and academic partnerships focused on technology and development in Ethiopia.
  </p>
  <a href="/contact/" class="btn btn--primary" style="background: black; color: #2e8b57; border: 2px solid #2e8b57; padding: 0.8rem 2rem; font-weight: 600; text-decoration: none; display: inline-block; border-radius: 30px;">
    Get In Touch <i class="fas fa-arrow-right"></i>
  </a>
</div>

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<!-- Add Academicons for academic icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<style>
/* Custom styles for splash page */
.btn--primary {
  background: white;
  color: #2e8b57;
  border: 2px solid #2e8b57;
  border-radius: 30px;
  padding: 0.8rem 2rem;
  font-weight: 600;
  transition: all 0.3s ease;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  text-decoration: none;
  display: inline-block;
}

.btn--primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(46, 139, 87, 0.3);
  background: #2e8b57;
  color: white;
}

/* Social Profiles Sidebar */
.social-sidebar {
  position: fixed;
  right: 30px;
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
  .author__avatar img {
    width: 200px;
    height: 200px;
  }
  
  /* Make research interest tags wrap better on mobile */
  .research-interests span {
    margin: 0.3rem;
  }
}
</style>
