# Ethan-Naugle.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ethan Naugle | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Ethan Naugle</h1>
      <p>9th Grader • Aspiring Developer • Creative Student</p>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>
        Hi! I'm Ethan, a 9th grader interested in coding, science, and creative projects. I love learning new things, building apps, and participating in my school's robotics club.
      </p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>
          <strong>Science Fair App</strong> – A simple web app to track science project progress.
        </li>
        <li>
          <strong>Math Quiz Game</strong> – A Python quiz that helps you practice math.
        </li>
        <li>
          <strong>Art Portfolio Website</strong> – My digital art and designs.
        </li>
      </ul>
    </section>

    <section id="skills">
      <h2>Skills & Interests</h2>
      <ul>
        <li>HTML, CSS, Python (beginner)</li>
        <li>Robotics Club Member</li>
        <li>Science Experiments, Drawing</li>
      </ul>
    </section>

    <section id="goals">
      <h2>Goals</h2>
      <ul>
        <li>Learn JavaScript and build my own website</li>
        <li>Join a hackathon</li>
        <li>Contribute to open source</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <ul>
        <li>Email: <a href="mailto:ethannaugle02@gmail.com">ethannaugle02@gmail.com</a></li>
        <li><a href="https://delranschools.org" target="_blank">My School Website</a></li>
      </ul>
    </section>

    <footer>
      <p>© 2025 Ethan Naugle</p>
    </footer>
  </div>
</body>
</html>
/* Minimalist Portfolio Styles */
body {
  background: #f9f9f9;
  font-family: 'Segoe UI', 'Arial', sans-serif;
  color: #222;
  margin: 0;
  padding: 0;
}
.container {
  max-width: 700px;
  margin: 40px auto;
  background: #fff;
  padding: 2em 2.5em;
  border-radius: 12px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.07);
}
header, footer {
  text-align: center;
}
header h1 {
  margin-bottom: 0.2em;
  font-size: 2.4em;
  letter-spacing: 0.03em;
}
header p {
  margin-top: 0;
  color: #555;
  font-size: 1.1em;
}
section {
  margin-top: 2em;
}
section h2 {
  border-bottom: 2px solid #ececec;
  padding-bottom: 0.3em;
  margin-bottom: 1em;
  font-size: 1.4em;
  color: #333;
}
ul {
  padding-left: 1.2em;
}
li {
  margin-bottom: 0.6em;
  font-size: 1.05em;
}
a {
  color: #0366d6;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
footer {
  margin-top: 2.5em;
  color: #aaa;
  font-size: 0.95em;
}
@media (max-width: 600px) {
  .container {
    padding: 1em 0.7em;
  }
  header h1 {
    font-size: 1.6em;
  }
}
