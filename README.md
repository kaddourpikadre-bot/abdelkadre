# abdelkadre
My personal website
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>موقعي الشخصي - عبد القادر</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      color: #333;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #1e90ff;
      color: white;
      padding: 40px 0;
    }
    h1 {
      margin: 0;
      font-size: 2.8em;
    }
    p {
      font-size: 1.3em;
    }
    section {
      padding: 40px 20px;
    }
    .projects, .social {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 20px;
    }
    .project, .social a {
      background-color: white;
      padding: 20px 30px;
      border-radius: 10px;
      box-shadow: 0 3px 6px rgba(0,0,0,0.1);
      text-decoration: none;
      color: #1e90ff;
      font-weight: bold;
      transition: all 0.3s;
    }
    .project:hover, .social a:hover {
      background-color: #1e90ff;
      color: white;
    }
    footer {
      margin: 40px 0;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>أنا عبد القادر</h1>
    <p>مبرمج تطبيقات متعددة المنصات</p>
  </header>

  <section class="projects">
    <h2>مشاريعي</h2>
    <div class="projects">
      <a class="project" href="#" target="_blank">مشروع 1</a>
      <a class="project" href="#" target="_blank">مشروع 2</a>
      <a class="project" href="#" target="_blank">مشروع 3</a>
      <a class="project" href="#" target="_blank">مشروع 4</a>
    </div>
  </section>

  <section class="social">
    <h2>تواصل معي</h2>
    <div class="social">
      <a href="https://github.com/kaddourpikadre-bot" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/in/kaddourpikadre" target="_blank">LinkedIn</a>
      <a href="https://twitter.com/" target="_blank">Twitter</a>
      <a href="mailto:your-email@example.com" target="_blank">Email</a>
    </div>
  </section>

  <footer>
    &copy; 2025 عبد القادر
  </footer>
</body>
</html>
