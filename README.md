<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Material Educativo</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            margin: 0 10px;
        }

        nav a:hover {
            background-color: #ddd;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }

        section {
            margin-bottom: 40px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .btn-download, .btn-buy {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            text-decoration: none;
        }

        .btn-buy {
            background-color: #007bff;
        }

        .material-list {
            list-style-type: none;
            padding: 0;
        }

        .material-list li {
            margin: 10px 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenidos a Material Educativo</h1>
        <p>Accede a recursos educativos, tanto gratuitos como de pago</p>
    </header>

    <nav>
        <a href="#free-material">Material Gratuito</a>
        <a href="#paid-material">Material de Compra</a>
        <a href="#contact">Contacto</a>
    </nav>

    <div class="container">
        <!-- Sección de material gratuito -->
        <section id="free-material">
            <h2>Material Gratuito</h2>
            <p>Accede a una variedad de recursos educativos gratuitos para mejorar tus conocimientos.</p>
            <ul class="material-list">
                <li>
                    <a href="material/curso-basico.pdf" class="btn-download">Descargar Curso Básico (PDF)</a>
                </li>
                <li>
                    <a href="material/ejercicio-matematicas.zip" class="btn-download">Descargar Ejercicios de Matemáticas (ZIP)</a>
                </li>
            </ul>
        </section>

        <!-- Sección de material de pago -->
        <section id="paid-material">
            <h2>Material de Compra</h2>
            <p>Explora nuestros productos educativos de alta calidad. Compra ahora y mejora tu aprendizaje.</p>
            <ul class="material-list">
                <li>
                    <a href="material/curso-avanzado.html" class="btn-buy">Comprar Curso Avanzado - $50</a>
                </li>
                <li>
                    <a href="material/ebook-programacion.pdf" class="btn-buy">Comprar eBook de Programación - $20</a>
                </li>
            </ul>
        </section>

        <!-- Sección de contacto -->
        <section id="contact">
            <h2>Contacto</h2>
            <p>Si tienes alguna pregunta, no dudes en ponerte en contacto con nosotros.</p>
            <form>
                <label for="name">Tu nombre:</label><br>
                <input type="text" id="name" name="name"><br><br>

                <label for="email">Tu correo:</label><br>
                <input type="email" id="email" name="email"><br><br>

                <label for="message">Mensaje:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Material Educativo. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
