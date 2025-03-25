
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
            justify-content: center;
            position: fixed;
            width: 100%;
            top: 0;
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
        .container {
            text-align: center;
            padding: 80px 20px 50px;
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
            background: url('o-projeto-abstrato-do-fundo-ouro-amarelo.jpg') no-repeat center center fixed;
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
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
            justify-content: center;
            margin-top: 40px;
        }
        .image-grid img {
            width: 100%;
            max-width: 500px;
            height: 900px;
            object-fit: cover;
            border-radius: 10px;
        }
        .floating-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: none;
            border: none;
        }
        .floating-button img {
            width: 60px;
            height: 60px;
            cursor: pointer;
        }
        @media (max-width: 768px) {
            .image-grid {
                grid-template-columns: 1fr;
            }
            .image-grid img {
                height: auto;
            }
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
        <img src="fakku_bar_logo_novo.jpg" alt="Fakku Bar Logo">
        <a href="#home">Home</a>
        <a href="#programacao" onclick="exibirProgramacao()">Programação</a>
        <a href="#eventos">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>
    <div class="container">
        <h1>Bem-vindo ao Fakku Bar</h1>
        <p>O melhor ambiente para suas noites inesquecíveis!</p>
        <div class="image-container">
            <img src="Miniatura_Youtube_Jogo_de_Futebol.jpg" alt="Imagem do Fakku Bar">
        </div>
    </div>
    
    <div id="programacao">
        <h1>PROGRAMAÇÃO DA SEMANA</h1>
        <p>Confira os eventos e atrações especiais da semana!</p>
        <div class="image-grid">
            <img src="quarta_delas.jpg" alt="Quarta Delas">
            <img src="Stories_Instagram_jogo_de_futebol.png" alt="Jogo de Futebol">
            <img src="Story_Instagram_Noite_do_Pagode.png" alt="Noite do Pagode">
            <img src="Story_Match_Divertido.png" alt="Match Divertido">
        </div>
    </div>
    
    <button class="floating-button" onclick="window.location.href='https://www.exemplo.com'">
        <img src="botao_icone.png" alt="Botão">
    </button>
</body>
</html>
