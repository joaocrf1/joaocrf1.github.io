<!DOCTYPE html> <!--teste-->
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="Author" content="Juan Tavares">
    <title>Meu currículo</title>
    <style>
        body {
            background-color: rgb(196, 245, 245);
        }
        main {
            padding: 0;
            margin: 10px;
            height: 100vh;
        }
        .container {
            padding: 0;
            margin: 0;
            width: 90vw;
            height: 90vh;
            display: flex;
            justify-content: space-between;
            align-items: stretch;
        }
        header {
            display: flex;
            width: 95vw;
            justify-content: center;
            background-color: aqua;
            border-color: dodgerblue;
            border: solid;
            padding: 0;
            margin: 0;
        }
        .left, .right {
            border-color: black;
            border: solid;
            display: flex;
            flex: 1;
            flex-direction: column;
            height: 70vh;
            justify-content: space-between;
            align-items: center;
        }
        .projects {
            border: solid;
            background-color: rgb(0, 247, 255);
        }
        .profilePhoto {
            width: 200px;
            height: 200px;
            border-radius: 50%;
        }
        .center {
            display: flex;
            flex: 2;
            justify-content: center;
        }
        div.verticalLine {
            display: flex;
            height: 640px;
            background-color: black;
            margin: 0 10px;
            width: 1px;
        }
        div.center ul {
            display: flex;
            justify-content: space-around;
            align-content: space-around;
            height: 50vh;
            flex-direction: column;
        }
        li {
            flex: 1 1 30%;
        }
        .experiences {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .courses {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        footer div {
            position: fixed;
            bottom: 0;
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            height: 50px;
            width: 95vw;
            background-color: black;
        }
        footer div.socialMedias img {
            width: 50px;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <header>
        <h1 class="title">Meu Portifólio</h1>
    </header>
    <main>
        <div class="container">
            <div class="left">
                <img src="imagens/perfil.jpg" alt="Minha foto de perfil" class="profilePhoto">
                <h1>Juan Tavares Marcolino Lirio</h1>
                <p>
                    Olá, tudo bem? Me chamo Juan e gosto muito de computadores e sistemas no geral, 
                    sempre me interessei por como as coisas funcionavam então sempre me dedico a programação,
                    desenvolvimento web, T.I. e tudo o que eu julgar interessante!
                </p>
                <h3>(27) 99692-6803</h3>
                <h3>juan.lirio010@gmail.com</h3>
            </div>
            <div class="center">
                <div class="skill">
                    <h2>Minhas habilidades:</h2>
                    <ul>
                        <li>Informática básica</li>
                        <li>Word, Power Point e Excel básicos</li>
                        <li>Java básico</li>
                        <li>Python 3 básico</li>
                        <li>HTML5 e CSS3 básicos</li>
                        <li>Redes de Computadores</li>
                    </ul>
                </div>
                <div class="verticalLine"></div>
                <div class="competence">
                    <h2>Minhas competências:</h2>
                    <ul>
                        <li>Adaptabilidade</li>
                        <li>Comprometimento</li>
                        <li>Proatividade</li>
                        <li>Comunicação</li>
                        <li>Controle emocional</li>
                        <li>Foco</li>
                    </ul>
                </div>
            </div>
            <div class="right">
                <div class="experiences">
                    <h2>Experiências:</h2>
                    <ul>
                        <li>SEAG - Estagiário - Suporte de TI</li>
                        <li>HT TECNOLOGIA - Estagiário - Infraestrutura de TI</li>
                    </ul>
                    <a href="projetos.html" class="projects">Projetos</a>
                </div>
                <div class="courses">
                    <h2>Cursos:</h2>
                    <ul>
                        <li>FAESA - Faculdade presencial - Tecnólogo em Análise e Desenvolvimento de Sistemas</li>
                        <li>Almirante Barroso - Técnico Integrado ao Ensino Médio - Redes de Computadores</li>
                        <li>BIT Laranjeiras - Curso presencial - Informática Básica</li>
                        <li>Rocketseat - Curso online - Aplicação em Java</li>
                        <li>SEBRAE - Curos online - Introdução a Jogos</li>
                    </ul>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <div class="socialMedias">
            <a href="https://github.com/juant-tavares/" target="_blanc">
                <img src="imagens/github.png" alt="Github">
            </a>
            <a href="https://www.linkedin.com/in/juan-tavares-21400724a" target="_blanc">
                <img src="imagens/linkedin.png" alt="linkedin">
            </a>
            <a href="https://www.instagram.com/juan_lirio01/" target="_blanc">
                <img src="imagens/instagram.jpg" alt="Instagram">
            </a>
        </div>
    </footer>
</body>
</html>
