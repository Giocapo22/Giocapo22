<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Problema Il Capo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #fff;
        }
        header {
            background-color: #ff6600;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: #ff9933;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        .bio, .links {
            padding: 40px;
            background-color: #262626;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        .bio h2, .links h2 {
            color: #ff6600;
        }
        .links a {
            display: block;
            margin: 10px 0;
            padding: 10px;
            background-color: #ff6600;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }
        .links a:hover {
            background-color: #e65c00;
        }
        footer {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Problema Il Capo</h1>
        <p>Desde el barrio, para el mundo</p>
    </header>
    
    <nav>
        <a href="#bio">Biografía</a>
        <a href="#links">Previsualización y Descarga</a>
        <a href="#contact">Contacto</a>
    </nav>

    <section id="bio" class="bio">
        <h2>Biografía</h2>
        <p>La historia de Problema Il Capo, desde el barrio hasta el escenario. Con una narrativa de superación, Problema representa el esfuerzo, el arte y el compromiso social.</p>
    </section>

    <section id="links" class="links">
        <h2>Previsualización y Descarga</h2>
        <a href="https://example.com/preview" target="_blank">Ver Previsualización</a>
        <a href="https://example.com/download" download>Descargar</a>
    </section>

    <section id="contact" class="bio">
        <h2>Contacto</h2>
        <p>Para consultas de prensa, colaboraciones o contrataciones, completa el formulario a continuación.</p>
        <form>
            <label for="name">Nombre:</label><br>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email"><br><br>
            <label for="message">Mensaje:</label><br>
            <textarea id="message" name="message" rows="4"></textarea><br><br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Problema Il Capo</p>
    </footer>
</body>
</html>
