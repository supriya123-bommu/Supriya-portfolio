<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Supriya Portfolio</title>


  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
  
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #f9f9f9, #ffffff);
      color: #333;
      margin: 0;
      padding: 0;
    }

  
    header {
      background: linear-gradient(90deg, #ff9a9e, #fad0c4);
      text-align: center;
      padding: 40px 20px;
      color: white;
    }

    header h1 {
      font-family: 'Pacifico', cursive;
      font-size: 3rem;
      margin: 0;
      color: #fff;
      text-shadow: 2px 2px 4px #00000020;
    }

    header p {
      font-size: 1.2rem;
      font-weight: 500;
      margin-top: 10px;
      color: #fffbe0;
    }

    
    .container {
      max-width: 960px;
      margin: auto;
      padding: 30px 20px;
    }

    
    .section-title {
      font-size: 2.2rem;
      font-weight: bold;
      color: #ff6f61;
      border-bottom: 3px solid #ffb347;
      padding-bottom: 5px;
      margin-bottom: 15px;
      font-family: 'Poppins', sans-serif;
    }

    
    p {
      font-size: 1.05rem;
      line-height: 1.7;
      color: #444;
    }


    strong {
      color: #8e44ad;
    }

    
    a {
      color: #1abc9c;
      font-weight: bold;
      text-decoration: none;
    }

    a:hover {
      color: #16a085;
      text-decoration: underline;
    }

    
    button {
      margin-top: 20px;
      background-color: #ff6f61;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s ease;
      box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.1);
    }

    button:hover {
      background-color: #e65c50;
    }

    
    footer {
      background-color: #f2f2f2;
      text-align: center;
      padding: 20px;
      color: #777;
      font-size: 0.95rem;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Supriya Bommu</h1>
    <p>Creative Web Developer | MCA Graduate</p>
  </header>

  <div class="container">
    
    <section>
      <h2 class="section-title">🌟 About Me</h2>
      <p>Hello! I’m <strong>Supriya</strong>, a passionate web developer with a Master’s in Computer Applications. I love building clean, responsive websites and bringing ideas to life with design and code.</p>
    </section>

    <!-- PROJECTS SECTION -->
    <section>
      <h2 class="section-title">💼 Projects</h2>
      <p><strong>Portfolio Website:</strong> A personal website made using HTML, CSS, and GitHub Pages. <br />
        🔗 <a href="https://supriya123-bommu.github.io/Supriya-portfolio/" target="_blank">View Live</a>
      </p>
    </section>

    <!-- CONTACT SECTION -->
    <section>
      <h2 class="section-title">📫 Contact</h2>
      <p>Email: <a href="mailto:supriya@example.com">supriya@example.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/supriya" target="_blank">linkedin.com/in/supriya</a></p>
      <button onclick="window.location.href='mailto:supriya@example.com'">📨 Contact Me</button>
    </section>
  </div>

  <footer>
    &copy; 2025 Supriya Bommu. Crafted with ❤️ and creativity.
  </footer>

</body>
</html>
