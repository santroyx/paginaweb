<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Santiago Troya - Diamante K2</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #34495e;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #2980b9;
            color: white;
        }
        .container {
            padding: 20px;
        }
        .products, .contact, .login {
            margin: 20px 0;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .product h3 {
            margin-top: 0;
        }
        .product button {
            padding: 10px 20px;
            background-color: #27ae60;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #2ecc71;
        }
        .social-media {
            text-align: center;
            padding: 20px;
        }
        .social-media a {
            margin: 0 10px;
            text-decoration: none;
            color: white;
            font-size: 24px;
        }
        .contact form, .login form {
            background-color: white;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .contact form input, .contact form textarea, .login form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact form button, .login form button {
            padding: 10px 20px;
            background-color: #2980b9;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact form button:hover, .login form button:hover {
            background-color: #3498db;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
    <!-- Font Awesome para los iconos de redes sociales -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>

<header>
    <h1>Santiago Troya - Diamante K2</h1>
    <p>Productos de Salud y Bienestar</p>
</header>

<nav>
    <a href="#products">Productos</a>
    <a href="#contact">Contacto</a>
    <a href="#login">Iniciar Sesión</a>
</nav>

<div class="container">
    <section id="products" class="products">
        <h2>Productos</h2>
        <div class="product">
            <h3>Producto 1: Suplemento Vitamínico</h3>
            <img src="https://via.placeholder.com/300x200" alt="Producto 1">
            <p>Un suplemento vitamínico completo para mejorar tu salud y bienestar.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <h3>Producto 2: Aceite Esencial</h3>
            <img src="https://via.placeholder.com/300x200" alt="Producto 2">
            <p>Aceite esencial natural para relajación y bienestar mental.</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <h3>Producto 3: Batido Proteico</h3>
            <img src="https://via.placeholder.com/300x200" alt="Producto 3">
            <p>Batido proteico para fortalecer tus músculos y aumentar tu energía.</p>
            <button>Comprar</button>
        </div>
        <!-- Agregar más productos según sea necesario -->
    </section>

    <section id="contact" class="contact">
        <h2>Contacto</h2>
        <form>
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <section id="login" class="login">
        <h2>Iniciar Sesión</h2>
        <form>
            <label for="username">Usuario:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Contraseña:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Iniciar Sesión</button>
        </form>
    </section>
</div>

<footer>
    <div class="social-media">
        <h3>Síguenos en redes sociales</h3>
        <a href="https://facebook.com" target="_blank" class="fab fa-facebook"></a>
        <a href="https://twitter.com" target="_blank" class="fab fa-twitter"></a>
        <a href="https://linkedin.com" target="_blank" class="fab fa-linkedin"></a>
        <a href="https://instagram.com" target="_blank" class="fab fa-instagram"></a>
    </div>
    <p>&copy; 2024 Santiago Troya - Diamante K2. Todos los derechos reservados.</p>
</footer>

</body>
</html>
