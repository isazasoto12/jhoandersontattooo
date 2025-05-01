<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>jhoandersontattoo store</title>
  <link href="https://fonts.googleapis.com/css2?family=Libre+Barcode+128+Text&family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #121212;
      color: #f4f4f4;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }
    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      text-align: center;
    }
    .logo {
      max-width: 300px;
      margin: 2rem auto;
      filter: drop-shadow(0 0 10px #e91e63);
      transition: transform 0.3s ease, filter 0.3s ease;
    }
    .logo:hover {
      transform: scale(1.05);
      filter: drop-shadow(0 0 15px #ff4081);
    }
    .container {
      background: #1e1e1e;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
      max-width: 400px;
      width: 90%;
      box-sizing: border-box;
    }
    label {
      display: block;
      margin: 0.5rem 0 0.25rem;
    }
    select, input {
      width: 100%;
      padding: 0.5rem;
      border: none;
      border-radius: 8px;
      margin-bottom: 1rem;
    }
    .resultado {
      text-align: center;
      font-size: 1.2rem;
      margin-top: 1rem;
      background: #2c2c2c;
      padding: 1rem;
      border-radius: 10px;
    }
    button {
      width: 100%;
      padding: 0.75rem;
      background: #e91e63;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background: #c2185b;
    }
    .contact-barcode {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
      margin: 3rem 1rem;
      width: 100%;
      max-width: 1200px;
      box-sizing: border-box;
    }
    .contact-item {
      background: #1e1e1e;
      padding: 1rem;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      text-align: center;
    }
    .contact-item img.icon {
      width: 40px;
      height: 40px;
      margin-bottom: 0.5rem;
    }
    .barcode {
      margin-top: 0.5rem;
      background: #fff;
      padding: 0.5rem;
      border-radius: 8px;
      width: 100%;
    }
    .agendar-cita {
      margin-top: 3rem;
      text-align: center;
    }
    .agendar-cita h2 {
      margin-bottom: 1rem;
    }
    .agendar-cita a {
      display: inline-block;
      margin: 0.5rem;
      text-decoration: none;
      color: white;
      background-color: #e91e63;
      padding: 0.75rem 1.5rem;
      border-radius: 8px;
      transition: background-color 0.3s;
    }
    .agendar-cita a:hover {
      background-color: #c2185b;
    }
    .galeria {
      margin-top: 4rem;
      width: 90%;
      max-width: 1000px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .galeria img {
      width: 100%;
      border-radius: 10px;
      object-fit: cover;
      transition: transform 0.3s;
    }
    .galeria img:hover {
      transform: scale(1.05);
    }
    @media (max-width: 600px) {
      .logo {
        max-width: 80%;
      }
      .container {
        padding: 1rem;
      }
      .agendar-cita a {
        width: 90%;
        padding: 1rem;
        font-size: 1rem;
      }
      .contact-barcode {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <img src="./038b4bed-5077-4ff9-ad5e-eed816c0b7b7.png" alt="Logo Tattoo" class="logo">
  <div class="container">
    <h1>jhoandersontattoo store</h1>
    <form id="formulario">
      <label for="tamano">Tamaño</label>
      <select id="tamano">
        <option value="50">Pequeño</option>
        <option value="100">Mediano</option>
        <option value="200">Grande</option>
      </select>

      <label for="estilo">Estilo</label>
      <select id="estilo">
        <option value="1">Minimalista</option>
        <option value="1.5">Tradicional</option>
        <option value="2">Realismo</option>
      </select>

      <label for="zona">Zona del cuerpo</label>
      <select id="zona">
        <option value="1">Brazo</option>
        <option value="1.2">Espalda</option>
        <option value="1.5">Cuello / Mano</option>
      </select>

      <label for="detalle">Nivel de detalle</label>
      <select id="detalle">
        <option value="1">Bajo</option>
        <option value="1.3">Medio</option>
        <option value="1.6">Alto</option>
      </select>

      <button type="submit">Cotizar</button>
    </form>
    <div class="resultado" id="resultado">
      Ingresa los detalles para cotizar.
    </div>
  </div>

  <div class="agendar-cita">
    <h2>Agendar una cita</h2>
    <a href="https://wa.me/32456319092" target="_blank">WhatsApp</a>
    <a href="mailto:jhoanfreitez@gmail.com">Correo</a>
    <a href="https://instagram.com/jhoandersontattoo" target="_blank">Instagram</a>
    <a href="https://www.facebook.com/jhoanderson.freitez?mibextid=wwXIfr" target="_blank">Facebook</a>
  </div>

  <div class="contact-barcode">
    <div class="contact-item">
      <a href="https://wa.me/32456319092" target="_blank">
        <img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
      </a>
      <div>+32456319092</div>
      <img class="barcode" src="https://barcode.tec-it.com/barcode.ashx?data=%2B32456319092&code=Code128&translate-esc=true" alt="Código WhatsApp">
    </div>
    <div class="contact-item">
      <a href="https://instagram.com/jhoandersontattoo" target="_blank">
        <img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
      </a>
      <div>@jhoandersontattoo</div>
      <img class="barcode" src="https://barcode.tec-it.com/barcode.ashx?data=jhoandersontattoo&code=Code128&translate-esc=true" alt="Código Instagram">
    </div>
    <div class="contact-item">
      <a href="mailto:jhoanfreitez@gmail.com">
        <img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" alt="Correo">
      </a>
      <div>jhoanfreitez@gmail.com</div>
      <img class="barcode" src="https://barcode.tec-it.com/barcode.ashx?data=jhoanfreitez%40gmail.com&code=Code128&translate-esc=true" alt="Código Correo">
    </div>
    <div class="contact-item">
      <a href="https://www.facebook.com/jhoanderson.freitez?mibextid=wwXIfr" target="_blank">
        <img class="icon" src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook">
      </a>
      <div>Facebook</div>
      <img class="barcode" src="https://barcode.tec-it.com/barcode.ashx?data=https%3A%2F%2Fwww.facebook.com%2Fjhoanderson.freitez%3Fmibextid%3DwwXIfr&code=Code128&translate-esc=true" alt="Código Facebook">
    </div>
  </div>

  <h2 style="margin-top:4rem; text-align:center;">Galería de Tatuajes</h2>
  <div class="galeria">
    <img src="https://source.unsplash.com/featured/?tattoo,1" alt="Tattoo 1">
    <img src="https://source.unsplash.com/featured/?tattoo,2" alt="Tattoo 2">
    <img src="https://source.unsplash.com/featured/?tattoo,3" alt="Tattoo 3">
    <img src="https://source.unsplash.com/featured/?tattoo,4" alt="Tattoo 4">
  </div>

  <script>
    const form = document.getElementById('formulario');
    const resultado = document.getElementById('resultado');

    form.addEventListener('submit', function(e) {
      e.preventDefault();

      const tamano = parseFloat(document.getElementById('tamano').value);
      const estilo = parseFloat(document.getElementById('estilo').value);
      const zona = parseFloat(document.getElementById('zona').value);
      const detalle = parseFloat(document.getElementById('detalle').value);

      const precio = tamano * estilo * zona * detalle;

      resultado.innerText = `Precio estimado: $${precio.toFixed(2)} USD`;
    });
  </script>
</body>
</html>
