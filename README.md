# ciucholandia<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sklep z Ubraniami</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
    }

    header {
      background-color: #000;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #222;
      padding: 10px 20px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: #f0c040;
    }

    section {
      padding: 60px 20px;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1521334884684-d80222895322') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 3em;
      margin: 0;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .product {
      border: 1px solid #ddd;
      border-radius: 8px;
      overflow: hidden;
      text-align: center;
      transition: box-shadow 0.3s;
    }

    .product:hover {
      box-shadow: 0 2px 12px rgba(0, 0, 0, 0.2);
    }

    .product img {
      width: 100%;
      height: auto;
    }

    .product h3 {
      margin: 10px 0;
    }

    .contact-form {
      max-width: 500px;
      margin: auto;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    .contact-form button {
      padding: 12px 20px;
      background-color: #000;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #444;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #000;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>ModaNow – Sklep z Ubraniami</h1>
    <p>Styl, który pokochasz</p>
  </header>

  <nav>
    <a href="#home">Strona Główna</a>
    <a href="#contact">Kontakt</a>
  </nav>

  <section id="home" class="hero">
    <h1>Nowa Kolekcja 2025</h1>
    <p>Odkryj naszą najnowszą ofertę</p>
  </section>

  <section>
    <h2 style="text-align:center;">Nasze Produkty</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246" alt="Koszulka">
        <h3>Koszulka Basic</h3>
        <p>49,99 zł</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1552374196-c4e7ffc6e126" alt="Bluza">
        <h3>Bluza Oversize</h3>
        <p>99,99 zł</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1602810317172-c6b08f6c4b3f" alt="Spodnie">
        <h3>Spodnie Jeans</h3>
        <p>129,99 zł</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2 style="text-align:center;">Kontakt</h2>
    <div class="contact-form">
      <form>
        <input type="text" placeholder="Imię i nazwisko" required />
        <input type="email" placeholder="Adres e-mail" required />
        <textarea placeholder="Twoja wiadomość" rows="5" required></textarea>
        <button type="submit">Wyślij</button>
      </form>
    </div>
  </section>

  <footer>
    &copy; 2025 ModaNow. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
