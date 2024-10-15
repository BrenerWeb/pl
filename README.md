<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="Portfólio de Brener Souza - Programador em constante aprendizado">
    <meta name="keywords" content="Brener Souza, portfólio, programador, desenvolvedor web">
    <meta name="author" content="Brener C. de Souza">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Meu Portfólio</title>

    <!-- Font Awesome para Ícones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Estilo Geral */
        body {
            background-color: #0e0e0e;
            color: #f8f8f8;
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }

        h1 {
            font-size: 3em;
            text-align: center;
            text-shadow: 0 0 15px #00ff00;
            margin-bottom: 10px;
        }

        h2, h3 {
            color: #00cc00;
            border-bottom: 2px solid #00ff00;
            padding-bottom: 10px;
        }

        a {
            color: #00ff00;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #00cc00;
            text-decoration: underline;
        }

        .container {
            max-width: 960px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
            background-color: #1a1a1a;
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.4);
            animation: fadeIn 1s ease-in-out;
        }

        .project {
            margin: 20px 0;
            padding: 15px;
            border: 1px solid #00ff00;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }

        .project:hover {
            transform: scale(1.05);
            box-shadow: 0 0 25px rgba(0, 255, 0, 0.6);
        }

        img {
            display: block;
            margin: 0 auto;
            border-radius: 50%;
            border: 3px solid #00ff00;
            width: 150px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 5px 0;
        }

        .links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 20px 0;
        }

        .links a {
            font-size: 1.5em;
            transition: transform 0.3s;
        }

        .links a:hover {
            transform: scale(1.1);
        }

        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 0.9em;
            color: #00cc00;
        }

        @media (max-width: 768px) {
            .links {
                flex-direction: column;
                align-items: center;
                
            }
            @media (max-width: 768px) {
    .container {
        padding: 5px; /* Menos espaço interno em telas pequenas */
    }
}

            .project {
                margin: 10px 0;
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>

<body>

    <div class="container">
        <h1>Seja Bem-Vindo ao meu portfolio</h1>
        <img src="brner.jpg" alt="Foto de Brener Souza">

        <h2>Sobre Mim</h2>
        <p>Olá! Sou Brener C. de Souza, programador em constante aprendizado e apaixonado por tecnologia. 
            Amo resolver problemas práticos com código e estou sempre buscando maneiras de aplicar 
            novos conhecimentos em projetos do mundo real. Meu objetivo é contribuir para soluções inovadoras e crescer na área de desenvolvimento.
        </p>

        <h2>Habilidades</h2>
        <ul>
            <li><strong>Linguagens:</strong> Python, JavaScript (ES6+), Java, C#, TypeScript</li>
            <li><strong>Frameworks e Bibliotecas:</strong> React, Node.js, Bootstrap, TailwindCSS</li>
            <li><strong>Ferramentas:</strong> Git/GitHub, Docker, Figma, Visual Studio Code</li>
            <li><strong>Metodologias:</strong> Scrum, Kanban, Agile</li>
        </ul>

        <h2>Cursos</h2>
        <ul>
            <li>Desenvolvimento Web Completo – Cursa Cursos (2023)</li>
            <li>JavaScript e ES6 para Iniciantes – Estacio (2023)</li>
            <li>Fundamentos de Linguagens Python e C++ – Xscript (2024)</li>
            <li>Versionamento com Git e GitHub – Dio.me (2023)</li>
            <li>Desenvolvimento de APIs RESTful – Coursera (2024)</li>
            <li> Endpoint Security – Networking Academy CISCO (2024)</li>
        </ul>

        <h2>Projetos</h2>
        <h2>Projetos</h2>
        <div class="project">
            <h3>Projeto 1: Calculadora de Carbono Pessoal</h3>
            <p>Aplicação web que calcula a pegada de carbono individual.</p>
            <a href="carbono.html" target="_blank">Acessar Projeto</a>
        </div>

        <div class="project">
            <h3>Projeto 2: Dashboard Financeiro Pessoal</h3>
            <p>Interface interativa para controle financeiro com gráficos.</p>
            <a href="controlefinanceiro.html" target="_blank">Acessar Projeto</a>
        </div>
        <div class="links">
            <a href="https://instagram.com/brenersouza" target="_blank">
                <i class="fab fa-instagram"></i> Instagram
            </a>
            <a href="https://github.com/BrenerWeb" target="_blank">
                <i class="fab fa-github"></i> GitHub
            </a>
            <a href="https://www.linkedin.com/in/brener-souza" target="_blank">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
        </div>
    </div>

    <footer>
        <p>© 2024 Brener C. de Souza. Todos os direitos reservados.</p>
    </footer>

    <script>
        document.querySelectorAll('.project').forEach(project => {
            project.addEventListener('click', () => {
                alert('Você abriu um projeto!');
            });
        });
    </script>

</body>
</html>
