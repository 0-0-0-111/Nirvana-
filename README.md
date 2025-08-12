<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Nirvana - An aspiring software developer sharing their journey, learning path, and helpful resources.">
  <title>Nirvana - Aspiring Software Developer</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">

  <style>
    body {
      background-color: #fff8b0;
      font-family: 'Pacifico', cursive;
      color: #001f4d;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
    }

    nav {
      text-align: center;
      padding: 15px;
      background: #ffda6b;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: #0044cc;
      font-weight: bold;
      text-decoration: none;
      margin: 0 15px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #222;
      text-shadow: 0 0 5px rgba(0,0,0,0.2);
    }

    main {
      max-width: 800px;
      margin: auto;
      background-color: lightgray;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      animation: fadeIn 1.2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h1 {
      text-align: center;
      color: #222;
    }

    h2 {
      text-align: center;
      font-size: 24px;
      color: #333;
    }

    section {
      margin-top: 20px;
    }

    details {
      background: #f7f7f7;
      padding: 10px;
      border-radius: 8px;
      margin-top: 10px;
      cursor: pointer;
      transition: background 0.3s;
    }

    details:hover {
      background: #eee;
    }

    p, ol {
      font-size: 16px;
      line-height: 1.6;
      color: #444;
    }

    ol {
      padding-left: 20px;
    }

    a {
      color: #0044cc;
      font-weight: bold;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    button {
      background: #0044cc;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 15px;
      font-size: 16px;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #003399;
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 15px;
      font-size: 14px;
      color: #666;
      margin-top: 40px;
    }
  </style>
</head>

<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Main Content -->
  <main id="home">
    <h1>Aspiring Software Developer</h1>
    <h2>Learn and Teach</h2>

    <p>
      I’m an <strong>aspiring Software Developer</strong> passionate about <strong>building impactful digital solutions</strong>.
      Currently learning the basics of <strong>coding</strong>, <strong>problem-solving</strong>, and <strong>software design</strong>.
      I'm on a journey to turn ideas into digital reality — one line of code at a time.
    </p>

    <section>
      <p><strong>What is Software Development?</strong></p>
      <p>
        Software development is the process of creating computer programs, apps, or systems that solve problems, perform tasks, or provide services.
        It includes <strong>planning</strong>, <strong>designing</strong>, <strong>coding</strong>, <strong>testing</strong>, <strong>deploying</strong>, and <strong>maintaining</strong> software.
      </p>
    </section>

    <!-- Collapsible Stages -->
    <section>
      <p><strong>Main Stages of Software Development:</strong></p>
      <details>
        <summary>Click to see stages</summary>
        <ol>
          <li><strong>Planning & Requirements:</strong> Understand what the software is supposed to do by talking with users or clients.</li>
          <li><strong>Design:</strong> Plan how the software will look and function, and choose the right tools.</li>
          <li><strong>Development (Coding):</strong> Write the code using programming languages like Python, JavaScript, etc.</li>
          <li><strong>Testing:</strong> Check for bugs and ensure everything works as expected.</li>
          <li><strong>Deployment:</strong> Release the software for users.</li>
          <li><strong>Maintenance & Updates:</strong> Fix issues and improve features over time.</li>
        </ol>
      </details>
    </section>

    <p>
      Want to know more about software development?<br />
      Visit <a href="https://www.freecodecamp.org/" target="_blank">freeCodeCamp.org</a> to start learning today!
    </p>

    <button onclick="alert('Thanks for visiting! 🚀')">Say Hello</button>
  </main>

  <!-- Footer -->
  <footer id="contact">
    <p>© 2025 Nirvana | Learning to Code</p>
  </footer>

</body>
</html>