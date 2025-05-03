<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UrbanWear</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f4;
    }
    header {
      background-color: #000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
    }
    .hero {
      height: 80vh;
      background-image: url('https://images.unsplash.com/photo-1521334884684-d80222895322');
      background-size: cover;
      background-position: center;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
      font-size: 3em;
      text-align: center;
    }
    .about, .products {
      padding: 50px 20px;
      text-align: center;
    }
    .products h2 {
      margin-bottom: 30px;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .product img {
      width: 100%;
      border-radius: 8px;
      transition: transform 0.3s ease;
      object-fit: cover;
    }

    .product img:hover {
      transform: scale(1.1);
    }
    .product img[alt="Hoodie"] {
      height: 730px;
    }
    .product img[alt="shoes"] {
      height: 730px;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>UrbanWear</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <div>Elevate Your Street Style</div>
  </section>

  <section class="about" id="about">
    <h2>About Us</h2>
    <p>UrbanWear is a bold streetwear brand combining style and comfort. We bring you the freshest looks straight from the heart of urban culture.</p>
  </section>

  <section class="products" id="products">
    <h2>Featured Products</h2>
    <div class="product-grid">
      <div class="product">
      <a href="baggy.html"> <img src="bsat-southside-embroidery-baggy-jeans-indigo-blue-limited-edition.jpg" alt="baggy jeans"></a> 
        <h3>baggy jeans</h3>
        <p>4500dzd</p>
      </div>
      <div class="product">
        <img src="1bf58838-40d9-4591-866e-ca381a446e8d.png" alt="Hoodie">
        <h3>Urban Hoodie</h3>
        <p>5000dzd</p>
      </div>
      <div class="product">
        <img src="d48d5088-f7c6-47af-9e5b-a5ff88d0e798.png" alt="shoes">
        <h3>shoes</h3>
        <p>12000dzd</p>
      </div>
    </div>
  </section>

  <footer id="contact">
    <p>Follow us on Instagram @urbanwear • Contact: info@urbanwear.com</p>
  </footer>
</body>
</html>
