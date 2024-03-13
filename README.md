# lucas-melo 
HTML (index.html):
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wiki de Inteligência Artificial</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Wiki de Inteligência Artificial</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#introducao">Introdução</a></li>
            <li><a href="#historia">História</a></li>
            <li><a href="#aplicacoes">Aplicações</a></li>
            <li><a href="#tecnologias">Tecnologias</a></li>
            <li><a href="#etica">Ética</a></li>
            <li><a href="#referencias">Referências</a></li>
        </ul>
    </nav>
    <main>
        <section id="introducao">
            <h2>Introdução</h2>
            <p>A inteligência artificial (IA) é um campo da ciência da computação que se concentra na criação de sistemas que podem realizar tarefas que normalmente exigiriam inteligência humana. Essas tarefas incluem aprendizado, raciocínio, percepção, tomada de decisão, compreensão da linguagem natural e interação social.</p>
        </section>
        <section id="historia">
            <h2>História</h2>
            <p>A história da inteligência artificial remonta às décadas de 1950 e 1960, com os primeiros estudos sobre redes neurais e programas de computador capazes de simular o pensamento humano. Desde então, a IA evoluiu significativamente, com marcos como o surgimento do aprendizado de máquina e das redes neurais profundas.</p>
        </section>
        <section id="aplicacoes">
            <h2>Aplicações</h2>
            <p>A inteligência artificial é amplamente utilizada em uma variedade de campos, incluindo medicina, finanças, manufatura, transporte, entretenimento e muito mais. Exemplos de aplicações incluem sistemas de diagnóstico médico, algoritmos de negociação de ações, robôs industriais, assistentes virtuais e carros autônomos.</p>
        </section>
        <section id="tecnologias">
            <h2>Tecnologias</h2>
            <p>Existem várias tecnologias fundamentais que impulsionam o campo da inteligência artificial, incluindo aprendizado de máquina, redes neurais artificiais, processamento de linguagem natural, visão computacional e algoritmos de otimização. Cada uma dessas tecnologias tem suas próprias técnicas e algoritmos específicos.</p>
        </section>
        <section id="etica">
            <h2>Ética</h2>
            <p>A IA também levanta questões éticas importantes, incluindo preocupações com privacidade, viés algorítmico, substituição de empregos humanos, autonomia de máquinas e responsabilidade legal. Essas questões estão moldando o debate sobre o desenvolvimento e o uso responsável da inteligência artificial.</p>
        </section>
    </main>
    <footer>
        <p>© 2024 Wiki de Inteligência Artificial. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

CSS (styles.css):

/* Reset CSS básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilos básicos para o corpo do documento */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    font-size: 2em;
}

nav ul {
    list-style-type: none;
    text-align: center;
    padding: 10px 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #333;
    text-decoration: none;
}

nav ul li a:hover {
    color: #555;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
