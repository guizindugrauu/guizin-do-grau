git clone https://github.com/username/username.github.io
cd guizin.github.io
git add --all
git commit -m "Adicionando código HTML inicial"
git push -u origin main
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Pessoal de Guilherme</title>
    <!-- Adicione um favicon -->
    <link rel="icon" href="C:\Users\Guilherme\AppData\Local\Temp\527487b9-f4cb-449f-8599-4a0f9f81c1ee_favicon_io.zip.1ee\favicon.ico" type="image/x-icon">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            color: #333333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333333;
            padding: 20px 0;
            text-align: center;
            border-bottom: 3px solid #ffcc00; /* Linha amarela na parte inferior do cabeçalho */
        }
        header h1 {
            margin: 0;
            font-size: 36px;
            color: #ffffff;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* Sombra no texto do cabeçalho */
        }
        nav {
            background-color: #666666;
            padding: 10px 0;
            text-align: center;
            border-bottom: 2px dashed #ffffff; /* Linha pontilhada branca na parte inferior da navegação */
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold; /* Texto em negrito nos links de navegação */
            transition: all 0.3s ease; /* Transição suave */
        }
        nav a:hover {
            text-decoration: underline;
            color: #ffcc00; /* Cor dos links de navegação ao passar o mouse */
            transform: scale(1.1); /* Efeito de escala */
        }
        main {
            padding: 20px;
        }
        .video-container {
            margin-bottom: 20px;
            text-align: center;
        }
        iframe {
            width: 80%;
            height: 400px;
            border: 5px solid #333333; /* Borda sólida grossa ao redor do vídeo */
            border-radius: 10px; /* Borda arredondada */
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2); /* Sombra ao redor do vídeo */
        }
        .article-link {
            display: block;
            color: #ff4444;
            text-decoration: none;
            font-size: 18px;
            margin-bottom: 10px;
            text-align: center;
            transition: all 0.3s ease; /* Transição suave */
        }
        .article-link:hover {
            text-decoration: underline;
            color: #cc0000; /* Cor dos links dos artigos ao passar o mouse */
            transform: rotate(5deg); /* Efeito de rotação */
        }
        footer {
            background-color: #333333;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
            border-top: 3px solid #ffcc00; /* Linha amarela na parte superior do rodapé */
        }
        footer img {
            max-width: 200px; /* Definindo um tamanho máximo para a imagem do Flamengo */
            height: auto; /* Mantém a proporção da imagem */
        }
        form {
            margin-top: 20px;
            text-align: left;
            border: 2px solid #666666; /* Borda sólida ao redor do formulário */
            padding: 20px;
            border-radius: 10px; /* Borda arredondada */
            background-color: #f9f9f9; /* Cor de fundo do formulário */
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        textarea {
            width: calc(100% - 20px);
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            font-family: Arial, sans-serif; /* Fonte do formulário */
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease; /* Transição suave */
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>SITE DO GUIZIN</h1>
    </header>
    <nav>
        <a href="#videos">Vídeos</a>
        <a href="#articles">Artigos</a>
        <a href="#contact">Contato</a>
    </nav>
    <main>
        <section id="videos">
            <h2>Vídeos</h2>
            <div class="video-container">
                <!-- Substitua os IDs dos vídeos abaixo pelos IDs reais dos seus vídeos do YouTube -->
                <iframe src="https://www.youtube.com/embed/qTLlMMWN_V8" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>
        <section id="articles">
            <h2>Artigos</h2>
            <a class="article-link" href="#">se você leu isso</a>
            <a class="article-link" href="#">meu amigo...</a>
            <a class="article-link" href="#">eu comi seu cu kkkkkkkkkkk</a>
        </section>
        <section id="contact">
            <h2>Contato</h2>
            <form action="#" method="post">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>
                <label for="phone">Telefone:</label>
                <input type="tel" id="phone" name="phone"><br>
                <label for="instagram">Instagram:</label>
                <input type="text" id="instagram" name="instagram"><br>
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" rows="4"></textarea><br>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </main>
    <footer>
        <img src="https://imagepng.org/wp-content/uploads/2017/10/crf-flamengo-2-1.png">
    </footer>
</body>
</html>

