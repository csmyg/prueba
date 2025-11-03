<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Página Personal</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f2f4f8;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #0077b6;
      color: white;
      text-align: center;
      padding: 2rem 0;
    }

    header h1 {
      font-size: 2.5rem;
    }

    nav {
      background-color: #023e8a;
      text-align: center;
      padding: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 3rem 10%;
    }

    .proyectos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
    }

    footer {
      background-color: #023e8a;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 3rem;
    }

    .contacto a {
      color: #0077b6;
      text-decoration: none;
      font-weight: bold;
    }

    .contacto a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>¡Hola! Soy ChatGPT 😎</h1>
    <p>Desarrollador creativo, amante del código y la inteligencia artificial</p>
  </header>

  <nav>
    <a href="#sobre-mi">Sobre mí</a>
    <a href="#proyectos">Proyectos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="sobre-mi">
    <h2>Sobre mí</h2>
    <p>Soy un asistente virtual con pasión por crear ideas, escribir código y ayudar a las personas a aprender cosas nuevas. Me encanta experimentar con diseño, desarrollo web y herramientas modernas.</p>
  </section>

  <section id="proyectos">
    <h2>Mis proyectos</h2>
    <div class="proyectos">
      <div class="card">
        <h3>Blog de tecnología</h3>
        <p>Un espacio donde comparto ideas y tutoriales sobre programación, IA y diseño.</p>
      </div>
      <div class="card">
        <h3>App de productividad</h3>
        <p>Una aplicación simple para organizar tus tareas y mejorar tu enfoque diario.</p>
      </div>
      <div class="card">
        <h3>Página creativa</h3>
        <p>Un proyecto experimental de diseño web minimalista y animaciones suaves.</p>      
      </div>
    </div>
  </section>

  <section id="contacto" class="contacto">
    <h2>Contacto</h2>
    <p>¿Quieres charlar o colaborar? Escríbeme en <a href="mailto:chatgpt@example.com">chatgpt@example.com</a></p>
  </section>

  <footer>
    <p>© 2025 ChatGPT — Creado con ❤️ y HTML + CSS</p>
  </footer>
</body>
</html>
