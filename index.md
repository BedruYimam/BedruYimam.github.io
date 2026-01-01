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
  
  <!-- Social Links -->
  <div style="margin: 1.5rem 0;">
    <a href="https://github.com/BedruYimam" target="_blank" style="margin: 0 0.5rem; color: #333; font-size: 1.2rem;">
      <i class="fab fa-github"></i>
    </a>
    <a href="https://scholar.google.com/citations?user=YOUR_ID" target="_blank" style="margin: 0 0.5rem; color: #4285f4; font-size: 1.2rem;">
      <i class="ai ai-google-scholar"></i>
    </a>
    <a href="https://linkedin.com/in/yourprofile" target="_blank" style="margin: 0 0.5rem; color: #0077b5; font-size: 1.2rem;">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://orcid.org/YOUR_ORCID" target="_blank" style="margin: 0 0.5rem; color: #a6ce39; font-size: 1.2rem;">
      <i class="ai ai-orcid"></i>
    </a>
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
<div style="background: #1a5c36; color: whitegray; padding: 3rem 1rem; text-align: center; margin-top: 3rem;">
  <h2 style="margin-top: 0; margin-bottom: 1rem;">Interested in Collaboration?</h2>
  <p style="max-width: 600px; margin: 0 auto 1.5rem auto; opacity: 0.9;">
    I welcome collaboration opportunities for research projects, student supervision, 
    and academic partnerships focused on technology and development in Ethiopia.
  </p>
  <a href="/contact/" class="btn btn--primary" style="background: white; color: #1a5c36; border: none; padding: 0.8rem 2rem; font-weight: 600;">
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
  background: linear-gradient(135deg, #2e8b57 0%, #3cb371 100%);
  border: none;
  border-radius: 30px;
  padding: 0.8rem 2rem;
  font-weight: 600;
  transition: all 0.3s ease;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.btn--primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(46, 139, 87, 0.3);
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
