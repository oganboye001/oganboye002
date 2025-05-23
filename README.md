@@ -0,0 +1,108 @@
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abduljalil Ibrahim Khalil - Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f0faff;
      color: #333;
      scroll-behavior: smooth;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
    }

    .hero {
      text-align: center;
      background-color: #e6f3ff;
      border-radius: 8px;
    }

    .about {
      background-color: #dff2ff;
      border-radius: 8px;
      padding: 2rem;
    }

    .about p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    footer {
      background-color: #0077cc;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    a {
      color: #005fa3;
    }
  </style>
</head>
<body>

  <header>
    <h1>Abduljalil Ibrahim Khalil</h1>
    <p>Software Engineering Student | iPhone Software and Hardware repairer | Business Person</p>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <!-- Home Section -->
    <section id="home" class="hero">
      <h2>Welcome to My Portfolio</h2>
      <p>Explore who I am and what I do.</p>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
      <h2>About Me</h2>
      <p>I’m <strong>Abduljalil Ibrahim Khalil</strong>, from <strong>Kano State</strong>, Nigeria. I live, school, and work in Kano. I’m a Business person and also a Professional <strong>PHONE REPAIRER</strong> both software and hardware issues.</p>
      <p>Currently, I’m studying <strong>Software Engineering</strong> at <strong>NORTHWEST UNIVERSITY, KANO STATE</strong>. My passion lies in combining tech skills with entrepreneurial insight to create meaningful solutions and financial growth.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Want to connect or collaborate?</p>
      <p>Reach me on <a href="https://github.com/" target="_blank">GitHub</a> or send an email to <strong>your-email@abduljalilibrahim84@gmail.com</strong>.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Abduljalil Ibrahim Khalil. All rights reserved.</p>
  </footer>

</body>
</html>
