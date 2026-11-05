# PulseBeat
Aplicación para músicos productores
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PulseBeat | Plataforma para Productores Musicales</title>
    <style>
        :root {
            --bg-color: #0f1117;
            --surface-color: #1a1d24;
            --primary-color: #6366f1;
            --primary-hover: #4f46e5;
            --text-main: #f3f4f6;
            --text-muted: #9ca3af;
            --border-color: #374151;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        header {
            background-color: var(--surface-color);
            border-bottom: 1px solid var(--border-color);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            text-decoration: none;
        }

        nav ul {
            display: list-item;
            list-style: none;
            display: flex;
            gap: 1.5rem;
        }

        nav a {
            color: var(--text-muted);
            text-decoration: none;
            transition: color 0.2s;
        }

        nav a:hover {
            color: var(--primary-color);
        }

        .hero {
            max-width: 1200px;
            margin: 0 auto;
            padding: 5rem 2rem;
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: var(--text-main);
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--text-muted);
            max-width: 700px;
            margin: 0 auto 2rem auto;
        }
        
        .btn {
            background-color: var(--primary-color);
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.2s;
            display: inline-block;
        }

        .btn:hover {
            background-color: var(--primary-hover);
        }

        footer {
            text-align: center;
            padding: 2rem;
            border-top: 1px solid var(--border-color);
            color: var(--text-muted);
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <header>
        <div class="nav-container">
            <a href="#" class="logo">⚡ PulseBeat</a>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#nosotros">Nosotros</a></li>
                    <li><a href="#servicios">Servicios</a></li>
                    <li><a href="#comunidad">Comunidad</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="inicio" class="hero">
            <h1>El ritmo de tu creatividad</h1>
            <p>Plataforma web para productores independientes. Gestiona, colabora y distribuye tus proyectos de audio sin fricciones de interfaz.</p>
            <a href="#servicios" class="btn">Empezar ahora</a>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 PulseBeat. Vocacional 5 - Grupo 5IV12 (Ramírez Vázquez, Cruz Lira, Cruz García).</p>
    </footer>

</body>
</html>
