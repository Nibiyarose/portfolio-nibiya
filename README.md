<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nibiya Rose - Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
      background: #f9f9f9;
    }
    header {
      background: linear-gradient(135deg, #9a90a5, #060d19);
      color: #fff;
      text-align: center;
      padding: 60px 20px;
    }
    header h1 {
      font-size: 2.5em;
      margin: 0;
    }
    header p {
      font-size: 1.2em;
      margin: 10px 0;
    }
    nav {
      background: #fff;
      display: flex;
      justify-content: center;
      padding: 10px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      color: #9dc2e7;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2em;
      color: #0d182a;
    }
    .skills, .projects, .awards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #aba9a9;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card i {
      font-size: 2em;
      color: #010409;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: linear-gradient(135deg, #9a90a5, #060d19);;
      color: #fff;
      margin-top: 50px;
    }
  </style>
</head>
<body>

<header>
  <h1> Nibiya Rose</h1>
  <p>Full Stack Developer | MERN Stack Enthusiast</p>
  <p><i class="fas fa-envelope"></i> nibiyanibiya6@gmail.com | <i class="fas fa-phone"></i> 9360814164</p>
  <p><a href="https://www.linkedin.com/in/nibiya-rose-046397361" target="_blank" style="color:#fff;">
     <i class="fab fa-linkedin"></i> LinkedIn</a></p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#awards">Awards</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>
    I’m Nibiya Rose, a BE Computer Science and Engineering graduate with a strong foundation in software 
    development and a passion for full-stack web development. I specialize in the MERN stack and enjoy 
    building responsive, dynamic web applications. I’m eager to apply my skills and grow as a professional developer.
  </p>
</section>

<section id="skills">
  <h2>Technical Skills</h2>
  <div class="skills">
    <div class="card"><i class="fas fa-code"></i> Frontend: HTML, CSS, JS, React, Tailwind</div>
    <div class="card"><i class="fas fa-laptop-code"></i> Backend: Node.js, Express.js</div>
    <div class="card"><i class="fas fa-database"></i> Database: MongoDB</div>
    <div class="card"><i class="fas fa-cogs"></i> Programming: JavaScript, TypeScript, Java</div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="card">
      <i class="fas fa-shopping-cart"></i>
      <h3>E-commerce Website</h3>
      <p>Dynamic, state-driven e-commerce platform built with React.js, Material-UI, and Tailwind CSS.</p>
    </div>
    <div class="card">
      <i class="fas fa-tasks"></i>
      <h3>To-Do List App</h3>
      <p>Task manager app with add, edit, delete, and local storage integration for persistence.</p>
    </div>
  </div>
</section>

<section id="awards">
  <h2>Awards & Certifications</h2>
  <div class="awards">
    <div class="card"><i class="fas fa-award"></i> MERN Stack Development Course - JClick Solutions</div>
    <div class="card"><i class="fas fa-award"></i> Python Automation & AI Internship - EduCAD Tech</div>
    <div class="card"><i class="fas fa-award"></i> Data Analysis & Visualization Workshop - CKS Solutions</div>
    <div class="card"><i class="fas fa-award"></i> SAWIT AI Learnathon - GUVI (HCL Group)</div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p style="text-align:center;">
    <i class="fas fa-envelope"></i> <a href="mailto:nibiyanibiya6@gmail.com">nibiyanibiya6@gmail.com</a> <br>
    <i class="fas fa-phone"></i> 9360814164 <br>
    <i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/nibiya-rose-046397361" target="_blank">LinkedIn Profile</a>
  </p>
</section>

<footer>
  <p>© 2025 Nibiya Rose | Portfolio Website</p>
</footer>

</body>
</html>
