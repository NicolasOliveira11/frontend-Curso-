## Diferença div & HTML semântico
A principal diferença é que a <div> é um elemento genérico, enquanto as tags semânticas descrevem o significado do conteúdo que elas contêm.

## Div
serve apenas para agrupar elementos. Ela não informa ao navegador, mecanismos de busca ou leitores de tela qual é a função daquele conteúdo.

<div>
    <div>
        <h1>Meu Site</h1>
    </div>

    <div>
        <a href="#">Início</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </div>

    <div>
        <h2>Bem-vindo!</h2>
        <p>Este é o conteúdo principal.</p>
    </div>

    <div>
        <p>© 2026 Meu Site</p>
    </div>
</div>

## HTML semântico
O HTML semântico utiliza tags que indicam a função do conteúdo, tornando o código mais organizado, acessível e fácil de entender.

<header>
    <h1>Meu Site</h1>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Sobre</a>
    <a href="#">Contato</a>
</nav>

<main>
    <section>
        <h2>Bem-vindo!</h2>
        <p>Este é o conteúdo principal.</p>
    </section>
</main>

<footer>
    <p>© 2026 Meu Site</p>
</footer>