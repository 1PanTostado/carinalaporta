<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mae Carina de Oxun - Servicio Espiritual</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Nunito:wght@300;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Nunito', sans-serif;
      background: linear-gradient(to bottom, #ffffff 0%, #e4c1f9 100%);
      color: #444;
      overflow-x: hidden;
    }

    header {
      background: linear-gradient(135deg, #aee1f9, #f9c784);
      text-align: center;
      padding: 3rem 1rem;
      position: relative;
      clip-path: ellipse(100% 80% at 50% 20%);
      color: white;
    }

    header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      font-weight: 300;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 2rem;
    }

    .perfil {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      background: #fff;
      border-radius: 1rem;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      padding: 2rem;
      align-items: center;
      margin-bottom: 2rem;
    }

    .perfil img {
      width: 180px;
      border-radius: 50%;
      border: 4px solid #f9c784;
    }

    .perfil p {
      font-size: 1.1rem;
      flex: 1;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      margin-bottom: 2rem;
    }

    .galeria img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 1rem;
      transition: transform 0.3s;
    }

    .galeria img:hover {
      transform: scale(1.05);
    }

    .whatsapp {
      text-align: center;
      margin: 2rem 0;
    }

    .whatsapp a {
      background-color: #25D366;
      color: white;
      padding: 1rem 2rem;
      border-radius: 50px;
      text-decoration: none;
      font-size: 1.2rem;
      transition: background 0.3s;
    }

    .whatsapp a:hover {
      background-color: #128C7E;
    }

    .formulario {
      background: #fff;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      margin-bottom: 2rem;
    }

    .formulario h2 {
      color: #a855f7;
      margin-bottom: 1rem;
    }

    .formulario iframe {
      width: 100%;
      height: 600px;
      border: none;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mae Carina de Oxun</h1>
    <p>"Con la sabiduría y amor de Oxún, guío tu camino hacia la armonía y la paz interior."</p>
  </header>

  <div class="container">
    <section class="perfil">
      <img src="Imagenes/perfil.jpg" alt="Foto de Carina Laporta">
      <p>"A través de la sabiduría de Oxún, te ofrezco un espacio seguro donde la paz y la prosperidad fluyen como el río. Mi misión es ayudarte a sanar, prosperar y encontrar la claridad espiritual para vivir con balance y alegría."</p>
    </section>

    <section class="galeria">
      <img src="Imagenes/camino.jpg" alt="Galería 1">
      <img src="Imagenes/asdfas.jpg" alt="Galería 2">
      <img src="Imagenes/reunion.jpg" alt="Galería 3">
      <img src="Imagenes/abrazo.jpg" alt="Galería 4">
      <img src="Imagenes/stast.jpg" alt="Galería 5">
      <img src="Imagenes/guia.jpg" alt="Galería 6">
    </section>

    <section class="whatsapp">
      <a href="https://wa.me/1234567890" target="_blank">💬 Contáctame por WhatsApp</a>
    </section>

    <section class="formulario">
      <h2>Deja tu comentario</h2>
      <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfRv5SJ4RypDmjbRimgkUaJEQ1I3gpDN1rSyTsYKmbiip60UQ/viewform?embedded=true" width="640" height="762" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>
    </section>
  </div>

  <footer>
    &copy; 2025 Carina Laporta. Todos los derechos reservados.
  </footer>
</body>
</html>
