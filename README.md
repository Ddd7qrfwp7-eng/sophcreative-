# sophcreative-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SophCreative | Agencia Creativa</title>
    <style>
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:system-ui,Arial,sans-serif;background:#0f0f14;color:#fff}
        header{min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;padding:20px;background:linear-gradient(135deg,#6a11cb,#2575fc)}
        h1{font-size:4rem; margin-top:20px;}
        .logo{max-width:150px; margin-bottom:20px;}
        .hero p{max-width:700px;margin:20px auto;font-size:1.2rem}
        .btn{display:inline-block;padding:14px 28px;background:#fff;color:#2575fc;text-decoration:none;border-radius:30px;font-weight:bold}
        section{padding:80px 8%}
        h2{text-align:center;margin-bottom:40px;font-size:2.2rem}
        .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px}
        .card{background:#1a1a24;padding:25px;border-radius:18px;transition:.3s}
        .card:hover{transform:translateY(-8px)}
        .portfolio{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
        .work{background:#1a1a24;padding:50px 20px;border-radius:18px;text-align:center}
        .contact{background:#1a1a24;border-radius:20px;padding:40px;text-align:center}
        footer{text-align:center;padding:25px;background:#09090d}
    </style>
</head>
<body>

<header>
    <img src="soph_logo.jpg" alt="Logo de SophCreative" class="logo">
    <h1>SophCreative</h1>
    <p>Transformamos ideas en marcas memorables. Diseño gráfico, redes sociales, edición de video y desarrollo web profesional.</p>
    <a class="btn" href="#contacto">Solicitar Cotización</a>
</header>

<section>
    <h2>Servicios</h2>
    <div class="cards">
        <div class="card"><h3>🎨 Diseño Gráfico</h3><p>Logotipos, identidad visual y material publicitario.</p></div>
        <div class="card"><h3>📱 Redes Sociales</h3><p>Creación de contenido, estrategia y crecimiento de marca.</p></div>
        <div class="card"><h3>💻 Diseño Web</h3><p>Páginas modernas, rápidas y optimizadas para móviles.</p></div>
        <div class="card"><h3>🎬 Edición de Video</h3><p>Reels, TikToks y anuncios que generan impacto.</p></div>
    </div>
</section>

<section>
    <h2>Portafolio</h2>
    <div class="portfolio">
        <div class="work">Proyecto de Branding</div>
        <div class="work">Campaña para Redes Sociales</div>
        <div class="work">Sitio Web Empresarial</div>
    </div>
</section>

<section id="contacto">
    <div class="contact">
        <h2>Contacto</h2>
        <p>📧 contacto@sophcreative.com</p>
        <p>📸 Instagram: @sophcreative</p>
        <p>📱 WhatsApp: +52 000 000 0000</p>
    </div>
</section>

<footer>
    <p>© 2026 SophCreative. Todos los derechos reservados.</p>
</footer>

</body>
</html>
