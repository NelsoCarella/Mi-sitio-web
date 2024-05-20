<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Entrenador Personal</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; color: #333; }
        header { background: #004d99; color: white; padding: 10px 20px; text-align: center; }
        nav { background: #0066cc; padding: 10px 20px; }
        nav a { color: white; text-decoration: none; margin-right: 10px; }
        section { padding: 20px; margin-top: 10px; background: white; }
        footer { background: #004d99; color: white; text-align: center; padding: 10px 20px; position: fixed; width: 100%; bottom: 0; }
        .container { width: 80%; margin: auto; overflow: hidden; }
        .contact-form { background: #f8f8f8; padding: 15px; margin-top: 15px; }
        label, input, textarea { display: block; width: 100%; margin-bottom: 10px; }
        input[type="submit"] { background: #0056b3; color: white; border: none; padding: 10px; cursor: pointer; }
        input[type="submit"]:hover { background: #004c99; }
    </style>
</head>
<body>
    <header>
        <h1>Tu Entrenador Personal</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio" class="container">
        <h2>Bienvenido a tu transformación</h2>
        <p>Descubre cómo puedo ayudarte a alcanzar tus metas físicas y mejorar tu salud y bienestar.</p>
    </section>
    <section id="sobre-mi" class="container">
        <h2>Sobre mí</h2>
        <p>Soy [Tu Nombre], entrenador personal certificado con años de experiencia ayudando a personas a lograr sus objetivos de fitness.</p>
    </section>
    <section id="servicios" class="container">
        <h2>Servicios</h2>
        <ul>
            <li>Entrenamiento personalizado</li>
            <li>Asesoramiento nutricional</li>
            <li>Rutinas ajustadas a tus necesidades</li>
            <li>Coaching motivacional</li>
        </ul>
    </section>
    <section id="contacto" class="container">
        <h2>Contacto</h2>
        <form class="contact-form">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" required></textarea>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Tu Entrenador Personal</p>
    </footer>
</body>
</html>
