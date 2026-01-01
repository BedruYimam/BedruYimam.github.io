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
feature_row:
  - title: "Research"
    excerpt: "Exploring AI, Machine Learning, and Computer Vision applications"
    url: "/research/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
  - title: "Teaching"
    excerpt: "Computer Science courses and curriculum development"
    url: "/teaching/"
    btn_class: "btn--primary"
    btn_label: "View Courses"
  - title: "Publications"
    excerpt: "Academic papers and research publications"
    url: "/publications/"
    btn_class: "btn--primary"
    btn_label: "Browse Publications"
---

<div class="author__avatar" style="text-align: center; margin: 2rem auto;">
  <img src="images/bedru.jpg" alt="Profile" class="profile-image" style="width: 250px; height: 250px; border-radius: 50%; border: 5px solid #2e8b57; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);">
</div>

{% include feature_row %}

<!-- Research Interests -->
<div style="max-width: 1200px; margin: 3rem auto; padding: 0 1rem;">
  <section style="margin: 3rem 0;">
    <h2 style="text-align: center; color: #2e8b57; margin-bottom: 1.5rem;">Research Focus</h2>
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
    </div>
  </section>
</div>

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<style>
  .btn--primary {
    background: linear-gradient(135deg, #2e8b57 0%, #3cb371 100%);
    border: none;
    border-radius: 30px;
    padding: 0.8rem 2rem;
    font-weight: 600;
    transition: all 0.3s ease;
  }
  
  .btn--primary:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(46, 139, 87, 0.3);
  }
</style>
