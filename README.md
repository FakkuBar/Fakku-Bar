<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakku Bar</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: black;
            color: white;
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #111;
            padding: 15px 30px;
        }
        .logo img {
            height: 50px;
        }
        .nav {
            display: flex;
            gap: 20px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }
        .nav a:hover {
            color: red;
        }
        .hero {
            position: relative;
            width: 100%;
            height: 80vh;
            background: url('Miniatura%20Youtube%20Jogo%20de%20Futebol%20Ao%20Vivo%20Transmiss%C3%A3o%20de%20jogo%20e%20live.jpg') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .hero h1 {
            font-size: 50px;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="logo">
            <img src="fakku-logo.png" alt="Fakku Bar Logo">
        </div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">Programação</a>
            <a href="#">Fotos</a>
            <a href="#">Eventos</a>
            <a href="#">Contato</a>
        </nav>
    </header>
    <section class="hero">
        <h1>Fakku Bar - O Melhor Lugar para Sua Noite</h1>
    </section>
</body>
</html>
