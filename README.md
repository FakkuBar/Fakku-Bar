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
    </style>
    <script>
        function abrirProgramacao() {
            let janela = window.open("", "_blank", "width=800,height=600");
            janela.document.write(`
                <html lang="pt-br">
                <head>
                    <meta charset="UTF-8">
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <title>Programação - Fakku Bar</title>
                    <style>
                        body {
                            margin: 0;
                            font-family: Arial, sans-serif;
                            background: linear-gradient(to right, #FFD700, #000000);
                            color: white;
                            text-align: center;
                            padding: 50px;
                        }
                    </style>
                </head>
                <body>
                    <h1>Programação do Fakku Bar</h1>
                    <p>Confira os eventos e atrações especiais da semana!</p>
                </body>
                </html>
            `);
            janela.document.close();
        }
    </script>
</head>
<body>
    <div class="navbar">
        <img src="fakku bar logo novo.jpg" alt="Fakku Bar Logo">
        <a href="#home" target="_blank">Home</a>
        <a onclick="abrirProgramacao()">Programação</a>
        <a href="#eventos" target="_blank">Eventos Corporativos</a>
        <a href="#contato" target="_blank">Contato</a>
    </div>
    <div class="container">
        <h1>Bem-vindo ao Fakku Bar</h1>
        <p>O melhor ambiente para suas noites inesquecíveis!</p>
        <div class="image-container">
            <img src="Miniatura Youtube Jogo de Futebol Ao Vivo Transmissão de jogo e live.jpg" alt="Imagem do Fakku Bar">
        </div>
    </div>
</body>
</html>
