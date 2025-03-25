<!DOCTYPE html> 
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakku Bar</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: black;
            font-family: Arial, sans-serif;
            color: white;
        }
        .navbar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 20px;
            background-color: rgba(0, 0, 0, 0.8);
        }
        .navbar img {
            width: 100px; /* Ajustado para um tamanho pequeno */
            height: auto;
        }
        .menu {
            display: flex;
            gap: 20px;
        }
        .menu a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }
        .slogan {
            font-size: 24px;
            font-weight: bold;
            color: #ff0000;
            text-shadow: 0 0 8px #ff0000, 0 0 16px #ff4500;
        }
    </style>
</head>
<body>
    <header class="navbar">
        <img src="/mnt/data/fakku bar logo novo.jpg" alt="Fakku Bar Logo">
        <nav class="menu">
            <a href="#">Home</a>
            <a href="#">Programação</a>
            <a href="#">Fotos</a>
            <a href="#">Eventos</a>
            <a href="#">Contato</a>
        </nav>
        <div class="slogan">Fakku Bar - O Melhor Lugar para Sua Noite</div>
    </header>
</body>
</html>
