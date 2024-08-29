<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#sobre-mi">Sobre mí</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h1>¡Hola! Soy [Tu Nombre]</h1>
        <p>Desarrollador Web | Diseñador | [Otra Profesión]</p>
    </section>

    <section id="sobre-mi">
        <h2>Sobre Mí</h2>
        <p>[Breve descripción sobre ti]</p>
    </section>

    <section id="proyectos">
        <h2>Proyectos</h2>
        <div class="proyecto">
            <h3>Proyecto 1</h3>
            <img src="images/proyecto1.png" alt="Proyecto 1">
            <p>[Descripción del Proyecto 1]</p>
        </div>
        <div class="proyecto">
            <h3>Proyecto 2</h3>
            <img src="images/proyecto2.png" alt="Proyecto 2">
            <p>[Descripción del Proyecto 2]</p>
        </div>
        <!-- Añade más proyectos según sea necesario -->
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2024 [Tu Nombre]. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
