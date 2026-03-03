<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Nombre | Soluciones Integrales</title>
    <style>
        /* --- VARIABLES DE COLOR (Tu Paleta) --- */
        :root {
            --bg-color: #E8E8C1;       /* Fondo Crema */
            --text-small: #000000;     /* Letra Pequeña */
            --title-color: #070733;    /* Títulos */
            --contact-color: #17042E;  /* Contactos/Botones */
            --white-overlay: rgba(255, 255, 255, 0.4); /* Para tarjetas */
        }

        /* --- ESTILOS GENERALES --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; /* Fuente limpia y andrógina */
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-small);
            line-height: 1.6;
            overflow-x: hidden;
        }

        a {
            text-decoration: none;
            transition: 0.3s ease;
        }

        ul {
            list-style: none;
        }

        /* --- CONTENEDOR PRINCIPAL --- */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* --- HEADER & NAV --- */
        header {
            padding: 40px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--title-color);
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        nav ul {
            display: flex;
            gap: 30px;
        }

        nav a {
            color: var(--title-color);
            font-weight: 500;
            font-size: 0.9rem;
        }

        nav a:hover {
            color: var(--contact-color);
            border-bottom: 1px solid var(--contact-color);
        }

        /* --- HERO SECTION --- */
        .hero {
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .hero h1 {
            font-size: 3.5rem;
            color: var(--title-color);
            margin-bottom: 20px;
            line-height: 1.1;
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 40px;
            color: var(--text-small);
        }

        .btn {
            display: inline-block;
            padding: 15px 40px;
            background-color: var(--contact-color);
            color: #E8E8C1; /* Invertido para contraste */
            font-weight: bold;
            border-radius: 50px;
            letter-spacing: 1px;
            box-shadow: 0 4px 15px rgba(23, 4, 46, 0.3);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(23, 4, 46, 0.4);
            background-color: var(--title-color);
        }

        /* --- SERVICIOS --- */
        .services {
            padding: 100px 0;
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            color: var(--title-color);
            margin-bottom: 60px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: var(--white-overlay);
            padding: 40px 30px;
            border: 1px solid var(--title-color);
            border-radius: 8px;
            text-align: center;
            transition: 0.3s;
        }

        .service-card:hover {
            background: #fff;
            transform: translateY(-5px);
        }

        .service-card h3 {
            color: var(--title-color);
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

        .service-card p {
            font-size: 0.95rem;
            color: var(--text-small);
        }

        /* --- SOBRE MI --- */
        .about {
            padding: 80px 0;
            background-color: rgba(255,255,255,0.2);
            text-align: center;
        }

        .about p {
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.1rem;
        }

        /* --- CONTACTO --- */
        .contact {
            padding: 100px 0;
            text-align: center;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 40px;
            flex-wrap: wrap;
        }

        .contact-item {
            color: var(--contact-color);
            font-size: 1.2rem;
            font-weight: bold;
            border-bottom: 2px solid transparent;
        }

        .contact-item:hover {
            border-bottom: 2px solid var(--contact-color);
        }

        /* --- FOOTER --- */
        footer {
            text-align: center;
            padding: 40px 0;
            font-size: 0.8rem;
            color: var(--title-color);
            border-top: 1px solid var(--title-color);
        }

        /* --- RESPONSIVE --- */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            nav ul { display: none; } /* Menú simplificado para móvil */
            .logo { font-size: 1.2rem; }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- HEADER -->
        <header>
            <div class="logo">Tu Nombre</div>
            <nav>
                <ul>
                    <li><a href="#servicios">Servicios</a></li>
                    <li><a href="#sobre-mi">Sobre Mí</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </header>

        <!-- HERO -->
        <section class="hero">
            <h1>Multitasker & <br>Closer Estratégica</h1>
            <p>Traducción, Ventas, Asistencia y Monitoría. <br>Unifico habilidades para potenciar tu negocio online.</p>
            <a href="#contacto" class="btn">Trabajemos Juntos</a>
        </section>

        <!-- SERVICIOS -->
        <section id="servicios" class="services">
            <h2 class="section-title">Lo Que Hago Por Ti</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3>Closer de Ventas</h3>
                    <p>Cierre de tratos de alto valor con empatía y estrategia. Convierto leads en clientes fieles.</p>
                </div>
                <div class="service-card">
                    <h3>Asistente Virtual</h3>
                    <p>Gestión administrativa, agenda y organización. Libera tu tiempo para lo importante.</p>
                </div>
                <div class="service-card">
                    <h3>Traducción EN/ES</h3>
                    <p>Traducción precisa y culturalmente adaptada para negocios globales.</p>
                </div>
                <div class="service-card">
                    <h3>Monitora de Modelos</h3>
                    <p>Gestión y supervisión de talento digital. Optimización de rendimiento y seguridad.</p>
                </div>
            </div>
        </section>

        <!-- SOBRE MI -->
        <section id="sobre-mi" class="about">
            <h2 class="section-title">Mi Enfoque</h2>
            <p>No soy solo una ejecutora, soy una socia estratégica. Mi perfil híbrido me permite entender tu negocio desde las ventas hasta la operación diaria, asegurando que nada se pierda en la traducción (literal y figurada).</p>
        </section>

        <!-- CONTACTO -->
        <section id="contacto" class="contact">
            <h2 class="section-title">Hablemos</h2>
            <p>¿Listo para optimizar tu tiempo y aumentar tus ventas?</p>
            <div class="contact-links">
                <a href="mailto:tuemail@ejemplo.com" class="contact-item">Email</a>
                <a href="https://wa.me/tunumero" class="contact-item">WhatsApp</a>
                <a href="https://linkedin.com/in/tuperfil" class="contact-item">LinkedIn</a>
                <a href="https://instagram.com/tuusuario" class="contact-item">Instagram</a>
            </div>
        </section>

        <!-- FOOTER -->
        <footer>
            <p>&copy; 2023 Tu Nombre. Todos los derechos reservados.</p>
        </footer>
    </div>

    <script>
        // Smooth Scroll simple para navegación interna
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
