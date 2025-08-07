<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página do Estudante - Higor</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        :root {
            --cor-principal: #3498db;
            --cor-secundaria: #2c3e50;
            --cor-fundo: #ecf0f1;
            --cor-card: #ffffff;
            --cor-texto-claro: #f4f6f7;
            --cor-texto-escuro: #34495e;
            --sombra: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--cor-fundo);
            color: var(--cor-texto-escuro);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: var(--cor-secundaria);
            color: var(--cor-texto-claro);
            padding: 40px 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: var(--sombra);
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .grid-materias {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card-materia {
            background-color: var(--cor-card);
            border-radius: 10px;
            padding: 25px;
            box-shadow: var(--sombra);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .card-materia:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
        }

        .card-materia a {
            text-decoration: none;
            color: var(--cor-principal);
            font-weight: 700;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }

        .card-materia a:hover {
            color: var(--cor-secundaria);
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Bem-vindo, Higor!</h1>
            <p>Selecione uma matéria para acessar o conteúdo.</p>
        </header>

        <section class="grid-materias">
            <div class="card-materia">
                <a href="biologia.html">Biologia</a>
            </div>
            <div class="card-materia">
                <a href="quimica.html">Química</a>
            </div>
            <div class="card-materia">
                <a href="ingles.html">Inglês</a>
            </div>
            <div class="card-materia">
                <a href="ed_financeira.html">Educação Financeira</a>
            </div>
            <div class="card-materia">
                <a href="ed_fisica.html">Educação Física</a>
            </div>
            <div class="card-materia">
                <a href="fisica.html">Física</a>
            </div>
            <div class="card-materia">
                <a href="matematica.html">Matemática</a>
            </div>
            <div class="card-materia">
                <a href="portugues.html">Português</a>
            </div>
            <div class="card-materia">
                <a href="projeto_de_vida.html">Projeto de Vida</a>
            </div>
            <div class="card-materia">
                <a href="filosofia.html">Filosofia</a>
            </div>
            <div class="card-materia">
                <a href="pensamento_computacional.html">Pensamento Computacional</a>
            </div>
            <div class="card-materia">
                <a href="geografia.html">Geografia</a>
            </div>
            <div class="card-materia">
                <a href="historia.html">História</a>
            </div>
        </section>
    </div>

</body>
</html>
