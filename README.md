<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kaizen - Mejora Continua</title>
    <link rel="icon" type="image/x-icon" href="../LOGO/LOGO-2.ico">
    <style>
        * { 
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f8f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #2c3e50;
            color: #fff;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header .logo {
            display: flex;
            align-items: center;
            font-size: 1.5em;
            font-weight: bold;
            letter-spacing: 1px;
        }
        header .logo img {
            margin-right: 10px; /* Cambia de izquierda a derecha */
            width: 40px;
            height: 40px;
        }
        header nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            font-size: 1em;
            transition: color 0.3s;
        }
        header nav a:hover {
            color: #1abc9c;
        }
        .social-icons img {
            width: 30px; /* Tamaño uniforme para todas las imágenes */
            height: 30px;
            margin: 0 10px;
            cursor: pointer;
        }
        /* Ajuste específico para face.png */
        .social-icons img[alt="Facebook"] {
            width: 30px; /* Igual tamaño que las otras imágenes */
            height: 30px;
        }

        .banner {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(135deg, #1abc9c, #16a085);
            color: white;
        }
        .banner h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .banner p {
            font-size: 1.2em;
            margin-bottom: 20px;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            gap: 30px;
            padding: 40px 20px;
        }
        .content .card {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: 300px;
            transition: transform 0.3s;
        }
        .content .card:hover {
            transform: translateY(-10px);
        }
        .content .card img {
            width: 100%;
            height: auto;
        }
        .content .card p {
            padding: 15px;
            font-size: 1em;
            text-align: center;
        }

        section {
            padding: 50px 20px;
            text-align: center;
            background-color: #fff;
            border-top: 1px solid #ddd;
        }
        section h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #2c3e50;
            color: #fff;
            margin-top: 40px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>


<header>
    <div class="logo">
        <img src="../LOGO/logo1.png" alt="Logo Kaizen"> <!-- Logo a la izquierda -->
        Kaizen - Mejora Continua
    </div>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#tienda">Tienda</a>
        <a href="#accesorios">Accesorios</a>
        <a href="#carrito">Carrito</a>
    </nav>
    <div class="social-icons">
        <img src="../LOGO/face.png" alt="Facebook">
        <img src="../LOGO/insta.webp" alt="Instagram">
        <img src="../LOGO/tiktok.png" alt="TikTok">
        <img src="../LOGO/correo.png" alt="Email">
        <img src="../LOGO/celu.webp" alt="Teléfono">
    </div>
</header>

<div class="banner">
    <h1>Servicios 100% Confiables</h1>
    <p>¿Eres nuevo cliente? Por ser nuestro nuevo cliente te ofrecemos tu primer mantenimiento de Software / Hardware 
        ¡TOTALMENTE GRATUITO!</p>
</div>

<div class="content">
    <div class="card">
        <img src="../LOGO/pc-setup.jpeg" alt="PC Setup">
        <p>Configuración personalizada de equipos.</p>
    </div>
    <div class="card">
        <img src="../LOGO/hardware-maintenance.jpg" alt="Mantenimiento de Hardware">
        <p>Mantenimiento y reparación de hardware.</p>
    </div>
</div>

<section id="inicio">
    <h2>Inicio</h2>
    <p>Contenido de la sección Inicio.</p>
</section>

<section id="tienda">
    <h2>Tienda</h2>
    <p>Contenido de la sección Tienda.</p>
</section>

<section id="accesorios">
    <h2>Accesorios</h2>
    <p>Contenido de la sección Accesorios.</p>
</section>

<section id="carrito">
    <h2>Carrito</h2>
    <p>Contenido de la sección Carrito.</p>
</section>

<footer>
    © 2024 Kaizen - Mejora Continua. Todos los derechos reservados.
</footer>

</body>
</html>
