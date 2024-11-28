# Portif-lio.finalizar
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #2C3E50, #34495E); /* Gradiente moderno */
            color: #fff;
            line-height: 1.6;
            padding: 0;
            margin: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Cabeçalho */
        header {
            background-color: #1F2A34;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #007bff;
        }

        /* Seções */
        section {
            padding: 60px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #fff;
        }

        section p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1rem;
            color: #BDC3C7;
        }

        /* Card de Projetos */
        .projeto {
            background-color: #2C3E50;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
            margin: 20px;
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .projeto:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
        }

        .projeto img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .projeto h3 {
            font-size: 1.6rem;
            color: #fff;
            margin-bottom: 10px;
        }

        .projeto p {
            font-size: 1rem;
            color: #BDC3C7;
        }

        /* Formulário de Contato */
        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            max-width: 400px;
            margin: 0 auto;
        }

        form input,
        form button {
            padding: 15px;
            font-size: 1.1rem;
            border: none;
            border-radius: 8px;
        }

        form input {
            background-color: #34495E;
            color: #fff;
            border: 2px solid #1F2A34;
        }

        form button {
            background-color: #007bff;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        form button:hover {
            background-color: #0056b3;
        }

        /* Rodapé */
        footer {
            background-color: #1F2A34;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            margin-top: auto;
        }

        footer p {
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <h1>Bem-vindo ao Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Seção Sobre -->
    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Sou um desenvolvedor apaixonado por tecnologia e com grande vontade de aprender. Busco sempre inovar e criar soluções digitais que tragam valor para as pessoas. Tenho experiência com diversas linguagens de programação e frameworks, e estou sempre me atualizando para acompanhar as novas tendências do mercado.</p>
    </section>

    <!-- Seção Projetos -->
    <section id="projetos">
        <h2>Meus Projetos</h2>

        <div class="projeto">
            <img src="https://via.placeholder.com/800x400" alt="Projeto 1">
            <h3>Projeto 1: Página de Portfólio</h3>
            <p>Este é um exemplo de um portfólio simples, com layout moderno e interativo. Ele mostra minhas habilidades em HTML, CSS e JavaScript, e é totalmente responsivo.</p>
        </div>

        <div class="projeto">
            <img src="https://via.placeholder.com/800x400" alt="Projeto 2">
            <h3>Projeto 2: Aplicativo de Tarefas</h3>
            <p>Um aplicativo para gestão de tarefas, desenvolvido com React, permitindo que os usuários possam adicionar, editar e excluir tarefas de forma intuitiva.</p>
        </div>
    </section>

    <!-- Seção Contato -->
    <section id="contato">
        <h2>Entre em Contato</h2>
        <form>
            <input type="text" placeholder="Seu Nome" required>
            <input type="email" placeholder="Seu Email" required>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2024 Ridael Terceiro. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
