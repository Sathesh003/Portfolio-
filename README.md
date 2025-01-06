<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    /* Global Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: url('images/peaceful-place.jpg') no-repeat center center fixed; /* Add your image path here */
      background-size: cover; /* Ensure the image covers the entire background */
      color: #ffffff;
      line-height: 1.6;
      scroll-behavior: smooth; /* Smooth scrolling for anchor links */
    }

    /* Header Styles */
    header {
      background: rgba(30, 30, 30, 0.9); /* Slightly transparent background */
      padding: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header h1 {
      margin: 0;
      font-size: 28px;
      color: #ffffff;
      text-align: center;
      width: 100%;
    }

    header img {
      display: block;
      margin: 10px auto;
      width: 100px;
      border-radius: 50%;
    }

    header nav {
      display: flex;
      gap: 20px;
      justify-content: center;
      width: 100%;
    }

    header nav a {
      color: #ffffff;
      text-decoration: none;
      font-size: 18px;
      padding: 8px 12px;
      border-radius: 5px;
      transition: background 0.3s;
    }

    header nav a:hover {
      background: #007BFF;
    }

    /* Hero Section */
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: rgba(30, 30, 30, 0.8); /* Slightly transparent overlay */
      border-bottom: 1px solid #333;
    }

    .hero h1 {
      font-size: 50px;
      color: #ffffff;
      margin: 0;
    }

    /* Section Styles */
    section {
      padding: 40px 20px;
      border-bottom: 1px solid #333;
      background: rgba(30, 30, 30, 0.8); /* Slightly transparent background for readability */
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    h1 {
      font-size: 28px;
      color: #ffffff;
      margin-bottom: 20px;
    }

    p, ul {
      font-size: 16px;
      color: #cccccc;
    }

    ul {
      list-style-type: square;
      margin-left: 20px;
    }

    ul li {
      margin-bottom: 10px;
    }

    /* Neon Button Styles */
    .neon-button {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      font-size: 18px;
      color: #fff;
      text-decoration: none;
      border: 2px solid #0ff;
      border-radius: 5px;
      background: transparent;
      cursor: pointer;
      position: relative;
      overflow: hidden;
      box-shadow: 0 0 5px #0ff, 0 0 20px #0ff, 0 0 40px #0ff;
      transition: all 0.3s ease-in-out;
    }

    .neon-button:hover {
      background: #0ff;
      color: #121212;
      box-shadow: 0 0 10px #0ff, 0 0 30px #0ff, 0 0 50px #0ff;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>SATHESH KUMAR V</h1>
    <img src="images/SATHESH.jpg" alt="Sathesh Kumar">
    <nav>
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <div class="hero">
    <h1>Welcome to My Portfolio</h1>
  </div>

  <!-- About Me Section -->
  <section id="about" class="container">
    <h1>About Me</h1>
    <p>
      Hi, I'm <strong>Sathesh Kumar</strong>, a passionate software developer with skills in both front-end and back-end technologies. 
      I love creating innovative and efficient solutions that make a difference. I possess strong analytical and problem-solving skills.
    </p>
    <p> I hold a B.E. in Electronics and Communication Engineering with a CGPA of 8.85 from Mohamed Sathak AJ College of Engineering.</p>
    <h2>Achievements</h2>
    <ul>
      <li>Received a star student award in college for academic performance and contribution to the college activities.</li>
      <li>Won a men's singles carrom tournament trophy.</li>
    </ul>
    <h3>Experience</h3>
    <p>Completed a Python programming internship at Codsoft Solution Private Limited.</p>
    <h4>Interests</h4>
    <p>Web development, digital marketing, and mobile app development.</p>
    <h5>Languages Known</h5>
    <ul>
      <li>English</li>
      <li>Tamil</li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="container">
    <h1>Projects</h1>
    <ul>
      <li>Created a brand Promo Video using Canva. GitHub Link: <a href="https://github.com/Sathesh003/digital-marketing-brand-promo-video" target="_blank">Brand Promo</a></li>
      <li>Developed a website named Green Thumb Up. GitHub Link: <a href="https://github.com/Sathesh003/Cloud-app-development-" target="_blank">Green Thumb Up</a></li>
      <li>AR/VR Conference Hall using Unity software. Showcasing skills in Unity, C#, and AR/VR technologies.</li>
      <li>Designed and developed a line follower robot.</li>
      <li>Final Year Project: Human-Centric Tea Preparation using a six-axis robotic arm enhanced with reinforcement learning.</li>
    </ul>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="container">
    <h1>Skills</h1>
    <div>
      <a href="#" class="neon-button">HTML</a>
      <a href="#" class="neon-button">CSS</a>
      <a href="#" class="neon-button">JavaScript</a>
      <a href="#" class="neon-button">C</a>
      <a href="#" class="neon-button">Python</a>
      <a href="#" class="neon-button">Java</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container">
    <h1>Contact</h1>
    <p>Email: venkatsathesh003@gmail.com</p>
    <p>Phone: 8838818304</p>
    <p>GitHub: <a href="https://github.com/Sathesh003" target="_blank">https://github.com/Sathesh003</a></p>
  </section>

</body>
</html>
