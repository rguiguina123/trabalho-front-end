<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Saiba mais sobre o Dia Internacional para a Eliminação da Violência contra a Mulher e como podemos unir forças para combater a violência de gênero.">
    <title>Dia Internacional Contra a Violência à Mulher</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-image: url('background-image.jpg');
            background-size: cover;
            background-attachment: fixed;
        }

        header {
            background-color: #f04a64;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            background-color: #d9435f;
            display: flex;
            justify-content: center;
            padding: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            margin-top: 20px;
            margin-bottom: 20px;
        }

        section {
            margin-bottom: 40px;
        }

        section h2 {
            color: #d9435f;
            margin-bottom: 10px;
        }

        section p {
            margin-bottom: 10px;
        }

        .campaign {
            background-color: #ffe4e9;
            border-left: 5px solid #f04a64;
            padding: 15px;
            margin-bottom: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        footer a {
            color: #f04a64;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Form Styles */
        .signup-form {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 5px;
        }

        .signup-form h3 {
            margin-top: 0;
        }

        .signup-form input[type="text"],
        .signup-form input[type="email"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .signup-form button {
            background-color: #f04a64;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }

        .signup-form button:hover {
            background-color: #d9435f;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dia Internacional Contra a Violência à Mulher</h1>
        <p>Unidos para eliminar a violência de gênero</p>
    </header>

    <nav class="nav nav-tabs">
        <a class="nav-item nav-link active" data-toggle="tab" href="#sobre">Sobre</a>
        <a class="nav-item nav-link" data-toggle="tab" href="#campanhas">Campanhas</a>
        <a class="nav-item nav-link" data-toggle="tab" href="#lei">Lei Maria da Penha</a>
        <a class="nav-item nav-link" data-toggle="tab" href="#cadastro">Cadastro</a>
    </nav>

    <main class="tab-content">
        <section id="sobre" class="tab-pane fade show active">
            <h2>O que é?</h2>
            <p>
                O Dia Internacional para a Eliminação da Violência contra a Mulher é celebrado em 25 de novembro. Essa
                data foi estabelecida pelas Nações Unidas para conscientizar sobre a violência que milhões de mulheres
                enfrentam diariamente em todo o mundo.
            </p>
            <p>
                A violência contra a mulher pode assumir diversas formas, como a violência física, psicológica, sexual
                e patrimonial. Segundo a ONU, uma em cada três mulheres no mundo já sofreu algum tipo de violência.
            </p>
        </section>

        <section id="campanhas" class="tab-pane fade">
            <h2>Campanhas</h2>
            <div class="campaign">
                <h3>#NemMais1MinutoDeSilêncio</h3>
                <p>
                    Essa campanha promove a conscientização e o incentivo à denúncia de casos de violência contra a
                    mulher. É um esforço conjunto entre organizações e a sociedade para combater essa prática.
                </p>
            </div>
            <div class="campaign">
                <h3>Campanha UNiTE</h3>
                <p>
                    Lançada pela ONU em 2008, a campanha UNiTE busca eliminar a violência contra mulheres e meninas
                    até 2030. Com ações globais, promove a conscientização e a discussão sobre soluções.
                </p>
            </div>
        </section>

        <section id="lei" class="tab-pane fade">
            <h2>Lei Maria da Penha</h2>
            <p>
                A Lei Maria da Penha, criada em 2006, é um marco na luta contra a violência doméstica no Brasil. Ela
                garante direitos às vítimas, como medidas protetivas, afastamento do agressor e apoio psicológico.
            </p>
            <p>
                Além disso, a lei prevê acompanhamento policial e proteção no ambiente de trabalho, para que as mulheres
                possam viver com segurança e dignidade.
            </p>
        </section>

        <section id="cadastro" class="tab-pane fade">
            <h2>Cadastre-se para receber novidades</h2>
            <div class="signup-form">
                <h3>Fique por dentro</h3>
                <p>Receba informações e atualizações sobre a luta contra a violência de gênero.</p>
                <form action="#" method="POST">
                    <input type="text" name="nome" placeholder="Seu nome" required>
                    <input type="email" name="email" placeholder="Seu email" required>
                    <button type="submit">Cadastrar</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <p>
            &copy; 2024 - Dia Internacional Contra a Violência à Mulher. Desenvolvido como projeto acadêmico. Saiba mais
            em <a href="https://dia-internacional-para-git-c361f6-gabryellas-projects-32e9ea44.vercel.app/">nosso site original</a>.
        </p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
