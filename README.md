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
            display: flex;
            align-items: center;
            justify-content: flex-start; /* Alinha itens à esquerda */
            position: fixed;
            width: 100%; /* Garante que a barra ocupe toda a largura */
            top: 0;
            left: 0;
            z-index: 1000;
        }
        .navbar img {
            height: 60px; /* Ajuste a altura conforme necessário */
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
            margin-top: 80px;
            display: flex; /* Usar flexbox para layout */
            justify-content: center; /* Centraliza o conteúdo */
            align-items: center; /* Alinha no centro verticalmente */
            flex-direction: column; /* Coloca itens em coluna */
        }
        .slideshow-container {
            max-width: 50%; /* Largura do slideshow ajustada */
            position: relative;
            margin: auto;
        }
        .slides {
            display: none;
            width: 100%;
            height: auto; /* Permite que a altura se ajuste à largura */
        }
        .fade {
            animation: fadeEffect 1s infinite; /* Alterado para loop contínuo */
        }
        @keyframes fadeEffect {
            from {opacity: 0;} 
            to {opacity: 1;}
        }
        .text-box {
            max-width: 45%; /* Largura da caixa de texto */
            background-color: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            color: white;
            text-align: left;
        }
        .floating-button {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 60px;
            height: 60px;
        }
        .hidden {
            display: none; /* Oculta a seção inicialmente */
        }
        h1 {
            margin-bottom: 20px; /* Margin para separar o título das imagens */
        }
    </style>
</head>
<body>
    <div class="navbar">
        <img src="fakku bar logo novo.jpg" alt="fakku bar logo novo.jpg">
        <a href="#programacao" onclick="showSection('programacao')">Programação</a>
        <a href="https://drive.google.com/file/d/1SGHjepQ1B6WGl8trWKwrsLNKiFWiccv1/view?usp=drive_link" target="_blank">Cardápio</a>
        <a href="#eventos" onclick="showSection('eventos')">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>

    <div id="programacao" class="container">
        <h1>Programação Semanal</h1> <!-- Título atualizado -->
        <div class="slideshow-container">
            <img class="slides fade" src="quarta delas.jpg" alt="quarta delas.jpg">
            <img class="slides fade" src="Stories Instagram jogo de futebol várzea grunge vermelho (1).png" alt="Stories Instagram jogo de futebol várzea grunge vermelho (1).png">
            <img class="slides fade" src="Story para Instagram Noite do Pagode Preto Popular.png" alt="Story para Instagram Noite do Pagode Preto Popular.png">
            <img class="slides fade" src="Story Match Divertido Marrom  (2).png" alt="Story Match Divertido Marrom  (2).png">
            <img class="slides fade" src="460575885_1259010748853725_7475187610060210292_n.jpg" alt="460575885_1259010748853725_7475187610060210292_n.jpg">
        </div>
    </div>

    <div id="eventos" class="container hidden">
        <div class="slideshow-container" style="align-self: flex-start;"> <!-- Alinhado à esquerda -->
            <img class="slides fade" src="evento corporativo 1.jpg" alt="evento corporativo 1.jpg">
            <img class="slides fade" src="evento corporativo 2.jpg" alt="evento corporativo 2.jpg">
            <img class="slides fade" src="evento corporativo 3.jpg" alt="evento corporativo 3.jpg">
            <img class="slides fade" src="evento corporativo 4.jpg" alt="evento corporativo 4.jpg">
        </div>
        <div class="text-box">
            <h1>Eventos Corporativos</h1>
            <p>Aqui você encontrará informações sobre nossos eventos corporativos.</p>
            <p>Estamos prontos para atender suas necessidades e fazer de seu evento um sucesso!</p>
            <!-- Adicione mais conteúdo sobre eventos corporativos aqui -->
        </div>
    </div>

    <a href="https://drive.google.com/file/d/1SGHjepQ1B6WGl8trWKwrsLNKiFWiccv1/view?usp=drive_link">
        <img src="whatsapp_icon.png" alt="WhatsApp" class="floating-button">
    </a>

    <script>
        let slideIndex = 0;
        showSlides();

        function showSlides() {
            let slides = document.getElementsByClassName("slides");
            for (let i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            slideIndex++;
            if (slideIndex > slides.length) {slideIndex = 1}
            slides[slideIndex - 1].style.display = "block";
            setTimeout(showSlides, 1000); // Tempo reduzido para 1 segundo para loop contínuo
        }

        function showSection(sectionId) {
            const sections = document.querySelectorAll('.container');
            sections.forEach(section => {
                section.classList.add('hidden');
            });
            document.getElementById(sectionId).classList.remove('hidden');
            showSlides(); // Reinicia o slideshow ao mudar de seção
        }
    </script>
</body>
</html>
