---
layout: single
title: "Contact"
permalink: /contact/
author_profile: true
classes: wide
---

<div style="text-align: center; margin-bottom: 3rem;">
  <h1 style="color: #2e8b57; margin-bottom: 1rem;">Contact Information</h1>
  <p style="font-size: 1.1rem; max-width: 800px; margin: 0 auto; color: #555;">
    Get in touch for research collaborations, student supervision, or academic inquiries
  </p>
</div>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-bottom: 3rem;">

  <!-- Contact Information Card -->
  <div style="background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 3px 15px rgba(0, 0, 0, 0.08);">
    <div style="text-align: center; margin-bottom: 1.5rem;">
      <div style="width: 80px; height: 80px; background: #e8f5e8; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 1rem auto;">
        <i class="fas fa-university" style="font-size: 2rem; color: #2e8b57;"></i>
      </div>
      <h2 style="color: #2e8b57; margin-bottom: 0.5rem;">Academic Contact</h2>
      <p style="color: #555; font-size: 0.9rem;">For research and academic matters</p>
    </div>
    
    <div style="margin-bottom: 1.5rem;">
      <div style="display: flex; align-items: flex-start; margin-bottom: 1rem;">
        <i class="fas fa-building" style="color: #2e8b57; margin-right: 1rem; margin-top: 0.3rem;"></i>
        <div>
          <h4 style="margin: 0 0 0.2rem 0; color: #2c3e50;">Department</h4>
          <p style="margin: 0; color: #555;">Department ofInformation Technology<br>Wollo University</p>
        </div>
      </div>
      
      <div style="display: flex; align-items: flex-start; margin-bottom: 1rem;">
        <i class="fas fa-map-marker-alt" style="color: #2e8b57; margin-right: 1rem; margin-top: 0.3rem;"></i>
        <div>
          <h4 style="margin: 0 0 0.2rem 0; color: #2c3e50;">Location</h4>
          <p style="margin: 0; color: #555;">Dessie, Ethiopia</p>
        </div>
      </div>
      
      <div style="display: flex; align-items: flex-start; margin-bottom: 1rem;">
        <i class="fas fa-envelope" style="color: #2e8b57; margin-right: 1rem; margin-top: 0.3rem;"></i>
        <div>
          <h4 style="margin: 0 0 0.2rem 0; color: #2c3e50;">Email</h4>
          <p style="margin: 0; color: #555;">
            <a href="mailto:bedruy4@gmail.com" style="color: #2e8b57; text-decoration: none;">bedruy4@gmail.com</a>
          </p>
        </div>
      </div>
      
      <div style="display: flex; align-items: flex-start; margin-bottom: 1rem;">
        <i class="fas fa-phone" style="color: #2e8b57; margin-right: 1rem; margin-top: 0.3rem;"></i>
        <div>
          <h4 style="margin: 0 0 0.2rem 0; color: #2c3e50;">Phone</h4>
          <p style="margin: 0; color: #555;">+251 [09-96-30-61-84]</p>
        </div>
      </div>
      
      <div style="display: flex; align-items: flex-start;">
        <i class="fas fa-clock" style="color: #2e8b57; margin-right: 1rem; margin-top: 0.3rem;"></i>
        <div>
          <h4 style="margin: 0 0 0.2rem 0; color: #2c3e50;">Office Hours</h4>
          <p style="margin: 0; color: #555;">
            Monday - Friday: 9:00 AM - 5:00 PM<br>
            By appointment preferred
          </p>
        </div>
      </div>
    </div>
    
    <div style="text-align: center; margin-top: 1.5rem;">
      <a href="mailto:bedruy4@gmail.com" class="contact-btn" style="background: #2e8b57;">
        <i class="fas fa-paper-plane"></i> Send Email
      </a>
    </div>
  </div>

  <!-- Contact Form Card -->
  <div style="background: white; padding: 2rem; border-radius: 10px; box-shadow: 0 3px 15px rgba(0, 0, 0, 0.08);">
    <div style="text-align: center; margin-bottom: 1.5rem;">
      <div style="width: 80px; height: 80px; background: #e8f5e8; border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 1rem auto;">
        <i class="fas fa-comments" style="font-size: 2rem; color: #2e8b57;"></i>
      </div>
      <h2 style="color: #2e8b57; margin-bottom: 0.5rem;">Send a Message</h2>
      <p style="color: #555; font-size: 0.9rem;">I'll respond as soon as possible</p>
    </div>
    
    <form id="contactForm" style="margin-top: 1.5rem;">
      <div style="margin-bottom: 1rem;">
        <label for="name" style="display: block; margin-bottom: 0.5rem; color: #2c3e50; font-weight: 500;">Your Name *</label>
        <input type="text" id="name" name="name" required style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 4px; font-size: 1rem; box-sizing: border-box;">
      </div>
      
      <div style="margin-bottom: 1rem;">
        <label for="email" style="display: block; margin-bottom: 0.5rem; color: #2c3e50; font-weight: 500;">Your Email *</label>
        <input type="email" id="email" name="email" required style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 4px; font-size: 1rem; box-sizing: border-box;">
      </div>
      
      <div style="margin-bottom: 1rem;">
        <label for="subject" style="display: block; margin-bottom: 0.5rem; color: #2c3e50; font-weight: 500;">Subject *</label>
        <select id="subject" name="subject" required style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 4px; font-size: 1rem; box-sizing: border-box; background: white;">
          <option value="">Select a topic</option>
          <option value="research">Research Collaboration</option>
          <option value="supervision">Student Supervision</option>
          <option value="course">Course Information</option>
          <option value="speaking">Speaking Engagement</option>
          <option value="other">Other Inquiry</option>
        </select>
      </div>
      
      <div style="margin-bottom: 1.5rem;">
        <label for="message" style="display: block; margin-bottom: 0.5rem; color: #2c3e50; font-weight: 500;">Message *</label>
        <textarea id="message" name="message" rows="5" required style="width: 100%; padding: 0.8rem; border: 1px solid #ddd; border-radius: 4px; font-size: 1rem; box-sizing: border-box; resize: vertical;"></textarea>
      </div>
      
      <div style="text-align: center;">
        <button type="submit" class="contact-btn" style="background: #2e8b57; border: none; cursor: pointer; width: 100%;">
          <i class="fas fa-paper-plane"></i> Send Message
        </button>
      </div>
    </form>
    
    <div id="formMessage" style="margin-top: 1rem; padding: 1rem; border-radius: 4px; display: none; text-align: center;"></div>
  </div>
