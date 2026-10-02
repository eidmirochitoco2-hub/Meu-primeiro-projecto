<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Meu Primeiro Projeto</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            min-height: 100vh;

            background:
                radial-gradient(circle at top, #263238, #0d1117 60%);

            color: white;

            display: flex;
            justify-content: center;
            align-items: center;

            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 800px;

            background: rgba(255, 255, 255, 0.08);

            border: 1px solid rgba(255, 255, 255, 0.15);

            border-radius: 20px;

            padding: 50px 30px;

            text-align: center;

            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.4);

            backdrop-filter: blur(10px);
        }

        .tag {
            display: inline-block;

            padding: 8px 16px;

            border-radius: 30px;

            background: #ffffff15;

            color: #90caf9;

            font-size: 14px;

            margin-bottom: 20px;
        }

        h1 {
            font-size: 48px;

            margin-bottom: 20px;

            background: linear-gradient(
                90deg,
                #ffffff,
                #90caf9
            );

            -webkit-background-clip: text;

            -webkit-text-fill-color: transparent;
        }

        p {
            font-size: 18px;

            line-height: 1.7;

            color: #cfd8dc;

            margin-bottom: 10px;
        }

        .button {
            display: inline-block;

            margin-top: 25px;

            padding: 14px 28px;

            background: #2196f3;

            color: white;

            text-decoration: none;

            border-radius: 10px;

            font-weight: bold;

            transition: 0.3s;
        }

        .button:hover {
            background: #42a5f5;

            transform: translateY(-3px);

            box-shadow: 0 10px 25px rgba(33, 150, 243, 0.35);
        }

        footer {
            margin-top: 35px;

            font-size: 13px;

            color: #90a4ae;
        }

        @media (max-width: 600px) {

            .container {
                padding: 40px 20px;
            }

            h1 {
                font-size: 36px;
            }

            p {
                font-size: 16px;
            }
        }
    </style>
</head>

<body>

    <main class="container">

        <span class="tag">
            🚀 Meu primeiro projeto
        </span>

        <h1>Olá, GitHub!</h1>

        <p>
            Este é o meu primeiro projeto publicado na Internet.
        </p>

        <p>
            Estou a aprender programação,
            desenvolvimento web e GitHub.
        </p>

        <a href="#" class="button">
            Explorar projeto
        </a>

        <footer>
            Criado com HTML e CSS
        </footer>

    </main>

</body>
</html>
