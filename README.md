<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>M.keerthana — Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <a class="logo" href="#home">M.keerthana</a>

      <nav class="nav">
        <button id="navToggle" class="nav-toggle" aria-label="Toggle navigation">☰</button>
        <ul id="navList" class="nav-list">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <main>
    <section id="home" class="hero">
      <div class="container hero-inner">
        <div class="hero-text">
          <h1>Hello, I'm <span class="accent">M.keerthana</span></h1>
          <p class="lead">Web Developer · Designer · Coder</p>
          <p class="cta-row">
            <a class="btn primary" href="#projects">See My Work</a>
            <a class="btn ghost" href="#contact">Contact Me</a>
          </p>
        </div>
        <div class="hero-card" aria-hidden="true">
          <!-- simple decorative card -->
          <div class="card-avatar">MK</div>
          <p class="card-note">Building clean, responsive web experiences.</p>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="section">
      <div class="container">
        <h2>About Me</h2>
        <p>I’m a creative and passionate Web Developer & Designer focused on building modern, responsive, and user-friendly websites. I enjoy solving problems with code, crafting simple interfaces, and turning ideas into polished digital experiences.</p>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="section alt">
      <div class="container">
        <h2>Skills</h2>
        <div class="skills-grid" role="list">
          <div class="skill" role="listitem">HTML</div>
          <div class="skill" role="listitem">CSS</div>
          <div class="skill" role="listitem">JavaScript</div>
          <div class="skill" role="listitem">React</div>
          <div class="skill" role="listitem">Node.js</div>
          <div class="skill" role="listitem">UI / UX Design</div>
          <div class="skill" role="listitem">Git & GitHub</div>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="section">
      <div class="container">
        <h2>Projects</h2>
        <div class="projects-grid">
          <article class="project-card">
            <h3>Portfolio Website</h3>
            <p>A modern responsive portfolio showcasing my skills and projects.</p>
            <a class="link" href="https://github.com/yourusername/portfolio" target="_blank" rel="noopener">View on GitHub →</a>
          </article>

          <article class="project-card">
            <h3>Task Manager App</h3>
            <p>Full-stack task management app with authentication and CRUD.</p>
            <a class="link" href="https://github.com/yourusername/task-manager" target="_blank" rel="noopener">View on GitHub →</a>
          </article>

          <article class="project-card">
            <h3>UI/UX Prototype</h3>
            <p>Mobile app prototype designed in Figma for a smooth user experience.</p>
            <a class="link" href="https://github.com/yourusername/design-prototype" target="_blank" rel="noopener">View on GitHub →</a>
          </article>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="section alt">
      <div class="container">
        <h2>Contact Me</h2>
        <form id="contactForm" class="contact-form">
          <div class="form-row">
            <input id="name" name="name" type="text" placeholder="Your Name" required />
            <input id="email" name="email" type="email" placeholder="Your Email"y required />
          </div>
          <input id="subject" name="subject" type="text" placeholder="Subject" required />
          <textarea id="message" name="message" rows="6" placeholder="Your Message" required></textarea>
          <div class="form-actions">
            <button type="submit" class="btn primary">Send Message</button>
            <button type="reset" class="btn ghost">Reset</button>
          </div>
          <p id="formStatus" class="form-status" aria-live="polite"></p>
        </form>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <p>© <span id="year"></span> M.keerthana. Built with ❤️ and code.</p>
      <div class="social">
        <a href="#" aria-label="GitHub">GitHub</a>
        <a href="#" aria-label="LinkedIn">LinkedIn</a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
