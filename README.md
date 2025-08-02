# pagina-romantica
para mi linda novia 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Para ti 💖</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ffe6f0, #fff6fb);
      color: #4b0039;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .container {
      max-width: 600px;
      padding: 20px;
      text-align: center;
    }
    h1 {
      animation: fadeInDown 1s ease-out;
    }
    .phrase {
      font-size: 1.3rem;
      margin: 25px 0;
      opacity: 0;
      animation: fadeInUp 1s ease forwards;
    }
    .phrase:nth-child(1) { animation-delay: 1s; }
    .phrase:nth-child(2) { animation-delay: 2.5s; }
    .phrase:nth-child(3) { animation-delay: 4s; }
    .phrase:nth-child(4) { animation-delay: 5.5s; }
    .phrase:nth-child(5) { animation-delay: 7s; }

    .gallery {
      display: grid;
      grid-template-columns: 1fr;
      gap: 15px;
      margin-top: 30px;
    }
    .gallery img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      opacity: 0;
      animation: fadeIn 1s ease forwards;
    }
    .gallery img:nth-child(1) { animation-delay: 8.5s; }
    .gallery img:nth-child(2) { animation-delay: 10s; }
    .gallery img:nth-child(3) { animation-delay: 11.5s; }
    .gallery img:nth-child(4) { animation-delay: 13s; }
    .gallery img:nth-child(5) { animation-delay: 14.5s; }

    .footer {
      margin-top: 40px;
      font-style: italic;
      font-size: 1.1rem;
      animation: fadeInUp 1s ease forwards;
      animation-delay: 16s;
      opacity: 0;
    }

    iframe {
      margin-top: 25px;
      border: none;
      border-radius: 12px;
      width: 100%;
      max-width: 560px;
      height: 315px;
      animation: fadeInUp 1s ease forwards;
      animation-delay: 17s;
      opacity: 0;
    }

    @keyframes fadeInUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeInDown {
      from { transform: translateY(-20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🌸 Para ti, con mucho amor 🌸</h1>

    <div class="phrase">Desde que llegaste, mi vida cambió de color.</div>
    <div class="phrase">Cada día contigo es mi nuevo favorito.</div>
    <div class="phrase">Tu sonrisa es mi canción favorita.</div>
    <div class="phrase">Eres mi lugar seguro en un mundo caótico.</div>
    <div class="phrase">Gracias por existir. Te amo.</div>

    <div class="gallery">
      <img src="foto1.jpg" alt="Foto 1" />
      <img src="foto2.jpg" alt="Foto 2" />
      <img src="foto3.jpg" alt="Foto 3" />
      <img src="foto4.jpg" alt="Foto 4" />
      <img src="foto5.jpg" alt="Foto 5" />
    </div>

    <iframe src="https://www.youtube.com/embed/OskXF3s0UT8?autoplay=1&mute=0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

    <div class="footer">
      Con todo lo que siento por ti :3
    </div>
  </div>
</body>
</html>
