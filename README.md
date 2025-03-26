<!DOCTYPE html>
<html lang="pt-br">
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
        .navbar {
            background-color: red;
            padding: 15px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: space-around;
            position: fixed;
            width: 100vw;
            top: 0;
            left: 0;
            z-index: 1000;
        }
        .navbar img {
            height: 50px;
            margin-right: 20px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            font-size: 18px;
            cursor: pointer;
        }
        .navbar a:hover {
            color: #FFD700;
        }
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                padding: 10px;
            }
            .navbar img {
                margin-bottom: 10px;
            }
        }
        .container {
            text-align: center;
            padding: 50px;
            margin-top: 80px;
        }
        .image-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .image-container img {
            width: 80%;
            max-width: 800px;
            height: auto;
        }
        .floating-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <img src="fakku_bar_logo_novo.jpg" alt="Fakku Bar Logo">
        <a href="#home">Home</a>
        <a href="programacao.html" target="_blank">Programação</a>
        <a href="#eventos">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>
    <div class="container">
        <h1>Bem-vindo ao Fakku Bar</h1>
        <p>O melhor ambiente para suas noites inesquecíveis!</p>
        <div class="image-container">
            <img src="miniatura_youtube.jpg" alt="Miniatura YouTube">
        </div>
    </div>
    <a href="outra_pagina.html">
        <img src="whatsapp_icon.png" alt="WhatsApp" class="floating-button">
    </a>
</body>
</html>
