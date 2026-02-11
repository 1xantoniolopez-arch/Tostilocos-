# Tostilocos-
Tostilocos los monos cuauhtemoc colima 
<!DOCTYPE html>
<html lang="es-MX">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tostilocos El Sabor Loco</title>

  <style>
    /* --- MOBILE FIRST --- */
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      margin: 0;
      background-color: #fff5ee;
      color: #222;
      line-height: 1.6;
    }

    header {
      background: #ff3c38;
      color: white;
      text-align: center;
      padding: 24px 16px;
    }

    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }

    header p {
      margin-top: 8px;
      font-size: 1rem;
    }

    nav {
      background: #ffb703;
      display: flex;
      flex-direction: column;
      text-align: center;
    }

    nav a {
      padding: 14px;
      text-decoration: none;
      color: #000;
      font-weight: bold;
      border-bottom: 1px solid rgba(0,0,0,0.1);
    }

    nav a:hover {
      background: #ffd166;
    }

    section {
      padding: 20px 16px;
    }

    h2 {
      color: #ff3c38;
      font-size: 1.4rem;
      margin-bottom: 10px;
    }

    .menu-item {
      background: white;
      padding: 16px;
      margin-bottom: 16px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.08);
    }

    .menu-item h3 {
      margin-top: 0;
      margin-bottom: 6px;
    }

    .precio {
      font-size: 1.2rem;
      font-weight: bold;
      color: #ff3c38;
      margin-top: 8px;
    }

    .btn {
      display: block;
      text-align: center;
      background: #ff3c38;
      color: white;
      padding: 14px;
      margin-top: 16px;
      border-radius: 8px;
      font-size: 1.1rem;
      font-weight: bold;
      text-decoration: none;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 16px;
      font-size: 0.9rem;
    }

    /* --- TABLET Y ESCRITORIO --- */
    @media (min-width: 768px) {
      nav {
        flex-direction: row;
        justify-content: center;
      }

      nav a {
        border-bottom: none;
        border-right: 1px solid rgba(0,0,0,0.1);
      }

      nav a:last-child {
        border-right: none;
      }

      section {
        max-width: 900px;
        margin: auto;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>🌶️ Tostilocos El Sabor Loco 🌶️</h1>
  <p>Antojos bien preparados y con harta salsa</p>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#menu">Menú</a>
  <a href="#nosotros">Nosotros</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h2>Bienvenidos</h2>
  <p>
    Si traes antojo de algo picosito, aquí es 😋  
    Preparamos tostilocos bien servidos, con ingredientes frescos,
    mucho sabor y el picante a tu gusto.
  </p>
</section>

<section id="menu">
  <h2>Menú</h2>

  <div class="menu-item">
    <h3>Tostilocos Clásicos</h3>
    <p>Tostitos, pepino, jícama, cueritos, cacahuate, limón, chamoy y salsas.</p>
    <div class="precio">$50 MXN</div>
  </div>

  <div class="menu-item">
    <h3>Tostilocos Especiales</h3>
    <p>Con camarón seco, mango, clamato y extra cuerito.</p>
    <div class="precio">$65 MXN</div>
  </div>

  <div class="menu-item">
    <h3>Extras</h3>
    <p>Más cueritos, más camarón, más salsa o más limón.</p>
    <div class="precio>">Desde $5 MXN</div>
  </div>
</section>

<section id="nosotros">
  <h2>¿Quiénes Somos?</h2>
  <p>
    Somos un emprendimiento local hecho con ganas y sazón.
    Cuidamos la limpieza, el sabor y que salgas feliz con tu tostiloco.
  </p>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📍 Ubicación: (agrega tu colonia o referencia)</p>
  <p>🕒 Viernes a Domingo · 4:00 pm – 10:00 pm</p>
  <p>📞 WhatsApp: 55 1234 5678</p>

  <a class="btn" href="https://wa.me/5215512345678" target="_blank">
    📲 Ordena por WhatsApp
  </a>
</section>

<footer>
  <p>© 2026 Tostilocos El Sabor Loco · Hecho con ❤️ y chilito</p>
</footer>

</body>
</html>
