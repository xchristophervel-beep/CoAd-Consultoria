**<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CoAd Consultoría</title>
<link rel="stylesheet" href="styles.css">
</head>

<body>

<header class="header">
  <div class="nav">
    <h1>CoAd</h1>
    <div class="icons">☰</div>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <div class="hero-text">
    <h2>Consultoría Administrativa</h2>
    <p>
      Solución que transforma tu negocio. En CoAd, ayudamos a micro, pequeñas y medianas empresas a mejorar sus ventas, organización y estrategias digitales.
    </p>
    <button>Leer más ↓</button>
  </div>
  <div class="hero-img"></div>
</section>

<!-- MENU -->
<section class="menu">
  <ul>
    <li>¿Quiénes somos?</li>
    <li>Misión y Visión</li>
    <li>¿Qué hacemos?</li>
    <li>¿Por qué elegirnos?</li>
    <li>Otros servicios</li>
  </ul>
</section>

<!-- QUIENES -->
<section class="overlay">
  <h2>¿Quiénes somos?</h2>
  <p>
    Somos una iniciativa dedicada a brindar asesoría administrativa accesible a las MiPymes. 
    Ayudamos a organizar procesos y fortalecer su crecimiento.
  </p>
</section>

<!-- MISION -->
<section class="overlay light">
  <h2>Misión</h2>
  <p>Brindar consultoría accesible y práctica para MiPymes.</p>

  <h2>Visión</h2>
  <p>Ser una consultoría digital reconocida por impulsar negocios.</p>
</section>

<!-- QUE HACEMOS -->
<section class="overlay">
  <h2>¿Qué hacemos?</h2>
  <p>
    Analizamos empresas y brindamos soluciones en administración, marketing y finanzas para mejorar su rendimiento.
  </p>
</section>

<!-- POR QUE -->
<section class="cards">
  <h2>¿Por qué elegirnos?</h2>

  <div class="grid">
    <div class="card">
      <h3>Accesibles</h3>
      <p>Nos adaptamos a tu presupuesto</p>
    </div>

    <div class="card">
      <h3>Colaborativos</h3>
      <p>Soluciones personalizadas</p>
    </div>

    <div class="card">
      <h3>Prácticos</h3>
      <p>Herramientas fáciles de aplicar</p>
    </div>
  </div>
</section>

<!-- SERVICIOS -->
<section class="services">
  <h2>Otros servicios</h2>

  <div class="grid">
    <div class="service">
      <h3>Redes sociales</h3>
      <p>Mejora tu presencia digital</p>
    </div>

    <div class="service">
      <h3>Diagnóstico</h3>
      <p>Detecta áreas de mejora</p>
    </div>

    <div class="service">
      <h3>Plantillas</h3>
      <p>Optimiza tu operación</p>
    </div>
  </div>
</section>

<!-- PROPUESTA -->
<section class="overlay">
  <h2>Propuesta de Valor</h2>
  <p>
    Soluciones administrativas accesibles que fortalecen la competitividad de las MiPymes
  </p>
</section>

<!-- CONTACTO -->
<section class="contact">
  <div>
    <h2>Tu éxito, nuestra misión</h2>
    <button>Contáctanos</button>

    <p>📞 123-456-789</p>
    <p>✉️ coadconsultoria@gmail.com</p>
  </div>
</section>

</body>
</html>**

body{
  margin:0;
  font-family:Arial;
  background:#0b2a3a;
  color:white;
}

/* NAV */
.header{
  padding:20px;
}

.nav{
  display:flex;
  justify-content:space-between;
}

/* HERO */
.hero{
  display:flex;
  padding:40px;
  align-items:center;
}

.hero-text{
  width:50%;
}

.hero-img{
  width:50%;
  height:300px;
  background:url('https://images.unsplash.com/photo-1554224155-8d04cb21cd6c') center/cover;
}

/* MENU */
.menu{
  background:rgba(255,255,255,0.05);
  padding:20px;
}

.menu ul{
  list-style:none;
}

.menu li{
  margin:10px 0;
  color:#00d4ff;
}

/* OVERLAY SECTIONS */
.overlay{
  padding:80px 20px;
  text-align:center;
  background:linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
  url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40') center/cover;
}

.light{
  background:linear-gradient(rgba(20,20,20,0.6), rgba(20,20,20,0.6)),
  url('https://images.unsplash.com/photo-1492724441997-5dc865305da7') center/cover;
}

/* CARDS */
.cards{
  padding:60px;
  text-align:center;
}

.grid{
  display:flex;
  gap:20px;
  justify-content:center;
}

.card{
  border:1px solid #00d4ff;
  padding:30px;
  border-radius:20px;
}

/* SERVICES */
.services{
  text-align:center;
  padding:60px;
}

.service{
  padding:20px;
}

/* CONTACT */
.contact{
  padding:60px;
  background:#06202c;
}
