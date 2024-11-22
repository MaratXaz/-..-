HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Webpage Layout</title>
  <link rel="stylesheet" href="марат.css">
</head>
<body>
  <header class="header">
    <div class="logo">whitesquare</div>
    <nav class="nav">
      <a href="#">Home</a>
      <a href="#">About Us</a>
      <a href="#">Services</a>
      <a href="#">Products</a>
      <a href="#">Contact</a>
    </nav>
  </header>
  <main class="main">
    <section class="intro">
      <h1>Мой сайт</h1>
      <p>Также мобильное мультимедийное представление multimedia performance</p>
    </section>
    <section class="features">
      <div class="feature">Характеристики</div>
      <div class="feature">Another Feature</div>
      <div class="feature">More Features</div>
    </section>
    <section class="details">
      <article>
        <h2>Our Plans</h2>
        <p>Получить 15 баллов по  HTML</p>
      </article>
      <article>
        <h2>24/7 Support</h2>
        <p>на связи</p>
      </article>
      <article>
        <h2>Our Clients</h2>
        <p1>Стив Джобс</p1> <br>
        <p2>Джюльетта Абугалиевна</p2>
      </article>
    </section>
  </main>
  <footer class="footer">
    <p>© whitesquare | Sitemap | Social Media Links</p>
  </footer>
</body>
</html>
Css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    background-color: #f4f4f4;
  }
  
  .nav a {
    margin: 0 1rem;
    text-decoration: none;
    color: #333;
  }
  
  .main {
    padding: 2rem;
  }
  
  .intro {
    text-align: center;
    margin-bottom: 2rem;
  }
  
  .features {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin-bottom: 2rem;
  }
  
  .feature {
    padding: 1rem;
    background-color: #eaeaea;
    text-align: center;
  }
  
  .details {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
  }
  
  article {
    padding: 1rem;
    background-color: #f9f9f9;
  }
  
  .footer {
    text-align: center;
    padding: 1rem;
    background-color: #f4f4f4;
    margin-top: 2rem;
  }
