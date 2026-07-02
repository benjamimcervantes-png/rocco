<button id="btnTema">🌙 Modo Escuro</button>

<article>
    <h2>Meu Hat-Trick Jogando com os Amigos do Meu Irmão ⚽🔥</h2>

    <p class="data">📅 17 de Janeiro de 2026</p>

    <img src="https://picsum.photos/600/300?random=17" alt="Jogo de futebol">

    <p>
        Ontem fui jogar futebol com os amigos do meu irmão mais velho.
        A maioria dos jogadores era adulta, mas também tinham três
        garotos da minha idade participando da partida.
    </p>

    <p>
        Durante o jogo, eu joguei tanto na linha quanto no gol. Quando
        estava na linha, consegui fazer uma ótima partida e marquei
        3 gols, completando um hat-trick.
    </p>

    <p>
        Também joguei como goleiro em alguns momentos. Fiz várias
        defesas e consegui ajudar meu time, mesmo tomando alguns gols.
        Foi uma experiência diferente e divertida poder jogar em duas
        posições.
    </p>

    <p>
        No final, nosso time acabou perdendo o jogo. Mesmo assim,
        fiquei muito feliz porque me esforcei bastante, marquei três
        gols e ainda consegui fazer algumas boas defesas no gol.
    </p>

    <p>
        Foi um dia muito divertido e uma experiência que vou lembrar
        por bastante tempo. Espero continuar melhorando e ter mais
        partidas assim no futuro.
    </p>
</article>
CSS
body{
    background-color: #87CEFA; /* Azul claro */
    color: black;
    font-family: Arial, sans-serif;
    transition: 0.3s;
}

article{
    background: white;
    padding: 20px;
    border-radius: 10px;
}

#btnTema{
    background-color: #1565C0;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 8px;
    cursor: pointer;
    font-size: 16px;
    margin: 20px;
}

.dark-mode{
    background-color: #001F54; /* Azul escuro */
    color: white;
}

.dark-mode article{
    background-color: #0B3D91;
    color: white;const botao = document.getElementById("btnTema");

botao.addEventListener("click", function() {
    document.body.classList.toggle("dark-mode");

    if (document.body.classList.contains("dark-mode")) {
        botao.textContent = "☀️ Modo Claro";
    } else {
        botao.textContent = "🌙 Modo Escuro";
    }
});
