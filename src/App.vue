<template id="app">
  <div >
    <!-- Header Section -->
    <header class="header">
      <div class="container header-container">
        <div class="logo">
          <h1>E-<span>sheba</span></h1>
        </div>
        <nav class="navigation">
          <ul>
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Application</a></li>
            <li><a href="#">History</a></li>
          </ul>
        </nav>
        <div class="auth-buttons">
          <button class="btn btn-outline">Log in</button>
          <button class="btn btn-primary">Sign up</button>
        </div>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
      <div class="container hero-container">
        <div class="hero-content">
          <h2>Find & Search Your</h2>
          <h2><span class="text-primary">Favourite</span> Doctor</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
          
          <div class="search-box">
            <div class="search-input">
              <span class="icon">
                <i class="fas fa-user-md"></i>
              </span>
              <input type="text" placeholder="Doctor's Name">
            </div>
            <div class="search-input">
              <span class="icon">
                <i class="fas fa-map-marker-alt"></i>
              </span>
              <input type="text" placeholder="Location">
            </div>
            <button class="search-btn">
              <i class="fas fa-search"></i>
            </button>
          </div>
        </div>
        <div class="hero-image">
          <img src="" alt="Doctor with stethoscope">
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
      <div class="container stats-container">
        <div class="stat-item">
          <h3>24/7</h3>
          <p>Online Service</p>
        </div>
        <div class="stat-item">
          <h3>100+</h3>
          <p>Doctors</p>
        </div>
        <div class="stat-item">
          <h3>1M+</h3>
          <p>Annual Patients</p>
        </div>
      </div>
    </section>

    <!-- Specialists Section -->
    <section class="specialists">
      <div class="container">
        <h2 class="section-title">Our Consulting Specialists</h2>
        <div class="specialists-grid">
          <div class="specialist-card">
            <div class="specialist-icon">
              <i class="fas fa-virus"></i>
            </div>
            <h3>Covid-19 Test</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
          </div>
          <div class="specialist-card active">
            <div class="specialist-icon">
              <i class="fas fa-lungs"></i>
            </div>
            <h3>Heart Lungs</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
          </div>
          <div class="specialist-card">
            <div class="specialist-icon">
              <i class="fas fa-pills"></i>
            </div>
            <h3>Supplement</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
          </div>
          <div class="specialist-card">
            <div class="specialist-icon">
              <i class="fas fa-brain"></i>
            </div>
            <h3>Mental Health</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="why-choose-us">
      <div class="container">
        <div class="why-choose-us-content">
          <div class="why-choose-us-image">
            <img src="" alt="Doctor in surgery">
          </div>
          <div class="why-choose-us-text">
            <h2 class="section-title">Why You Choose Us?</h2>
            <ul class="benefits-list">
              <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li><i class="fas fa-check"></i> Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
            </ul>
            <a href="#" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
      <div class="container">
        <h2 class="section-title">What <span class="text-primary">Our Member's</span> Saying About Us</h2>
        <p class="section-subtitle">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.</p>
        
        <div class="testimonials-content">
          <div class="testimonial-avatars">
            <div class="avatar-group">
              <div class="avatar" v-for="i in 5" :key="i">
                <img src="" alt="User avatar">
              </div>
            </div>
            <p>100+ Reviews</p>
          </div>
          
          <div class="testimonial-card">
            <div class="testimonial-header">
              <div class="user-info">
                <img src="" alt="Jane Cooper">
                <div>
                  <h4>Jane Cooper</h4>
                  <p>Patient</p>
                </div>
              </div>
              <div class="rating">
                <i class="fas fa-star" v-for="i in 5" :key="i"></i>
              </div>
            </div>
            <p class="testimonial-text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam eget varius amet facilisis.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Future Health Section -->
    <section class="future-health">
      <div class="container">
        <div class="future-health-content">
          <div class="future-health-text">
            <h2 class="section-title">The Future <br>of <span class="text-primary">Quality Health</span></h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non nulla feugiat risus nisl sed ullamcorper. Auctor semper fermentum integer vel. Id morbi ut in blandit id porttum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non nulla feugiat risus nisl sed ullamcorper. Auctor semper fermentum integer vel. Id morbi ut in blandit id porttum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non nulla feugiat risus nisl sed ullamcorper. Auctor semper fermentum integer vel. Id morbi ut in blandit id porttum.</p>
            <a href="#" class="learn-more">Learn More <i class="fas fa-arrow-right"></i></a>
          </div>
          <div class="future-health-image">
            <img src="" alt="Doctor with patient">
          </div>
        </div>
      </div>
    </section>

    <!-- Newsletter Section -->
    <section class="newsletter">
      <div class="container">
        <h2 class="section-title">Subscribe To Our Newsletter</h2>
        <div class="newsletter-form">
          <input type="email" placeholder="Enter your email">
          <button class="btn-circle">
            <i class="fas fa-arrow-right"></i>
          </button>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
      <div class="container footer-container">
        <div class="footer-column">
          <h3 class="footer-logo">E-sheba</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non nulla feugiat risus nisl sed ullamcorper.</p>
          <div class="social-icons">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
          </div>
        </div>
        <div class="footer-column">
          <h3>Useful Links</h3>
          <ul class="footer-links">
            <li><a href="#">About Us</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Our Team</a></li>
          </ul>
        </div>
        <div class="footer-column">
          <h3>Address</h3>
          <div class="map-container">
            <img src="" alt="Map"> 
          </div> 
        </div> 
      </div> 
      <div class="copyright"> 
        <p>© 2023 All Right Reserved</p> 
      </div> 
    </footer> 
  </div> 
