<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alex Styles Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #fafafa;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(90deg, red, blue, yellow);
      color: white;
      text-align: center;
      padding: 1.5rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    nav {
      margin-top: 0.5rem;
    }

    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: yellow;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #222;
      margin-bottom: 1rem;
    }

    .portfolio {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      width: 200px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #eee;
      margin-top: 2rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Alex Styles</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m Alex Styles, a graphic designer who loves creating clean and colorful designs. Here are some of my projects.</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="card">Project 1</div>
      <div class="card">Project 2</div>
      <div class="card">Project 3</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: alex.styles@example.com</p>
  </section>

  <footer>
    <p>© 2025 Alex Styles</p>
  </footer>

</body>
</html>