</div>

## Quick Contact Guide

### For Research Collaboration
- **Best contact method:** Email with detailed project proposal
- **Response time:** Within 2-3 business days
- **Include:** Brief project summary, potential outcomes, and collaboration ideas

### For Student Supervision
- **Best contact method:** Email with academic transcript and research interests
- **Response time:** Within 1 week during academic terms
- **Include:** CV, academic background, and specific research interests

### For Course Information
- **Best contact method:** Email or during office hours
- **Response time:** Within 24-48 hours
- **Include:** Course code and specific questions

### For Speaking Engagements
- **Best contact method:** Email with event details
- **Response time:** Within 1 week
- **Include:** Event date, topic, audience, and duration

## Social and Academic Profiles

<div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 1.5rem; margin: 2rem 0;">
  <a href="https://github.com/BedruYimam" target="_blank" class="social-btn" style="background: #333;">
    <i class="fab fa-github"></i> GitHub
  </a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID" target="_blank" class="social-btn" style="background: #4285f4;">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
  <a href="https://linkedin.com/in/yourprofile" target="_blank" class="social-btn" style="background: #0077b5;">
    <i class="fab fa-linkedin"></i> LinkedIn
  </a>
  <a href="https://orcid.org/YOUR_ORCID" target="_blank" class="social-btn" style="background: #a6ce39;">
    <i class="ai ai-orcid"></i> ORCID
  </a>
  <a href="https://www.researchgate.net/profile/YOUR_PROFILE" target="_blank" class="social-btn" style="background: #00d0af;">
    <i class="ai ai-researchgate"></i> ResearchGate
  </a>
  <a href="https://twitter.com/yourprofile" target="_blank" class="social-btn" style="background: #1da1f2;">
    <i class="fab fa-twitter"></i> Twitter
  </a>
