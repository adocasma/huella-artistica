<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Sitio Web Minimalista</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <h1>Mi Sitio Web</h1>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Acerca de</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <section class="hero">
      <div class="container">
        <h1>Bienvenido a mi sitio web</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fringilla auctor mi, ac eleifend neque interdum non.</p>
      </div>
    </section>
    
    <section class="content">
      <div class="container">
        <h2>Acerca de</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse fringilla auctor mi, ac eleifend neque interdum non. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>
      </div>
    </section>
    
    <section class="content">
      <div class="container">
        <h2>Contacto</h2>
        <form>
          <label for="name">Nombre:</label>
          <input type="text" id="name" name="name">
          
          <label for="email">Email:</label>
          <input type="email" id="email" name="email">
          
          <label for="message">Mensaje:</label>
          <textarea id="message" name="message"></textarea>
          
          <input type="submit" value="Enviar">
        </form>
      </div>
    </section>
  </main>
  
  <footer>
    <p>Derechos de autor &copy; 2023 Mi Sitio Web. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
