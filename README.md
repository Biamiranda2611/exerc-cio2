<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial do Portfólio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .pagina {
            display: grid;
            grid-template-areas:
                "cabeçalho cabeçalho cabeçalho"
                "navegação conteúdo conteúdo"
                "navegação rodapé rodapé";
            grid-template-columns: 200px 1fr 1fr;
            grid-template-rows: 100px 1fr 50px;
            gap: 20px;
            height: 100vh;
        }

        .cabeçalho {
            grid-area: cabeçalho;
            background: #333;
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .navegação {
            grid-area: navegação;
            background: #f4f4f4;
            padding: 20px;
        }

        .conteúdo {
            grid-area: conteúdo;
            background: #fff;
            padding: 20px;
        }

        .rodapé {
            grid-area: rodapé;
            background: #333;
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="pagina">
        <header class="cabeçalho">Cabeçalho</header>
        <nav class="navegação">Navegação</nav>
        <main class="conteúdo">Conteúdo Principal</main>
        <footer class="rodapé">Rodapé</footer>
    </div>
</body>
</html>
