<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #2e7d32;
      color: white;
      padding: 1em;
      text-align: center;
      position: relative;
    }
    header::before, header::after {
      content: '🌿';
      font-size: 2em;
      position: absolute;
      top: 1.2em;
    }
    header::before {
      left: 1em;
    }
    header::after {
      right: 1em;
    }
    h1 {
      font-family: 'Pacifico', cursive;
      font-size: 6em;
      margin: 0;
    }
    nav {
      background-color: #388e3c;
      display: flex;
      justify-content: center;
      gap: 1em;
      padding: 0.5em 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2em;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5em;
    }
    .producto {
      background-color: white;
      border-radius: 8px;
      padding: 1em;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .producto img {
      max-width: 100%;
      border-radius: 4px;
    }
    .producto a {
      display: inline-block;
      margin-top: 1em;
      padding: 0.5em 1em;
      background-color: #2e7d32;
      color: white;
      text-decoration: none;
      border-radius: 4px;
    }
    footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>GreenCore</h1>
    <p>El arte esta en todos lados</p>
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="productos">
    <h2>Nuestros Productos</h2>
    <div class="productos">
      <div class="producto">
        <h3>The dazzling pineapple</h3>
        <p>Lámpara frutal, con forma de piña, ideal para tu escritorio.</p>
        <a href="Thedazzlingpineapple.html">Ver más</a>
      </div>
       <div class="producto">
        <h3>MotoCycle</h3>
        <p>Figura de motocicleta.</p>
        <a href="MotoCycle.html">Ver más</a>
      </div>
      <div class="producto">
        <h3>Scorpwire</h3>
        <p>Fiegura de escorpión.</p>
        <a href="Scorpwire.html">Ver más</a>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre GreenCore</h2>
    <p>GreenCore nació con la misión de crear soluciones ecologicas. Hacemos arte a base del reciclaje.Creemos en el poder de las 3R para cambiar el mundo!</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>¿Tienes preguntas o quieres realizar un pedido? Escríbenos a <a href="mailto:greencoreofcl@gmail.com">greencoreofcl@gmail.com</a> o encuentranos en instagram como @greencore_ofcl.</p>
  </section>

  <section id="Equipo">
    <h2>Colaboradores</h2>
    <p>Hernandez Tevera Luisa Margarita, Cortes Ortiz Maria Teresa,Hernandez Escobar Roberto Carlos, Hernandez Abadia Celia Abigail, Toalá Vázquez Diego </p>
  </section>

  <footer>
    <p>&copy; 2025 GreenCore.¡JAGUARES!.</p>
  </footer>
</body>
</html>
