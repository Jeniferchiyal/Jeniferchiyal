<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primer Portafolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#cosas-sobre-mi">Sobre mí</a></li>
                <li><a href="#algunos-de-mis-proyectos">Proyectos</a></li>
                <li><a href="#dudas-al-siguiente-contacto-xd">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h1>¡Hola! Soy Jenifer, y estoy desarrollando un portafolio sin la mas minima idea de como se hace, siendo este mi primer año en utilizar este tipo de plataformas :D</h1>
        <p>Estudiante | Mini progamador en HTML</p>
    </section>

    <section id="sobre-mi">
        <h2>Cosas Sobre Mí</h2>
        <p>Soy un estudiante, cursando el segundo de año de diversificado, me gustan los mangos xd, uno de mis pasatiempos es ejecutar instrumentos o dormir</p>
    </section>

    <section id="proyectos">
        <h2>Proyectos</h2>
        <div class="proyecto">
            <h3>Proyecto 1</h3>
            <img src="images/proyecto1.png" alt="Proyecto 1">
            <p>Uno de mis proyectos de los cuales aun siguen siendo personales es culminar con mis estudios, pero, si llegase la oportunidad de realizar algun proyecto con mas impacto, entonces ese proyecto de realizaria</p>
        </div>
        <div class="proyecto">
            <h3>Proyecto 2</h3>
            <img src="proyecto.png" alt="Proyecto 2">
            <p>Aun estoy planeando el segungo proyecto</p>
        </div>
    </section>

    <section id="dudas al siguiente contacto xd">
        <h2>Contacto</h2>
        <form>
            <label for="nombre"Jenny:</label>
            <input type="text" id="nombre" name="nombre" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Jenifer. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
