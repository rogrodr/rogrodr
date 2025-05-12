<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Seu Nome] - Perfil</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #1f1f1f, #4b4b4b);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        .card {
            max-width: 600px;
            background: rgba(30, 30, 30, 0.9);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
            text-align: center;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #c1121f;
            margin-bottom: 15px;
            transition: transform 0.3s;
        }
        .profile-img:hover {
            transform: scale(1.1);
        }
        h1 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #fff;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        p {
            font-size: 1em;
            margin-bottom: 20px;
            color: #d1d5db;
        }
        .skills, .contact {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin: 15px 0;
        }
        .skills span, .contact a {
            background: #c1121f;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            transition: background 0.3s, transform 0.2s;
        }
        .skills span:hover, .contact a:hover {
            background: #9b0e18;
            transform: translateY(-3px);
        }
        .contact a {
            color: #fff;
            text-decoration: none;
        }
        .highlight {
            color: #c1121f;
            font-weight: bold;
        }
        footer {
            margin-top: 20px;
            font-size: 0.8em;
            color: #6b7280;
        }
        @media (max-width: 500px) {
            .card {
                padding: 20px;
            }
            h1 {
                font-size: 1.5em;
            }
            p {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="https://via.placeholder.com/120" alt="Foto de Perfil" class="profile-img">
        <h1>👋 Robson Rodrigues</h1>
        <p>Estudante de <span class="highlight">Sistemas</span>, apaixonado por <span class="highlight">desenvolvimento</span> e <span class="highlight">segurança da informação</span>. A prendendo a construo soluções com código e curiosidade!</p>
        
        <div class="skills">
            <span>Java</span>
            <span>JavaScript</span>
            <span>React</span>
            <span>SQL</span>
            <span>Node.js</span>
            <span>HTML/CSS</span>
            <span>Spring Boot</span>
        </div>
        
        <div class="contact">
            <a href="mailto:[seu.email@example.com]" target="_blank">📧 E-mail</a>
            <a href="[Link para LinkedIn]" target="_blank">🔗 LinkedIn</a>
            <a href="[Link para X]" target="_blank">🐦 X</a>
            <a href="https://github.com/[seu-usuario]" target="_blank">💻 GitHub</a>
        </div>
        
        <footer>
            <p>🚀 Explore meus projetos no GitHub! ✨</p>
        </footer>
    </div>
</body>
</html>
