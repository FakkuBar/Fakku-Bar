<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programação - Fakku Bar</title>
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
        .container {
            text-align: center;
            padding: 50px;
            margin-top: 80px;
        }
        .slideshow-container {
            max-width: 80%;
            position: relative;
            margin: auto;
        }
        .slides {
            display: none;
            width: 100%;
        }
        .fade {
            animation: fadeEffect 2s infinite;
        }
        @keyframes fadeEffect {
            from {opacity: 0.4;} 
            to {opacity: 1;}
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
        <img src="fakku bar logo novo.jpg" alt="fakku bar logo novo.jpg">
        <a href="index.html">Programação</a>
        <a href="https://drive.google.com/file/d/1SGHjepQ1B6WGl8trWKwrsLNKiFWiccv1/view?usp=drive_link" target="_blank">Cardápio</a>
        <a href="#eventos">Eventos Corporativos</a>
        <a href="#contato">Contato</a>
    </div>
    <div class="container">
        <h1>Programação</h1>
        <div class="slideshow-container">
            <img class="slides fade" src="quarta delas.jpg" alt="quarta delas.jpg">
            <img class="slides fade" src="Stories Instagram jogo de futebol várzea grunge vermelho (1).png" alt="Stories Instagram jogo de futebol várzea grunge vermelho (1).png">
            <img class="slides fade" src="Story para Instagram Noite do Pagode Preto Popular.png" alt="Story para Instagram Noite do Pagode Preto Popular.png">
            <img class="slides fade" src="Story Match Divertido Marrom  (2).png" alt="Story Match Divertido Marrom  (2).png">
            <img class="slides fade" src="460575885_1259010748853725_7475187610060210292_n.jpg" alt="460575885_1259010748853725_7475187610060210292_n.jpg">
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
            setTimeout(showSlides, 3000);
        }
    </script>
</body>
</html>
