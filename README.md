<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bruma Café & Brunch | Montevideo</title>
  <meta name="description" content="Bruma Café & Brunch en Montevideo. Café de especialidad, brunch, pastelería artesanal y reservas de mesa." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Playfair+Display:wght@600;700;800&family=Pacifico&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="header" id="header">
    <a href="#inicio" class="brand">
      <img src="assets/logo.jpg" alt="Logo Bruma Café" />
    </a>
    <button class="menu-btn" id="menuBtn" aria-label="Abrir menú">☰</button>
    <nav class="nav" id="nav">
      <a href="#inicio">Inicio</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#menu">Menú</a>
      <a href="#galeria">Galería</a>
      <a href="#reservas">Reservas</a>
      <a href="#contacto">Contacto</a>
    </nav>
    <a class="instagram" href="https://instagram.com/brumacafe" target="_blank" rel="noopener">@brumacafe</a>
    <a class="btn btn-small" href="#reservas">Reservar mesa</a>
  </header>

  <main>
    <section class="hero" id="inicio">
      <div class="hero-overlay"></div>
      <div class="hero-content reveal">
        <p class="eyebrow">Entre sabores y pausa</p>
        <h1>Entre sabores <span>y pausa</span></h1>
        <p class="hero-text">Un lugar en Montevideo para disfrutar buen café, comida deliciosa y momentos que se quedan contigo.</p>
        <div class="hero-actions">
          <a class="btn" href="#menu">Ver menú ☕</a>
          <a class="btn btn-outline" href="#reservas">Reservar mesa 📅</a>
        </div>
        <div class="features">
          <div>☕ <strong>Café</strong><small>de especialidad</small></div>
          <div>🌿 <strong>Ingredientes</strong><small>frescos</small></div>
          <div>📶 <strong>WiFi</strong><small>libre</small></div>
          <div>🤎 <strong>Ambiente</strong><small>acogedor</small></div>
        </div>
      </div>
    </section>

    <section class="about" id="nosotros">
      <div class="about-img reveal-left">
        <img src="assets/fachada.jpg" alt="Fachada de Bruma Café" />
      </div>
      <div class="about-text reveal-right">
        <p class="section-label">Sobre nosotros</p>
        <h2>Mucho más que café</h2>
        <p>Bruma nace de la idea de crear un espacio donde cada detalle invite a disfrutar. Café de calidad, recetas caseras y un ambiente cálido en el corazón de Montevideo.</p>
        <p>Acá, cada visita es una pausa para vos.</p>
        <span class="signature">— Equipo Bruma</span>
      </div>
    </section>

    <section class="menu-section" id="menu">
      <p class="section-label reveal">Nuestro menú</p>
      <h2 class="reveal">Hecho con amor, para vos</h2>
      <div class="cards">
        <article class="card reveal"><img src="assets/hero.jpg" alt="Café de especialidad"><div><h3>Cafés</h3><p>Café de especialidad para todos los gustos.</p><a href="#reservas">Ver opciones →</a></div></article>
        <article class="card reveal"><img src="assets/imagen-te.jpg" alt="Té e infusiones" onerror="this.src='assets/interior2.jpg'"><div><h3>Tés e infusiones</h3><p>Variedad de tés e infusiones naturales.</p><a href="#reservas">Ver opciones →</a></div></article>
        <article class="card reveal"><img src="assets/interior1.jpg" alt="Pastelería artesanal"><div><h3>Pastelería</h3><p>Repostería artesanal hecha en casa.</p><a href="#reservas">Ver opciones →</a></div></article>
        <article class="card reveal"><img src="assets/interior2.jpg" alt="Desayunos y brunch"><div><h3>Desayunos</h3><p>Opciones completas para empezar bien.</p><a href="#reservas">Ver opciones →</a></div></article>
      </div>
    </section>

    <section class="stats reveal">
      <div>☕ <strong>12K+</strong><span>Tazas servidas</span></div>
      <div>👥 <strong>5K+</strong><span>Clientes felices</span></div>
      <div>♡ <strong>100%</strong><span>Hecho con amor</span></div>
      <div>📍 <strong>Montevideo</strong><span>Nuestra casa</span></div>
    </section>

    <section class="gallery" id="galeria">
      <p class="section-label reveal">Nuestro espacio</p>
      <h2 class="reveal">Ambiente que enamora</h2>
      <div class="gallery-grid">
        <img class="reveal" src="assets/fachada.jpg" alt="Entrada del café">
        <img class="reveal" src="assets/hero.jpg" alt="Café y brunch">
        <img class="reveal" src="assets/interior1.jpg" alt="Interior del local">
        <img class="reveal" src="assets/interior2.jpg" alt="Mesas del café">
      </div>
    </section>

    <section class="reservation" id="reservas">
      <div class="reservation-text reveal-left">
        <p class="section-label">Reservas</p>
        <h2>Reservá tu mesa</h2>
        <p>Asegurá tu lugar y vení a disfrutar de una experiencia única en Bruma Café.</p>
      </div>
      <form class="booking-form reveal-right" id="bookingForm">
        <input type="text" id="name" placeholder="Tu nombre" required>
        <input type="date" id="date" required>
        <input type="time" id="time" required>
        <select id="people" required>
          <option value="">Cantidad de personas</option>
          <option>1 persona</option><option>2 personas</option><option>3 personas</option><option>4 personas</option><option>5+ personas</option>
        </select>
        <button class="btn" type="submit">Reservar por WhatsApp</button>
        <small>La reserva se envía por WhatsApp. No requiere pago online.</small>
      </form>
    </section>
  </main>

  <footer class="footer" id="contacto">
    <div><img src="assets/logo.jpg" alt="Logo Bruma Café"><p>Café de especialidad, comida casera y un ambiente cálido en Montevideo.</p></div>
    <div><h4>Navegación</h4><a href="#inicio">Inicio</a><a href="#nosotros">Nosotros</a><a href="#menu">Menú</a><a href="#galeria">Galería</a><a href="#reservas">Reservas</a></div>
    <div><h4>Horarios</h4><p>Lunes a viernes<br>08:00 - 20:00</p><p>Sábados y domingos<br>09:00 - 21:00</p></div>
    <div><h4>Contacto</h4><p>📍 Montevideo, Uruguay</p><p>📞 099 123 456</p><p>✉️ hola@brumacafe.com</p></div>
    <p class="copy">© 2026 Bruma Café & Brunch. Diseñado por LC Web Studio.</p>
  </footer>

  <a class="whatsapp" href="https://wa.me/59899123456" target="_blank" rel="noopener">☘</a>
  <script src="script.js"></script>
</body>
</html>
