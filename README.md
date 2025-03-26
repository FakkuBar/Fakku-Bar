
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
        #programacao {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
                        url('imagens/o-projeto-abstrato-do-fundo-ouro-amarelo.jpg') no-repeat center center fixed;
            background-size: cover;
            padding: 50px;
            text-align: center;
            position: relative;
            z-index: 1;
        }
        #programacao h1 {
            font-size: 48px;
            font-weight: bold;
            margin-top: 20px;
            text-transform: uppercase;
        }
        .image-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }
        .image-grid img {
            width: 100%;
            max-width: 400px;
            height: auto;
            border-radius: 10px;
        }
        @media (max-width: 768px) {
            .image-grid {
                flex-direction: column;
                align-items: center;
            }
        }
        .floating-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
        }
    </style>
    <script>
        function scrollPara(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</head>
<body>
    <div class="navbar">
        <img src="imagens/fakku_bar_logo_novo.jpg" alt="Fakku Bar Logo">
        <a href="#home">Home</a>
        <a href="javascript:void(0)" onclick="scrollPara('programacao')">Programação</a>
        <a href="#eventos">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>
    <div class="container">
        <h1>Bem-vindo ao Fakku Bar</h1>
        <p>O melhor ambiente para suas noites inesquecíveis!</p>
        <div class="image-container">
            <img src="imagens/miniatura_youtube.jpg" alt="Imagem do Fakku Bar">
        </div>
    </div>
    <div id="programacao">
        <h1>PROGRAMAÇÃO DA SEMANA</h1>
        <p>Confira os eventos e atrações especiais da semana!</p>
        <div class="image-grid">
            <img src="imagens/quarta_delas.jpg" alt="Quarta Delas">
            <img src="imagens/futebol_varzea.png" alt="Futebol Várzea">
            <img src="imagens/noite_pagode.png" alt="Noite do Pagode">
            <img src="imagens/match_divertido.png" alt="Match Divertido">
        </div>
    </div>
    <a href="outra_pagina.html">
        <img src="imagens/whatsapp_icon.png" alt="WhatsApp" class="floating-button">
    </a>
</body>
</html>
