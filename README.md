<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Carros</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: white;
        }

        header {
            background: black;
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
        }

        nav {
            text-align: center;
            background: #222;
            padding: 10px;
        }

        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: red;
        }

        .container {
            padding: 20px;
        }

        .car-card {
            background: #1c1c1c;
            border-radius: 15px;
            padding: 15px;
            margin: 20px auto;
            width: 80%;
            box-shadow: 0px 0px 15px rgba(255,0,0,0.5);
            transition: transform 0.3s;
        }

        .car-card:hover {
            transform: scale(1.05);
        }

        .car-card img {
            width: 100%;
            border-radius: 10px;
        }

        .car-title {
            font-size: 24px;
            margin-top: 10px;
        }

        .price {
            color: red;
            font-size: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: black;
            margin-top: 30px;
        }
    </style>
</head>

<body>

<header>
    🚗 Página de Carros
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Modelos</a>
    <a href="#">Contacto</a>
</nav>

<div class="container">

    <div class="car-card">
        <img src="carro1.jpg" alt="Carro deportivo">
        <div class="car-title">Carro Deportivo</div>
        <p>Velocidad máxima y diseño moderno.</p>
        <div class="price">$50,000</div>
    </div>

    <div class="car-card">
        <img src="carro2.jpg" alt="Carro clásico">
        <div class="car-title">Carro Clásico</div>
        <p>Estilo antiguo con elegancia única.</p>
        <div class="price">$30,000</div>
    </div>

</div>

<footer>
    © 2026 Página de Carros
</footer>

</body>
</html>