</template> 

<script setup>
// Vue 3 Composition API setup
import { ref, onMounted } from 'vue';

// You can add any reactive data or methods here
</script>

<style>
/* Import Font Awesome for icons */
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');
/* Import Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

:root {
  --primary-color: #0066ff;
  --primary-dark: #0052cc;
  --primary-light: #e6f0ff;
  --secondary-color: #333333;
  --text-color: #333333;
  --text-light: #666666;
  --background-light: #f0f7ff;
  --white: #ffffff;
  --border-color: #e0e0e0;
  --border-radius: 8px;
  --box-shadow: 0 4px 12px rgba(0, 102, 255, 0.1);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  color: var(--text-color);
  line-height: 1.6;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

a {
  text-decoration: none;
  color: inherit;
}

ul {
  list-style: none;
}

img {
  max-width: 100%;
}

.text-primary {
  color: var(--primary-color);
}

.section-title {
  font-size: 2.2rem;
  font-weight: 700;
  margin-bottom: 1.5rem;
}

.section-subtitle {
  color: var(--text-light);
  margin-bottom: 2rem;
}

/* Button Styles */
.btn {
  padding: 10px 24px;
  border-radius: 4px;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.3s ease;
  border: none;
  font-size: 0.9rem;
}

.btn-primary {
  background-color: var(--primary-color);
  color: var(--white);
}

.btn-primary:hover {
  background-color: var(--primary-dark);
}

.btn-outline {
  background-color: transparent;
  color: var(--primary-color);
  border: 1px solid var(--primary-color);
}

.btn-outline:hover {
  background-color: var(--primary-light);
}

