<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Maderería Local - Calidad en Madera</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</head>
<body>

  <!-- Navegación -->
  <nav class="container-fluid">
    <ul>
      <li><strong>Maderería Local</strong></li>
    </ul>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#productos">Productos</a></li>
      <li><a href="#servicios">Servicios</a></li>
      <li><a href="#nosotros">Nosotros</a></li>
      <li><a href="#contacto" role="button">Contacto</a></li>
    </ul>
  </nav>

  <!-- Contenido Principal -->
  <main class="container">
    
    <!-- Sección: Inicio -->
    <section id="inicio">
      <hgroup>
        <h2>Bienvenidos a Maderería Local</h2>
        <h3>Su mejor opción en productos de madera de alta calidad</h3>
      </hgroup>
      <p>Ofrecemos una amplia variedad de maderas y productos derivados, con el compromiso de brindar un servicio excepcional a nuestros clientes.</p>
      <figure>
        <img src="https://source.unsplash.com/featured/?wood" alt="Imagen de madera">
        <figcaption><a href="https://unsplash.com/" target="_blank">Imagen ilustrativa de madera</a></figcaption>
      </figure>
    </section>
    
    <!-- Sección: Productos -->
    <section id="productos">
      <hgroup>
        <h2>Nuestros Productos</h2>
        <h3>Calidad y variedad</h3>
      </hgroup>
      <p>En nuestra maderería ofrecemos:</p>
      <ul>
        <li>Madera tratada</li>
        <li>Madera dura y blanda</li>
        <li>Tableros de madera y contrachapado</li>
        <li>Accesorios y herramientas para carpintería</li>
      </ul>
    </section>
    
    <!-- Sección: Servicios -->
    <section id="servicios">
      <hgroup>
        <h2>Servicios</h2>
        <h3>Soluciones personalizadas</h3>
      </hgroup>
      <p>Ofrecemos servicios adicionales para ayudarle a completar su proyecto:</p>
      <ul>
        <li>Corte de madera a medida</li>
        <li>Entrega a domicilio</li>
        <li>Asesoría en proyectos de carpintería</li>
      </ul>
    </section>

    <!-- Sección: Nosotros -->
    <section id="nosotros">
      <hgroup>
        <h2>Sobre Nosotros</h2>
        <h3>Compromiso y experiencia</h3>
      </hgroup>
      <p>Somos una maderería con más de 20 años de experiencia, comprometidos con la calidad de nuestros productos y la satisfacción de nuestros clientes. Nuestro equipo de expertos está siempre dispuesto a ayudarle a encontrar la mejor solución para su proyecto.</p>
    </section>

    <!-- Sección: Contacto -->
    <section id="contacto" aria-label="Contacto">
      <hgroup>
        <h2>Contacto</h2>
        <h3>Estamos aquí para ayudarte</h3>
      </hgroup>
      <form class="grid">
        <input type="text" id="nombre" name="nombre" placeholder="Nombre" aria-label="Nombre" required>
        <input type="email" id="email" name="email" placeholder="Correo electrónico" aria-label="Correo electrónico" required>
        <textarea id="mensaje" name="mensaje" placeholder="Escribe tu mensaje aquí" aria-label="Mensaje" required></textarea>
        <button type="submit" onclick="event.preventDefault()">Enviar Mensaje</button>
      </form>
    </section>

  </main>

  <!-- Pie de página -->
  <footer class="container">
    <small>
      <a href="#inicio">Inicio</a> • <a href="#productos">Productos</a> • <a href="#contacto">Contacto</a>
    </small>
    <p>&copy; 2024 Maderería Local - Todos los derechos reservados</p>
  </footer>

</body>
</html>