</div>

## Frequently Asked Questions

<div class="faq-item" style="margin-bottom: 1rem; border-bottom: 1px solid #eee; padding-bottom: 1rem;">
  <h4 style="color: #2e8b57; margin-bottom: 0.5rem; cursor: pointer;" onclick="toggleFAQ(this)">
    <i class="fas fa-chevron-right" style="margin-right: 0.5rem; transition: transform 0.3s;"></i>
    How can I apply for graduate studies under your supervision?
  </h4>
  <div class="faq-answer" style="display: none; color: #555; padding-left: 1.5rem;">
    Please send an email with your CV, academic transcripts, and a brief statement of research interests. Include why you're interested in working with me specifically and how your background aligns with my research areas.
  </div>
</div>

<div class="faq-item" style="margin-bottom: 1rem; border-bottom: 1px solid #eee; padding-bottom: 1rem;">
  <h4 style="color: #2e8b57; margin-bottom: 0.5rem; cursor: pointer;" onclick="toggleFAQ(this)">
    <i class="fas fa-chevron-right" style="margin-right: 0.5rem; transition: transform 0.3s;"></i>
    What is the typical response time for emails?
  </h4>
  <div class="faq-answer" style="display: none; color: #555; padding-left: 1.5rem;">
    I typically respond to emails within 2-3 business days. During busy academic periods (exams, paper deadlines), response times may be longer. For urgent matters, please indicate "URGENT" in the subject line.
  </div>
</div>

<div class="faq-item" style="margin-bottom: 1rem; border-bottom: 1px solid #eee; padding-bottom: 1rem;">
  <h4 style="color: #2e8b57; margin-bottom: 0.5rem; cursor: pointer;" onclick="toggleFAQ(this)">
    <i class="fas fa-chevron-right" style="margin-right: 0.5rem; transition: transform 0.3s;"></i>
    Can undergraduate students work on research projects?
  </h4>
  <div class="faq-answer" style="display: none; color: #555; padding-left: 1.5rem;">
    Yes, I frequently work with undergraduate students on research projects. Interested students should have completed relevant coursework and be prepared to commit significant time. Contact me with your academic background and interests.
  </div>
</div>

<div class="faq-item" style="margin-bottom: 1rem; border-bottom: 1px solid #eee; padding-bottom: 1rem;">
  <h4 style="color: #2e8b57; margin-bottom: 0.5rem; cursor: pointer;" onclick="toggleFAQ(this)">
    <i class="fas fa-chevron-right" style="margin-right: 0.5rem; transition: transform 0.3s;"></i>
    Do you accept international research collaborations?
  </h4>
  <div class="faq-answer" style="display: none; color: #555; padding-left: 1.5rem;">
    Absolutely. I welcome international collaborations. Please include information about your institution, potential funding sources (if any), and specific collaboration ideas in your initial contact.
  </div>
</div>

## Campus Location

<div style="background: #f8f9fa; padding: 1.5rem; border-radius: 8px; margin: 2rem 0;">
  <h3 style="color: #2e8b57; margin-top: 0; margin-bottom: 1rem;">
    <i class="fas fa-map-marked-alt" style="margin-right: 0.5rem;"></i> Wollo University Campus
  </h3>
  <p style="color: #555; margin-bottom: 1rem;">
    <strong>Main Campus Address:</strong><br>
    Wollo University<br>
    P.O. Box [Box Number]<br>
    Dessie, Ethiopia
  </p>
  <p style="color: #555; margin-bottom: 1rem;">
    <strong>Department Location:</strong><br>
    Computer Science Department<br>
    [Building Name], Room [Room Number]<br>
    [Specific directions if needed]
  </p>
  <div style="background: #e8f5e8; padding: 1rem; border-radius: 4px; margin-top: 1rem;">
    <p style="margin: 0; color: #2e8b57; font-weight: 500;">
      <i class="fas fa-info-circle" style="margin-right: 0.5rem;"></i>
      For campus visits, please schedule an appointment in advance.
    </p>
  </div>
