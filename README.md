<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MovezzShop - Catálogo de Zapatillas Exclusivas</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      background: #0d47a1; /* Fondo azul oscuro */
      color: #fff;
      line-height: 1.6;
      /* Imagen de fondo con temática de tiburones */
      background-image: url('https://source.unsplash.com/1600x900/?shark');
      background-size: cover;
      background-attachment: fixed;
      background-blend-mode: overlay;
    }
    header {
      background: rgba(0,0,0,0.6);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    nav {
      background: rgba(0,0,0,0.7);
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      background: rgba(0,0,0,0.5);
      margin: 20px auto;
      max-width: 1000px;
      border-radius: 8px;
    }
    section h2 {
      margin-bottom: 20px;
      border-bottom: 2px solid #fff;
      display: inline-block;
      padding-bottom: 5px;
    }
    .product {
      display: flex;
      flex-wrap: wrap;
      margin-bottom: 20px;
      border-bottom: 1px solid #fff;
      padding-bottom: 20px;
    }
    .product img {
      max-width: 300px;
      width: 100%;
      border-radius: 8px;
      margin-right: 20px;
    }
    .product-details {
      flex: 1;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.7);
    }
    /* Responsive */
    @media (max-width: 768px) {
      .product {
        flex-direction: column;
        text-align: center;
      }
      .product img {
        margin: 0 auto 20px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>MovezzShop</h1>
    <p>Catálogo de Zapatillas Exclusivas</p>
  </header>
  <nav>
    <a href="#introduccion">Introducción</a>
    <a href="#nike">Nike</a>
    <a href="#adidas">Adidas</a>
    <a href="#balenciaga">Balenciaga</a>
    <a href="#gucci">Gucci</a>
    <a href="#versace">Versace</a>
    <a href="#louisvuitton">Louis Vuitton</a>
    <a href="#supreme">Supreme</a>
    <a href="#contacto">Contacto</a>
  </nav>
  
  <!-- Sección de Introducción -->
  <section id="introduccion">
    <h2>Introducción</h2>
    <p>Bienvenido al catálogo de zapatillas de MovezzShop. Aquí encontrarás una selección exclusiva de las mejores zapatillas de marcas reconocidas y de lujo. Explora cada sección para descubrir modelos únicos, con imágenes oficiales y detalles completos de tallas para Europa, Asia y Estados Unidos.</p>
  </section>
  
  <!-- Sección Nike -->
  <section id="nike">
    <h2>Nike</h2>
    <div class="product">
      <img src="https://tse2.mm.bing.net/th?id=OIP.jAfxTdSPx5u2fvoSXc-zmQHaFP&pid=Api" alt="Nike Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Air Max 270</li>
          <li>Air Force One</li>
          <li>React Infinity Run</li>
          <li>Air Jordan (ediciones limitadas)</li>
          <li>ZoomX Vaporfly</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 39, 40, 41, 42, 43, 44, 45</p>
        <p>Asia: Aproximadamente 250, 255, 260, 265, 270, 275, 280</p>
        <p>US: 6, 7, 8, 9, 10, 11, 12</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Adidas -->
  <section id="adidas">
    <h2>Adidas</h2>
    <div class="product">
      <img src="https://tse2.mm.bing.net/th?id=OIP.P0AZwYnE9B6kSPZkX16HFQHaFf&pid=Api" alt="Adidas Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Ultraboost</li>
          <li>Superstar</li>
          <li>NMD</li>
          <li>Stan Smith</li>
          <li>Gazelle</li>
          <li>Yeezy Boost 350</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 38 a 46</p>
        <p>Asia: Aproximadamente 245 a 285</p>
        <p>US: 5 a 12</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Balenciaga -->
  <section id="balenciaga">
    <h2>Balenciaga</h2>
    <div class="product">
      <img src="https://tse3.mm.bing.net/th?id=OIP.S1WQWsmHD9CjznQ0rTYFswHaL2&pid=Api" alt="Balenciaga Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Triple S</li>
          <li>Speed Trainer</li>
          <li>Ediciones especiales y colaboraciones</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 39 a 45</p>
        <p>Asia: Conversión ajustada</p>
        <p>US: 6 a 11</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Gucci -->
  <section id="gucci">
    <h2>Gucci</h2>
    <div class="product">
      <img src="https://tse3.mm.bing.net/th?id=OIP.Eg3-FIZeXZ7RdRHclMR94wHaEy&pid=Api" alt="Gucci Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Gucci Ace</li>
          <li>Gucci Rhyton</li>
          <li>Ediciones exclusivas</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 38 a 44</p>
        <p>Asia: Conversión equivalente</p>
        <p>US: 5 a 11</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Versace -->
  <section id="versace">
    <h2>Versace</h2>
    <div class="product">
      <img src="https://tse2.mm.bing.net/th?id=OIP.uiZpxoawY-lrzDPyx3JGqQHaJ4&pid=Api" alt="Versace Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Versace Chain Reaction</li>
          <li>Diseños exclusivos y lujosos</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 38 a 44</p>
        <p>Asia: Sistema propio de conversión</p>
        <p>US: 5 a 11</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Louis Vuitton -->
  <section id="louisvuitton">
    <h2>Louis Vuitton</h2>
    <div class="product">
      <img src="https://via.placeholder.com/300x200.png?text=Louis+Vuitton" alt="Louis Vuitton Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>LV Archlight</li>
          <li>LV Trainer</li>
          <li>Otras ediciones exclusivas</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 38 a 44</p>
        <p>Asia: Conversión estandarizada</p>
        <p>US: 5 a 11</p>
      </div>
    </div>
  </section>
  
  <!-- Sección Supreme -->
  <section id="supreme">
    <h2>Supreme</h2>
    <div class="product">
      <img src="https://tse2.mm.bing.net/th?id=OIP.P0AZwYnE9B6kSPZkX16HFQHaFf&pid=Api" alt="Supreme Zapatillas">
      <div class="product-details">
        <h3>Modelos Destacados:</h3>
        <ul>
          <li>Colaboraciones exclusivas</li>
          <li>Ediciones limitadas</li>
          <li>Diseños urbanos</li>
        </ul>
        <p><strong>Tallas Disponibles:</strong></p>
        <p>Europa: 38 a 46</p>
        <p>Asia: Conversión correspondiente</p>
        <p>US: 5 a 12</p>
      </div>
    </div>
  </section>
  
  <!-- Sección de Contacto -->
  <section id="contacto">
    <h2>Contacto y Redes</h2>
    <p>Para más información, contáctanos en:</p>
    <ul>
      <li>Teléfono: +34 123 456 789</li>
      <li>Email: info@movezzshop.com</li>
      <li>Sitio Web: www.movezzshop.com</li>
    </ul>
    <p>Síguenos en redes sociales:</p>
    <ul>
      <li>Instagram</li>
      <li>Facebook</li>
      <li>Twitter</li>
    </ul>
  </section>
  
  <footer>
    <p>&copy; 2025 MovezzShop. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
