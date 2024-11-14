<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Currículo - luanne kathlen</title>
    <meta name="description" content="Currículo profissional de luanne kathlen, Desenvolvedor Web Junior">
    
    <!-- Favicon -->
    <link rel="icon" type="image/svg+xml" href="favicon.svg">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <script src="https://kit.fontawesome.com/your-font-awesome-kit.js" crossorigin="anonymous"></script>

    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2ecc71;
            --accent-color: #e74c3c;
            --background-color: #f9f9f9;
            --text-color: #333;
            --hover-color: #ccc;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color) 40%, var(--secondary-color) 60%);
            padding: 50px 0;
            text-align: center;
            color: white;
        }

        header img {
            width: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-weight: bold;
        }

        header p {
            font-style: italic;
            color: #fff;
        }

        nav {
            background: var(--primary-color);
            padding: 15px 0;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin: 0 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            transition: color 0.3s ease;
            font-weight: bold;
        }

        nav a:hover {
            color: var(--hover-color);
        }

        main {
            padding: 50px 0;
        }

        section {
            background: var(--background-color);
            padding: 30px;
            margin-bottom: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        .skills ul {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .contact-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .contact-info p {
            width: calc(50% - 10px);
            padding: 15px;
            background: #f8f9fa;
            border-radius: 5px;
            margin: 10px 0;
        }

        footer {
            background: var(--secondary-color);
            color: white;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <img src="c:\Users\ALUNO.DESKTOP-Q6LOE4I\Downloads\perfil po github\foto\e162567c-d4bd-4f19-82f4-e4b836733b4b.jpg" alt="luanne kathlen">
            <h1>luanne kathlen</h1>
            <p>Desenvolvedor Web Junior | Novato na área, mas pronto para aprender e crescer!</p>
        </header>

        <nav>
            <ul>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>

        <main>
            <section id="about">
                <h2>Sobre mim</h2>
                <p>Estou começando minha jornada como desenvolvedor web. Tenho conhecimentos básicos em HTML, CSS e estou aprendendo JavaScript.</p>
            </section>

            <section id="skills">
                <h2>Habilidades</h2>
                <div class="skills">
                    <h3>Tecnologias</h3>
                    <ul>
                        <li>HTML5</li>
                        <li>CSS3</li>
                        <li>JavaScript (em aprendizado)</li>
                    </ul>

                    <h3>Linguagens de programação</h3>
                    <ul>
                        <li>Python (básico)</li>
                        <li>Java (básico)</li>
                    </ul>
                </div>
            </section>

            <section id="experience">
                <h2>Experiência Profissional</h2>
                <p>Atualmente estou buscando minha primeira oportunidade no mercado de trabalho. Estou disposto a aprender e crescer com uma equipe dedicada.</p>
            </section>

            <section id="contact">
                <h2>Contato</h2>
                <div class="contact-info">
                    <p>Email: luannekathlendasilva@email.com</p>
                    <p>Instagram: im_luanne</p>
                </div>
            </section>
        </main>

        <footer>
            &copy; 2024 luanne kathlen. Todos os direitos reservados.
        </footer>
    </div>

    <!-- JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.7.2/dist/jquery.fancybox.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-1:55E4STXj/GN1CmZZ8pzyf/MuhRGnypiD7ZJvuCN2rF2doGwIb5d26vjo6P0Y1:0" crossorigin="anonymous"></script>
</body>
