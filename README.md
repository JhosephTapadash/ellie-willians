# ellie-willians
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ellie Williams - The Last of Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table, th, td {
            border: 1px solid #000;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        form label {
            display: block;
            margin-top: 10px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
        }

        form input[type="submit"] {
            width: auto;
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ellie Williams - The Last of Us</h1>
        <nav>
            <ul>
                <li><a href="#home">Página Inicial</a></li>
                <li><a href="#personagens">Personagens</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#autores">Autores</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Bem-vindo ao site dedicado a Ellie Williams</h2>
            <p>Este site é dedicado à personagem Ellie Williams do jogo "The Last of Us". Aqui você encontrará informações sobre os personagens, episódios e muito mais.</p>
            <img src="ellie.jpg" alt="Ellie Williams" style="max-width: 100%; height: auto;">
        </section>

        <section id="personagens">
            <h2>Personagens</h2>
            <ul>
                <li>Ellie Williams</li>
                <li>Joel Miller</li>
                <li>Tess</li>
                <li>Tommy Miller</li>
            </ul>
            <h2>Episódios</h2>
            <table>
                <tr>
                    <th>Nome do Episódio</th>
                    <th>Descrição</th>
                </tr>
                <tr>
                    <td>Episódio 1</td>
                    <td>Introdução de Ellie</td>
                </tr>
                <tr>
                    <td>Episódio 2</td>
                    <td>Jornada com Joel</td>
                </tr>
            </table>
        </section>

        <section id="contato">
            <h2>Contato</h2>
            <form action="/submit_form" method="POST">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea><br><br>
                <input type="submit" value="Enviar">
            </form>
        </section>

        <section id="autores">
            <h2>Autores</h2>
            <p>Este site foi criado por fãs de Ellie Williams.</p>
            <ul>
                <li>Autor 1: Especialista em desenvolvimento web</li>
                <li>Autor 2: Fã de "The Last of Us"</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Ellie Williams Fan Site</p>
    </footer>
</body>
</html>
