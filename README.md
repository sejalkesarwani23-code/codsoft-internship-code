# codsoft-internship-code
#all about internship program
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <div class="container">
      <h1>Sejal Kesarwani</h1>
      <p>Creative Developer • UI Designer • Dream Coder 💻</p>
    </div>
  </header>

  <section id="about" class="section">
    <h2>About Me</h2>
    <div class="about-container">
      <img src="your-photo.jpg" alt="Sejal Kesarwani" class="profile-img" />
      <p>
        Hi, I'm Sejal — a passionate web developer and designer. I love creating beautiful, accessible, and responsive websites. My journey started with HTML & CSS and has now expanded to JavaScript and React.
      </p>
    </div>
  </section>

  <section id="skills" class="section colored">
    <h2>Skills</h2>
    <ul class="skills-grid">
      <li>HTML5</li>
      <li>CSS3</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Figma</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">
        <img src="project1.jpg" alt="Project 1">
        <h3>Weather App</h3>
        <p>A sleek weather app using OpenWeather API and responsive layout design.</p>
      </div>
      <div class="project-card">
        <img src="project2.jpg" alt="Project 2">
        <h3>Portfolio Site</h3>
        <p>A colorful and modern portfolio website made with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project-card">
        <img src="project3.jpg" alt="Project 3">
        <h3>To-Do App</h3>
        <p>A fully functional to-do list with task filtering, light/dark mode, and local storage.</p>
      </div>
    </div>
  </section>

  <section id="resume" class="section colored">
    <h2>Resume</h2>
    <a href="Sejal-Resume.pdf" class="resume-btn" download>📄 Download My Resume</a>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>📧 Email: sejalk@example.com</p>
    <p>📞 Phone: +91 98765 43210</p>
  </section>

  <footer>
    <p>© 2025 Sejal Kesarwani | All rights reserved.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background: #f8f9fc;
  color: #333;
  line-height: 1.6;
}

header {
  background: linear-gradient(to right, #6a11cb, #2575fc);
  color: #fff;
  text-align: center;
  padding: 3rem 1rem;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

header h1 {
  font-size: 2.5rem;
}

header p {
  font-size: 1.2rem;
  margin-top: 0.5rem;
}

.section {
  padding: 3rem 1rem;
  max-width: 1000px;
  margin: auto;
}

h2 {
  font-size: 2rem;
  color: #444;
  margin-bottom: 1.5rem;
  position: relative;
}

h2::after {
  content: "";
  width: 60px;
  height: 4px;
  background: #6a11cb;
  display: block;
  margin-top: 8px;
  border-radius: 5px;
}

.about-container {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
  align-items: center;
}

.profile-img {
  width: 180px;
  border-radius: 50%;
  border: 5px solid #6a11cb;
}

.skills-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  list-style: none;
  padding: 0;
  justify-content: center;
}

.skills-grid li {
  background: #2575fc;
  color: white;
  padding: 0.75rem 1.5rem;
  border-radius: 30px;
  font-weight: 500;
  transition: background 0.3s;
}

.skills-grid li:hover {
  background: #6a11cb;
}

.projects-grid {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.project-card {
  background: white;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
  transition: transform 0.3s;
}

.project-card:hover {
  transform: scale(1.03);
}

.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.project-card h3 {
  margin: 1rem;
  color: #2575fc;
}

.project-card p {
  margin: 0 1rem 1rem;
  font-size: 0.95rem;
}

.resume-btn {
  display: inline-block;
  background: #6a11cb;
  color: #fff;
  padding: 0.8rem 2rem;
  border-radius: 30px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s;
}

.resume-btn:hover {
  background: #2575fc;
}

#contact p {
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}

footer {
  text-align: center;
  background: #333;
  color: #fff;
  padding: 1rem;
  margin-top: 3rem;
}

.colored {
  background: linear-gradient(to right, #f1f0f7, #fdfcfc);
}
