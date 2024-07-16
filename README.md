<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .info-section {
            margin-bottom: 20px;
        }
        .info-section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Página Personal</h1>
    </header>
    <nav>
        <a href="#consejos">Consejos Diarios</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container">
        <section id="consejos" class="info-section">
            <h2>Consejos Diarios</h2>
            <p>Aquí encontrarás información útil para el día a día:</p>
            <ul>
                <li><strong>Organización:</strong> Usa una lista de tareas para mantenerte al día con tus responsabilidades.</li>
                <li><strong>Salud:</strong> Intenta caminar al menos 30 minutos al día para mantenerte en forma.</li>
                <li><strong>Productividad:</strong> Divide tus tareas grandes en pequeñas para manejarlas mejor.</li>
                <li><strong>Finanzas:</strong> Lleva un registro de tus gastos para tener un mejor control de tu presupuesto.</li>
            </ul>
        </section>
        <section id="contacto" class="info-section">
            <h2>Contacto</h2>
            <p>Puedes seguirme en Instagram para más consejos y actualizaciones:</p>
            <p><a href="https://www.instagram.com/tu_usuario" target="_blank">@tu_usuario</a></p>
        </section>
    </div>
    <footer>
        &copy; 2024 Mi Página Personal
    </footer>
</body>
</html>