.btn-circle {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  background-color: var(--primary-color);
  color: var(--white);
  display: flex;
  align-items: center;
  justify-content: center;
  border: none;
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn-circle:hover {
  background-color: var(--primary-dark);
}

.learn-more {
  color: var(--primary-color);
  font-weight: 500;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin-top: 1rem;
}

.learn-more i {
  transition: transform 0.3s ease;
}

.learn-more:hover i {
  transform: translateX(5px);
}

/* Header Styles */
.header {
  padding: 20px 0;
  background-color: var(--background-light);
}

.header-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo h1 {
  font-size: 1.8rem;
  font-weight: 700;
}

.logo span {
  color: var(--primary-color);
}

.navigation ul {
  display: flex;
  gap: 30px;
}

.navigation a {
  font-weight: 500;
  transition: color 0.3s ease;
}

.navigation a:hover, .navigation a.active {
  color: var(--primary-color);
}

.auth-buttons {
  display: flex;
  gap: 12px;
}

/* Hero Section */
.hero {
  background-color: var(--background-light);
  padding: 60px 0;
  position: relative;
  overflow: hidden;
}

.hero-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.hero-content {
  flex: 1;
}

.hero-content h2 {
  font-size: 2.8rem;
  font-weight: 700;
  line-height: 1.2;
  margin-bottom: 1rem;
}

.hero-content p {
  color: var(--text-light);
  margin-bottom: 2rem;
  max-width: 500px;
}

.hero-image {
  flex: 1;
  display: flex;
  justify-content: center;
}

.hero-image img {
  max-width: 100%;
  border-radius: 50%;
  background-color: var(--primary-light);
}

.search-box {
  display: flex;
  background-color: var(--white);
  border-radius: var(--border-radius);
  box-shadow: var(--box-shadow);
  overflow: hidden;
  max-width: 500px;
}

.search-input {
  flex: 1;
  display: flex;
  align-items: center;
  padding: 0 15px;
  border-right: 1px solid var(--border-color);
}

.search-input:last-of-type {
  border-right: none;
}

.search-input .icon {
  color: var(--text-light);
  margin-right: 10px;
}

.search-input input {
  border: none;
  outline: none;
  padding: 15px 0;
  width: 100%;
  font-family: inherit;
}

.search-btn {
  background-color: var(--primary-color);
  color: var(--white);
  border: none;
  width: 50px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.search-btn:hover {
  background-color: var(--primary-dark);
}

/* Stats Section */
.stats {
  background-color: var(--primary-color);
  color: var(--white);
  padding: 30px 0;
}

.stats-container {
  display: flex;
  justify-content: space-around;
  text-align: center;
}

.stat-item h3 {
  font-size: 2.2rem;
  font-weight: 700;
  margin-bottom: 5px;
}

.stat-item p {
  font-size: 1rem;
  opacity: 0.9;
}

/* Specialists Section */
.specialists {
  padding: 80px 0;
}

.specialists-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 40px;
}

.specialist-card {
  background-color: var(--white);
  border-radius: var(--border-radius);
  padding: 30px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
  text-align: center;
}

.specialist-card.active {
  background-color: var(--primary-color);
  color: var(--white);
}

.specialist-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
}

.specialist-icon {
  width: 60px;
  height: 60px;
  background-color: var(--primary-light);
  color: var(--primary-color);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 20px;
  font-size: 1.5rem;
}

.specialist-card.active .specialist-icon {
  background-color: var(--white);
}

.specialist-card h3 {
  font-size: 1.2rem;
  margin-bottom: 15px;
}

.specialist-card p {
  font-size: 0.9rem;
  color: var(--text-light);
}

.specialist-card.active p {
  color: rgba(255, 255, 255, 0.8);
}

/* Why Choose Us Section */
.why-choose-us {
  padding: 80px 0;
}

.why-choose-us-content {
  display: flex;
  align-items: center;
  gap: 50px;
}

.why-choose-us-image {
  flex: 1;
}

.why-choose-us-image img {
  border-radius: 10px;
  box-shadow: var(--box-shadow);
}

.why-choose-us-text {
  flex: 1;
}

.benefits-list {
  margin: 20px 0;
}

.benefits-list li {
  margin-bottom: 15px;
  display: flex;
  align-items: flex-start;
  gap: 10px;
}

.benefits-list i {
  color: var(--primary-color);
  margin-top: 5px;
}

/* Testimonials Section */
.testimonials {
  padding: 80px 0;
  background-color: var(--background-light);
  text-align: center;
}

.testimonials-content {
  display: flex;
  align-items: center;
  gap: 40px;
  margin-top: 40px;
  text-align: left;
}

.testimonial-avatars {
  flex: 1;
}

.avatar-group {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 15px;
}

