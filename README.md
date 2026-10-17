<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#080d1b">
  <title>Md Abdullah Al Noman | Personal Website</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #080d1b;
      color: #f1f5f9;
      line-height: 1.7;
    }

    header {
      background: #10182b;
      padding: 18px 7%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 1px solid #24304a;
    }

    .logo {
      color: #60a5fa;
      font-size: 21px;
      font-weight: bold;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    nav a {
      text-decoration: none;
      color: #e2e8f0;
      font-size: 14px;
    }

    nav a:hover {
      color: #60a5fa;
    }

    .hero {
      min-height: 82vh;
      padding: 80px 8%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background:
        radial-gradient(circle at top, #172b52, #080d1b 65%);
    }

    .avatar {
      width: 125px;
      height: 125px;
      border-radius: 50%;
      background: #172b52;
      border: 3px solid #60a5fa;
      display: grid;
      place-items: center;
      font-size: 43px;
      font-weight: bold;
      color: #93c5fd;
      margin-bottom: 24px;
      box-shadow: 0 0 35px #2563eb40;
    }

    .hero h1 {
      font-size: clamp(30px, 6vw, 48px);
      line-height: 1.25;
      margin-bottom: 15px;
    }

    .hero h1 span {
      color: #60a5fa;
    }

    .hero p {
      color: #cbd5e1;
      max-width: 600px;
      margin-bottom: 24px;
    }

    .button {
      display: inline-block;
      background: #3b82f6;
      color: white;
      padding: 11px 22px;
      border-radius: 8px;
      text-decoration: none;
      margin: 5px;
      border: 1px solid #60a5fa;
    }

    .button.secondary {
      background: transparent;
    }

    section {
      padding: 65px 8%;
    }

    .section-title {
      text-align: center;
      color: #60a5fa;
      font-size: 29px;
      margin-bottom: 28px;
    }

    .card {
      max-width: 760px;
      margin: 0 auto;
      background: #111a2d;
      padding: 25px;
      border: 1px solid #263653;
      border-radius: 15px;
    }

    .card p {
      color: #cbd5e1;
      margin: 8px 0;
    }

    .highlight {
      color: #93c5fd;
      font-weight: bold;
    }

    .skills {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    .skill {
      padding: 10px 16px;
      border-radius: 9px;
      background: #14233c;
      border: 1px solid #304769;
      color: #bfdbfe;
    }

    .contact {
      text-align: center;
    }

    footer {
      padding: 25px 15px;
      text-align: center;
      background: #10182b;
      color: #94a3b8;
      font-size: 13px;
    }

    @media (max-width: 520px) {
      header {
        justify-content: center;
      }

      nav {
        justify-content: center;
      }

      .hero {
        min-height: 75vh;
        padding: 60px 6%;
      }

      section {
        padding: 48px 6%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">NOMAN.</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#dream">Dream</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="avatar">N</div>

      <h1>Hi, I'm <span>Md Abdullah Al Noman</span></h1>

      <p>
        Student | Dreamer | Future Achiever
        <br>
        Dream Big. Work Hard. Stay Humble.
      </p>

      <a class="button" href="#about">Discover More</a>
      <a class="button secondary" href="#contact">Contact Me</a>
    </section>

    <section id="about">
      <h2 class="section-title">About Me</h2>

      <div class="card">
        <p>
          Assalamu Alaikum! Welcome to my personal website.
        </p>
        <p>
          My name is <span class="highlight">Md Abdullah Al Noman</span>.
          I am a student who believes in learning, self-improvement,
          and working hard to achieve my goals.
        </p>
        <p>
          I am currently studying in the Humanities department.
          I want to develop my skills, gain knowledge, and build
          a successful future.
        </p>
      </div>
    </section>

    <section id="education">
      <h2 class="section-title">My Education</h2>

      <div class="card">
        <p><span class="highlight">Institution:</span>
          Rangpur Government City College</p>

        <p><span class="highlight">Department:</span>
          Humanities</p>

        <p><span class="highlight">Academic Batch:</span>
          HSC 2027</p>

        <p><span class="highlight">Current Level:</span>
          Higher Secondary (HSC)</p>
      </div>
    </section>

    <section id="dream">
      <h2 class="section-title">My Goals</h2>

      <div class="card">
        <p>🎯 Focus on my studies and achieve good results.</p>
        <p>💻 Learn coding and build my own website.</p>
        <p>📚 Improve my English and gain new skills.</p>
        <p>🚀 Work hard to make my dreams come true.</p>
      </div>
    </section>

    <section id="skills">
      <h2 class="section-title">My Interests</h2>

      <div class="skills">
        <div class="skill">Learning</div>
        <div class="skill">Technology</div>
        <div class="skill">Web Development</div>
        <div class="skill">English</div>
        <div class="skill">Personal Growth</div>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2 class="section-title">Contact Me</h2>

      <div class="card">
        <p>
          Thank you for visiting my personal website!
        </p>
        <p>
          You can connect with me through my social media profiles.
        </p>

        <a class="button" href="#" onclick="return false">
          Facebook (Add Link)
        </a>

        <a class="button secondary" href="#" onclick="return false">
          YouTube (Add Link)
        </a>
      </div>
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Md Abdullah Al Noman.</p>
    <p>Made with passion and a dream.</p>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>

</body>
</html>

