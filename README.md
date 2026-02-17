<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sinchana G | Data Analyst Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- NAVBAR -->
  <nav>
    <h2>Sinchana G</h2>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HOME -->
  <section id="home" class="hero">
    <div class="avatar">SG</div>
    <h1>Sinchana G</h1>
    <p>Aspiring Data Analyst | Data Scientist | Freelancer</p>
    <a href="#projects" class="btn">View Projects</a>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a fresher actively seeking Data Analyst and Data Scientist roles.
      I enjoy working with data, finding insights, and creating dashboards
      that support better decision-making.
    </p>
    <p><strong>Education:</strong><br>
      Bachelor’s of Engineering – ATME College of Engineering (2025)
    </p>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="grid">
      <span>Excel</span>
      <span>SQL</span>
      <span>Python</span>
      <span>Power BI</span>
      <span>Data Analysis</span>
      <span>Data Cleaning</span>
      <span>Machine Learning</span>
    </div>
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2>Services</h2>
    <div class="cards">
      <div class="card">📊 Data Analysis</div>
      <div class="card">🧹 Data Cleaning</div>
      <div class="card">📈 Power BI Dashboards</div>
      <div class="card">🔍 Exploratory Data Analysis</div>
      <div class="card">📑 Excel Reporting</div>
      <div class="card">🤖 Basic Machine Learning</div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Projects</h2>

    <div class="project">
      <h3>🛒 BlinkIt Sales Analysis</h3>
      <p>Power BI dashboard analyzing sales KPIs and trends.</p>
      <a href="https://github.com/sinchanapnn-lgtm/project" target="_blank">View on GitHub</a>
    </div>

    <div class="project">
      <h3>🍫 Chocolate Sales Analysis</h3>
      <p>Python-based analysis of sales performance and seasonality.</p>
      <a href="https://github.com/sinchanapnn-lgtm/chocolate-sales" target="_blank">View on GitHub</a>
    </div>

    <div class="project">
      <h3>📊 Data Science Job Analysis</h3>
      <p>EDA and insights from real-world data science job datasets.</p>
      <a href="https://github.com/sinchanapnn-lgtm/Data-Science-Job" target="_blank">View on GitHub</a>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact Me</h2>

    <!-- IMPORTANT: Replace action link with your Formspree link -->
    <form action="https://formspree.io/f/xxxxabcd" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>

    <p>Email: sinchanapnn@gmail.com</p>
    <p>
      <a href="https://www.linkedin.com/in/sinchana-g-94a67b232/" target="_blank">LinkedIn</a> |
      <a href="https://github.com/sinchanapnn-lgtm" target="_blank">GitHub</a>
    </p>
  </section>

  <footer>
    © 2026 Sinchana G
  </footer>

</body>
</html>

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f5f9ff;
  color: #222;
}

nav {
  display: flex;
  justify-content: space-between;
  padding: 15px 40px;
  background: #0a3d91;
  color: white;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 20px;
}

nav a {
  color: white;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(135deg, #0a3d91, #3b82f6);
  color: white;
}

.avatar {
  width: 90px;
  height: 90px;
  background: white;
  color: #0a3d91;
  border-radius: 50%;
  font-size: 32px;
  font-weight: bold;
  line-height: 90px;
  margin: auto;
}

.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background: white;
  color: #0a3d91;
  text-decoration: none;
  border-radius: 5px;
}

section {
  padding: 50px 40px;
}

.grid span {
  background: #e0ecff;
  padding: 10px;
  border-radius: 5px;
}

.grid, .cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
}

.card, .project {
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
}

form {
  max-width: 400px;
  margin: auto;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
}

button {
  background: #0a3d91;
  color: white;
  border: none;
  padding: 10px;
  width: 100%;
}

footer {
  text-align: center;
  padding: 15px;
  background: #0a3d91;
  color: white;
}