</div>

## Alternative Contact Methods

### Department Office
- **Department Secretary:** [Secretary Name]
- **Department Phone:** +251 [Department Phone]
- **Department Email:** cs@wollo.edu.et (example)

### Administrative Assistant
- **Name:** [Assistant Name]
- **Email:** [Assistant Email]
- **Availability:** [Days/Times]

---

## Response Commitment

I am committed to responding to all serious inquiries in a timely manner. Your interest in my work is appreciated, and I look forward to connecting with potential collaborators, students, and colleagues.

*Note: For student advising, please include your student ID and program details in your correspondence.*

---

<style>
/* Custom styles for contact page */
.page__content h2 {
  color: #2e8b57;
  border-bottom: 2px solid #e8f5e8;
  padding-bottom: 0.5rem;
  margin-top: 2.5rem;
}

.contact-btn {
  display: inline-block;
  background: #2e8b57;
  color: white;
  padding: 0.8rem 2rem;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 600;
  transition: all 0.3s ease;
  text-align: center;
  border: none;
  font-size: 1rem;
  cursor: pointer;
}

.contact-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(46, 139, 87, 0.3);
}

.social-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: white;
  padding: 0.8rem 1.5rem;
  text-decoration: none;
  border-radius: 30px;
  font-weight: 500;
  transition: all 0.3s ease;
}

.social-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.social-btn i {
  font-size: 1.2rem;
}

.faq-item h4:hover {
  color: #3cb371;
}

input:focus, select:focus, textarea:focus {
  outline: none;
  border-color: #2e8b57;
  box-shadow: 0 0 0 2px rgba(46, 139, 87, 0.1);
}

@media (max-width: 768px) {
  .contact-btn, .social-btn {
    width: 100%;
    justify-content: center;
    margin-bottom: 0.5rem;
  }
  
  .social-btn {
    flex: 1;
    min-width: 150px;
  }
}
</style>

<script>
// Simple form handling (for demonstration - would need backend for production)
document.getElementById('contactForm').addEventListener('submit', function(e) {
  e.preventDefault();
  
  const formMessage = document.getElementById('formMessage');
  const submitBtn = this.querySelector('button[type="submit"]');
  
  // Show loading state
  const originalText = submitBtn.innerHTML;
  submitBtn.innerHTML = '<i class="fas fa-spinner fa-spin"></i> Sending...';
  submitBtn.disabled = true;
  
  // Simulate form submission
  setTimeout(() => {
    // In a real implementation, you would send the form data to a server here
    // For GitHub Pages, you would need to use a third-party service like Formspree
    
    formMessage.textContent = 'Thank you for your message! I will respond as soon as possible.';
    formMessage.style.backgroundColor = '#d4edda';
    formMessage.style.color = '#155724';
    formMessage.style.border = '1px solid #c3e6cb';
    formMessage.style.display = 'block';
    
    // Reset form
    this.reset();
    
    // Reset button
    submitBtn.innerHTML = originalText;
    submitBtn.disabled = false;
    
    // Hide message after 5 seconds
    setTimeout(() => {
      formMessage.style.display = 'none';
    }, 5000);
  }, 1500);
});

// FAQ toggle function
function toggleFAQ(element) {
  const answer = element.nextElementSibling;
  const icon = element.querySelector('i');
  
  if (answer.style.display === 'block') {
    answer.style.display = 'none';
    icon.style.transform = 'rotate(0deg)';
  } else {
    answer.style.display = 'block';
    icon.style.transform = 'rotate(90deg)';
  }
}
</script>

<!-- Add Font Awesome Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
<!-- Add Academicons for academic icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
