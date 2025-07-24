<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PIER de México</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1581093588401-ecf063763d25') no-repeat center center/cover;
      color: white;
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
    }
    nav {
      background-color: #004080;
      padding: 15px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
    }
    footer {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 15px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    ul li::before {
      content: "\2714\0020";
      color: #004080;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 15px;
      padding: 10px;
      font-size: 1em;
    }
    form button {
      background-color: #004080;
      color: white;
      padding: 10px;
      font-size: 1em;
      border: none;
      cursor: pointer;
    }
    .socials {
      margin-top: 20px;
    }
    .socials a {
      margin: 0 10px;
      color: #004080;
      font-size: 1.5em;
      text-decoration: none;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      text-align: center;
      font-size: 30px;
      line-height: 60px;
      z-index: 1000;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>PIER de México</h1>
    <p>Especialistas en Inyección de Plástico</p>
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#servicios">Servicios</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio" class="container">
    <h2>Bienvenidos a PIER de México</h2>
    <p>Somos una empresa mexicana dedicada a la inyección de plástico con altos estándares de calidad, tecnología y compromiso.</p>
  </section>

  <section id="servicios" class="container">
    <h2>Servicios</h2>
    <ul>
      <li>Maquila de inyección de plástico</li>
      <li>Diseño y modificación de moldes</li>
      <li>Producción en alto y bajo volumen</li>
      <li>Control de calidad y empaque personalizado</li>
    </ul>
  </section>

  <section id="nosotros" class="container">
    <h2>Quiénes Somos</h2>
    <p>PIER de México es una empresa orgullosamente mexicana con experiencia en el sector plástico. Enfocados en la innovación, precisión y satisfacción del cliente.</p>
  </section>

  <section id="contacto" class="container">
    <h2>Contacto</h2>
    <form action="#" method="post">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu correo" required>
      <textarea name="mensaje" rows="5" placeholder="Escribe tu mensaje aquí" required></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
    <div class="socials">
      <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
      <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
    </div>
    <p>Dirección: Celaya, Guanajuato, México</p>
    <p>Correo: contacto@pierdemexico.com</p>
    <p>Teléfono: +52 461 123 4567</p>
  </section>

  <footer>
    <p>&copy; 2025 PIER de México. Todos los derechos reservados.</p>
  </footer>

  <a href="https://wa.me/5214611234567" class="whatsapp" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>
</body>
</html>
