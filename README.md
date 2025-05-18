<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Radio Stereo M</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #1e3c72, #2a5298);
      color: white;
      text-align: center;
      padding: 20px;
    }

    header {
      margin-bottom: 30px;
    }

    img.logo {
      max-width: 150px;
      margin-top: 20px;
    }

    h1 {
      font-size: 2.5em;
      margin: 0.2em 0;
    }

    .player {
      margin-top: 40px;
    }

    audio {
      width: 100%;
      max-width: 400px;
      outline: none;
    }

    footer {
      margin-top: 50px;
      font-size: 0.9em;
      color: #ccc;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo Radio Stereo M" class="logo" />
    <h1>Radio Stereo M</h1>
    <p>¡La radio que te gusta, ahora en línea!</p>
  </header>

  <section class="player">
    <h2>Escúchanos en vivo</h2>
    <audio controls autoplay>
      <source src="AQUÍ_TU_LINK_DE_STREAMING" type="audio/mpeg" />
      Tu navegador no soporta el audio en línea.
    </audio>
  </section>

  <footer>
    &copy; 2025 Radio Stereo M. Todos los derechos reservados.
  </footer>
</body>
</html>
