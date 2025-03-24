 <img src="fakku bar logo novo.jpg" alt="Ambiente do Fakku Bar" style="width:100%; max-height:400px; object-fit:cover;">
    </section>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fakku Bar</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #a40000; /* Vermelho */
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #000; /* Preto */
            padding: 10px;
        }
        nav a {
            color: #FFD700; /* Dourado */
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #FFD700; /* Dourado */
            color: #000; /* Preto */
            transition: 0.3s;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .cardapio, .promocoes {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .item {
            border: 1px solid #ccc;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
            width: 30%;
        }
        footer {
            background-color: #000; /* Preto */
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            .item {
                width: 80%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Fakku Bar</h1>
        <p>Slogan: O melhor pagode e drinks de São Paulo!</p>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#programacao">Programação</a>
        <a href="#promocoes">Promoções</a>
        <a href="#cardapio">Cardápio</a>
        <a href="#galeria">Galeria</a>
        <a href="#localizacao">Localização e Contato</a>
    </nav>

    <section id="home">
        <h2>Bem-vindo ao Fakku Bar!</h2>
        <img src="460575885_1259010748853725_7475187610060210292_n.jpg" alt="Ambiente do Fakku Bar" style="width:100%; max-height:400px; object-fit:cover;">
    </section>

    <section id="programacao">
        <h2>Programação</h2>
        <div>
            <p>Confira nossa agenda de shows e DJs!</p>
            <img src="banner-show.jpg" alt="Shows no Fakku Bar" style="width:100%; max-height:300px; object-fit:cover;">
        </div>
    </section>

    <section id="promocoes">
        <h2>Promoções</h2>
        <div class="promocoes">
            <div class="item">
                <h3>Promoção 1</h3>
                <p>50% de desconto em todos os drinks!</p>
            </div>
            <div class="item">
                <h3>Promoção 2</h3>
                <p>Compre 1, leve 2 em porções!</p>
            </div>
        </div>
    </section>

    <section id="cardapio">
        <h2>Cardápio</h2>
        <div class="cardapio">
            <div class="item">
                <h3>Bebidas</h3>
                <p>Caipirinha, Cerveja, e muito mais!</p>
            </div>
            <div class="item">
                <h3>Porções</h3>
                <p>Frango à passarinho, Batata frita, e outras delícias!</p>
            </div>
        </div>
    </section>

    <section id="galeria">
        <h2>Galeria</h2>
        <p>Confira fotos e vídeos do nosso bar!</p>
        <img src="imagem-galeria.jpg" alt="Galeria de imagens do Fakku Bar" style="width:100%; max-height:400px; object-fit:cover;">
    </section>

    <section id="localizacao">
        <h2>Localização e Contato</h2>
        <p>Endereço: Rua Dr. Cesário Mota Jr., nº 629, São Paulo</p>
        <div>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.854679133679!2d-46.65593898502163!3d-23.56442178468106!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce59c0c1d3c7c7%3A0x9b0a30cb4c1837b8!2sFakku%20Bar!5e0!3m2!1spt-BR!2sbr!4v1638324205865!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
        <p>Siga-nos nas redes sociais!</p>
        <a href="https://www.instagram.com/fakkubar" target="_blank">Instagram</a>
    </section>

    <footer>
        <p>&copy; 2023 Fakku Bar. Todos os direitos reservados.</p>
        <p>Faça sua reserva pelo WhatsApp!</p>
    </footer>
</body>
</html>
