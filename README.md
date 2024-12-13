<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scout de Jogos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Scout de Jogos</h1>
    </header>
    <main>
        <form id="scout-form">
            <label for="jogador">Nome do Jogador:</label>
            <input type="text" id="jogador" required>
            
            <label for="posicao">Posição:</label>
            <select id="posicao">
                <option value="Ataque">Ataque</option>
                <option value="Defesa">Defesa</option>
                <option value="Meio">Meio</option>
            </select>
            
            <label for="pontos">Pontos Marcados:</label>
            <input type="number" id="pontos" min="0" required>

            <button type="button" id="adicionar">Adicionar</button>
        </form>

        <section id="resultado">
            <h2>Resultados do Scout</h2>
            <ul id="lista-scout"></ul>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
