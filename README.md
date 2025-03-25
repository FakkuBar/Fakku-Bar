<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakku Bar</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #FFD700, #000000);
            color: white;
        }
        .navbar {
            background-color: black;
            padding: 15px;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
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
        .container {
            text-align: center;
            padding: 50px;
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
        /* Estilos para a seção de programação */
        #programacao {
            background: url('o-projeto-abstrato-do-fundo-ouro-amarelo-beira-tem-bordas-da-cor-escura-projetor-preto-sol-ou-luz-com-sombra-108765387.jpg') no-repeat center center fixed;
            background-size: cover;
            padding: 50px;
            text-align: center;
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
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
    </style>
    <script>
        function exibirProgramacao() {
            document.getElementById('programacao').scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</head>
<body>
    <div class="navbar">
        <img src="fakku bar logo novo.jpg" alt="Fakku Bar Logo">
        <a href="#home">Home</a>
        <a href="#programacao" onclick="exibirProgramacao()">Programação</a>
        <a href="#eventos">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>
    <div class="container">
        <h1>Bem-vindo ao Fakku Bar</h1>
        <p>O melhor ambiente para suas noites inesquecíveis!</p>
        <div class="image-container">
            <img src="Miniatura Youtube Jogo de Futebol Ao Vivo Transmissão de jogo e live.jpg" alt="Imagem do Fakku Bar">
        </div>
    </div>
    
    <!-- Seção de Programação -->
    <div id="programacao">
        <h1>PROGRAMAÇÃO DA SEMANA</h1>
        <p>Confira os eventos e atrações especiais da semana!</p>
        <div class="image-grid">
            <img src="corinthians x palmeiras 1.jpg" alt="corinthians x palmeiras 1.jpg">
            <img src="imagem2.jpg" alt="Evento 2">
            <img src="imagem3.jpg" alt="Evento 3">
            <img src="imagem4.jpg" alt="Evento 4">
        </div>
    </div>
</body>
</html>
