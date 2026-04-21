<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Autos Premium</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: #0d0d0d;
    color: white;
}

/* NAVBAR */
header {
    background: black;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    color: red;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

nav a:hover {
    color: red;
}

/* HERO */
.hero {
    background: url('carro1.jpg') center/cover;
    height: 400px;
    display: flex;
    align-items: center;
    padding-left: 50px;
}

.hero h2 {
    font-size: 50px;
}

.hero button {
    padding: 10px 20px;
    background: red;
    border: none;
    color: white;
    cursor: pointer;
}

/* SECTION */
.section {
    padding: 40px;
    text-align: center;
}

.cars {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: #1c1c1c;
    width: 300px;
    border-radius: 15px;
    overflow: hidden;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
}

.card h3 {
    margin: 10px;
}

.price {
    color: red;
    font-size: 20px;
}

/* BUTTON */
.btn {
    background: red;
    padding: 10px;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
    color: white;
}

/* FOOTER */
footer {
    background: black;
    text-align: center;
    padding: 20px;
}
</style>

</head>

<body>

<header>
    <h1>🚗 AUTOS</h1>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Modelos</a>
        <a href="#">Servicios</a>
        <a href="#">Contacto</a>
    </nav>
</header>

<div class="hero">
    <div>
        <h2>Encuentra tu carro ideal</h2>
        <button>Ver catálogo</button>
    </div>
</div>

<div class="section">
    <h2>Nuestros Mejores Carros</h2>

    <div class="cars">

        <div class="card">
            <img src="carro1.jpg">
            <h3>Carro Deportivo</h3>
            <p>Alta velocidad y diseño moderno</p>
            <p class="price">$50,000</p>
            <a class="btn" href="#">Comprar</a>
        </div>

        <div class="card">
            <img src="carro2.jpg">
            <h3>Carro Clásico</h3>
            <p>Elegancia y estilo antiguo</p>
            <p class="price">$30,000</p>
            <a class="btn" href="#">Comprar</a>
        </div>

        <div class="card">
            <img src="carro1.jpg">
            <h3>Carro SUV</h3>
            <p>Perfecto para familia</p>
            <p class="price">$40,000</p>
            <a class="btn" href="#">Comprar</a>
        </div>

    </div>
</div>

<div class="section" style="background:#111;">
    <h2>Servicios</h2>
    <p>✔ Financiamiento</p>
    <p>✔ Garantía</p>
    <p>✔ Envío a todo el país</p>
</div>

<div class="section">
    <h2>Contacto</h2>
    <p>Email: autos@email.com</p>
    <p>Tel: 123-456-7890</p>
</div>

<footer>
    © 2026 Autos Premium
</footer>

</body>
</html>
