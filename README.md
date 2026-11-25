<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ansar Zaman | Professional Website Developer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background-color: #060b19;
      color: #ffffff;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #071330 0%, #0d255e 100%);
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #ffd000;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .logo {
      font-size: 1.5rem;
      font-weight: 800;
      color: #ffd000;
      letter-spacing: 1px;
    }
    nav a {
      color: #ffffff;
      text-decoration: none;
      margin-left: 25px;
      font-weight: 600;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ffd000;
    }
    .hero {
      text-align: center;
      padding: 60px 8% 40px;
      background: radial-gradient(circle at top, #0f2c70 0%, #060b19 70%);
    }
    .badge {
      display: inline-block;
      background: #ffd000;
      color: #060b19;
      font-weight: 800;
      padding: 6px 16px;
      border-radius: 50px;
      font-size: 0.9rem;
      margin-bottom: 15px;
    }
    .hero h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }
    .hero h1 span {
      color: #ffd000;
    }
    .hero p {
      max-width: 700px;
      margin: 0 auto 25px;
      color: #cbd5e1;
      font-size: 1.1rem;
    }
    .btn {
      display: inline-block;
      background: #ffd000;
      color: #060b19;
      padding: 12px 28px;
      border-radius: 8px;
      font-weight: 800;
      text-decoration: none;
      margin: 5px;
      transition: 0.3s;
    }
    .btn:hover {
      background: #e6bc00;
      transform: translateY(-2px);
    }
    .btn-outline {
      background: transparent;
      border: 2px solid #ffd000;
      color: #ffd000;
    }
    .btn-outline:hover {
      background: #ffd000;
      color: #060b19;
    }
    .banner-showcase {
      max-width: 1050px;
      margin: 35px auto 0;
      border-radius: 14px;
      overflow: hidden;
      border: 2px solid #1e3a8a;
      box-shadow: 0 15px 40px rgba(0, 0, 0, 0.6);
    }
    .banner-showcase img {
      width: 100%;
      display: block;
    }
    section {
      padding: 60px 8%;
    }
    .section-title {
      text-align: center;
      font-size: 2.2rem;
      margin-bottom: 40px;
    }
    .section-title span {
      color: #ffd000;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
    }
    .card {
      background: #0d1730;
      border: 1px solid #1e3a8a;
      border-radius: 12px;
      padding: 25px;
      transition: 0.3s;
    }
    .card:hover {
      border-color: #ffd000;
      transform: translateY(-5px);
    }
    .card h3 {
      color: #ffd000;
      margin-bottom: 12px;
      font-size: 1.3rem;
    }
    .card ul {
      list-style: none;
      color: #cbd5e1;
    }
    .card ul li {
      margin-bottom: 8px;
    }
    .card ul li::before {
      content: "✔ ";
      color: #ffd000;
      font-weight: bold;
    }
    .skills-wrap {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    .skill-pill {
      background: #0d1730;
      border: 1px solid #ffd000;
      color: #ffffff;
      padding: 10px 22px;
      border-radius: 8px;
      font-weight: 700;
      font-size: 1rem;
    }
    .contact-box {
      background: linear-gradient(135deg, #0d255e 0%, #071330 100%);
      border: 1px solid #ffd000;
      border-radius: 14px;
      padding: 40px;
      text-align: center;
      max-width: 750px;
      margin: 0 auto;
    }
    .contact-box p {
      margin: 12px 0 25px;
      color: #cbd5e1;
    }
    footer {
      text-align: center;
      padding: 25px;
      background: #040812;
      color: #94a3b8;
      border-top: 1px solid #1e293b;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">ANSAR ZAMAN</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#skills">Tech Stack</a>
      <a href="#contact">Hire Me</a>
    </nav>
  </header>

  <div class="hero">
    <div class="badge">100% SATISFACTION GUARANTEED</div>
    <h1>Professional <span>Website Developer</span></h1>
    <p>Turn Your Ideas Into Reality — Responsive Business Websites, Custom E-Commerce Stores, and Full-Stack Web Applications built for speed, SEO, and conversions.</p>
    <a href="#contact" class="btn">Start Your Project →</a>
    <a href="#services" class="btn btn-outline">View My Services</a>

    <div class="banner-showcase">
      <img src="banner.png" alt="Ansar Zaman Web Development Portfolio Banner" />
    </div>
  </div>

  <section id="services">
    <h2 class="section-title">My <span>Services</span></h2>
    <div class="grid">
      <div class="card">
        <h3>Business Website Design</h3>
        <ul>
          <li>Modern & Responsive Design</li>
          <li>Fast Loading Speed</li>
          <li>SEO Friendly Structure</li>
          <li>100% Mobile Friendly</li>
        </ul>
      </div>
      <div class="card">
        <h3>E-Commerce Solutions</h3>
        <ul>
          <li>Custom Online Store Design</li>
          <li>Secure Payment Gateway Integration</li>
          <li>Easy Product & Order Management</li>
          <li>Conversion-Focused Layout</li>
        </ul>
      </div>
      <div class="card">
        <h3>Full Stack Development</h3>
        <ul>
          <li>Custom Web Applications & APIs</li>
          <li>Admin Dashboards & Databases</li>
          <li>Bug Fixing & Speed Optimization</li>
          <li>VPS & Cloud Deployment</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2 class="section-title">Technologies & <span>Skills</span></h2>
    <div class="skills-wrap">
      <div class="skill-pill">WordPress</div>
      <div class="skill-pill">HTML5</div>
      <div class="skill-pill">CSS3</div>
      <div class="skill-pill">PHP</div>
      <div class="skill-pill">JavaScript</div>
      <div class="skill-pill">Python</div>
      <div class="skill-pill">React</div>
      <div class="skill-pill">Flutter</div>
      <div class="skill-pill">Node.js</div>
    </div>
  </section>

  <section id="contact">
    <div class="contact-box">
      <h2>Ready to Build Your Website?</h2>
      <p>Let's discuss your business website, online store, or custom web application today.</p>
      <a href="https://www.fiverr.com/" target="_blank" class="btn">Order on Fiverr</a>
      <a href="mailto:contact@example.com" class="btn btn-outline">Send Email</a>
    </div>
  </section>

  <footer>
    © 2026 Ansar Zaman — All Rights Reserved.
  </footer>

</body>
</html>