.avatar {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  overflow: hidden;
  border: 2px solid var(--white);
}

.testimonial-card {
  flex: 2;
  background-color: var(--white);
  border-radius: var(--border-radius);
  padding: 30px;
  box-shadow: var(--box-shadow);
}

.testimonial-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}

.user-info {
  display: flex;
  align-items: center;
  gap: 15px;
}

.user-info img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}

.rating {
  color: #FFD700;
}

.testimonial-text {
  color: var(--text-light);
  line-height: 1.8;
}

/* Future Health Section */
.future-health {
  padding: 80px 0;
}

.future-health-content {
  display: flex;
  align-items: center;
  gap: 50px;
}

.future-health-text {
  flex: 1;
}

.future-health-text p {
  margin-bottom: 15px;
  color: var(--text-light);
}

.future-health-image {
  flex: 1;
}

.future-health-image img {
  border-radius: 10px;
  box-shadow: var(--box-shadow);
}

/* Newsletter Section */
.newsletter {
  padding: 60px 0;
  background-color: var(--primary-color);
  color: var(--white);
  text-align: center;
}

.newsletter .section-title {
  margin-bottom: 30px;
}

.newsletter-form {
  display: flex;
  max-width: 500px;
  margin: 0 auto;
  background-color: var(--white);
  border-radius: 50px;
  overflow: hidden;
}

.newsletter-form input {
  flex: 1;
  border: none;
  outline: none;
  padding: 15px 25px;
  font-family: inherit;
  font-size: 1rem;
}

/* Footer Section */
.footer {
  background-color: var(--primary-color);
  color: var(--white);
  padding: 60px 0 0;
}

.footer-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 40px;
  margin-bottom: 40px;
}

.footer-logo {
  font-size: 1.8rem;
  margin-bottom: 20px;
}

.social-icons {
  display: flex;
  gap: 15px;
  margin-top: 20px;
}

.social-icons a {
  width: 36px;
  height: 36px;
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background-color 0.3s ease;
}

.social-icons a:hover {
  background-color: rgba(255, 255, 255, 0.2);
}

.footer-links {
  margin-top: 20px;
}

.footer-links li {
  margin-bottom: 10px;
}

.footer-links a {
  opacity: 0.8;
  transition: opacity 0.3s ease;
}

.footer-links a:hover {
  opacity: 1;
}

.map-container {
  margin-top: 20px;
  border-radius: var(--border-radius);
  overflow: hidden;
}

.copyright {
  text-align: center;
  padding: 20px 0;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  font-size: 0.9rem;
  opacity: 0.8;
}

/* Responsive Styles */
@media (max-width: 992px) {
  .hero-container, 
  .why-choose-us-content,
  .testimonials-content,
  .future-health-content {
    flex-direction: column;
  }
  
  .hero-content {
    text-align: center;
    margin-bottom: 40px;
  }
  
  .hero-content p {
    margin: 0 auto 2rem;
  }
  
  .search-box {
    margin: 0 auto;
  }
  
  .why-choose-us-image,
  .future-health-image {
    order: -1;
    margin-bottom: 30px;
  }
  
  .testimonial-avatars {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}

@media (max-width: 768px) {
  .header-container {
    flex-direction: column;
    gap: 20px;
  }
  
  .navigation ul {
    gap: 15px;
  }
  
  .section-title {
    font-size: 1.8rem;
  }
  
  .hero-content h2 {
    font-size: 2.2rem;
  }
  
  .search-box {
    flex-direction: column;
  }
  
  .search-input {
    border-right: none;
    border-bottom: 1px solid var(--border-color);
  }
  
  .search-btn {
    width: 100%;
    height: 50px;
  }
  
  .stats-container {
    flex-direction: column;
    gap: 20px;
  }
}

@media (max-width: 576px) {
  .navigation ul {
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .auth-buttons {
    flex-direction: column;
    width: 100%;
  }
  
  .btn {
    width: 100%;
  }
  
  .testimonial-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 15px;
  }
}
</style>