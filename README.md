<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Portfólio Camile</title>
</head>

<head>
  <style>
    body {
      background-color: rgb(245, 209, 215);
    }
  </style>
</head>

<div style="background-color: #e763ac; padding: 10px; text-align: center;">
  <h2 style="margin: 30; font-weight: bold;"></h2>
</div>


<body>
 
    <header class="container text-center">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTKaHnnVi3zzaIEzIONA8gSohk1yQam2ZVWUg&s" alt="avatar da Camile" class="rounded-circle" width="150" height="150" srcset="">
        <p class="lead">Prazer, sou a Camile!</p>
        <h1>Eu ensino Espanhol</h1>
        <p>Sou estudante do Ensino Médio. Ensino a fala, escuta e escrita em espanhol, e 
            a cultura dos países que tem o espanhol como língua materna, para
            adolescentes e adultos interessados!
            </p>
        <p>Habilidades</p>
        <div>
            <p class="badge bg-secondary">FALA</p>
            <p class="badge bg-secondary">ESCRITA</p>
            <p class="badge bg-secondary">ESCUTA</p>
            <p class="badge bg-secondary">CULTURA</p>
        </div>
     
</body>

</html>
    </header>
    <main class="container mt-5">
        <h2>Veja os meus projetos!</h2>
        <div class="row">
            <!-- Projeto 1 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="https://espanholdeverdade.com.br/wp-content/uploads/2021/06/small-flag-of-spain-on-a-map-background-with-selective-focus-650x650.jpg" class="card-img-top" alt="Imagem do projeto de guia para iniciantes">
                    <div class="card-body">
                        <h5 class="card-title">Meu guia de Espanhol para iniciantes!</h5>
                        <p class="card-text">Criei essa página na web para ajudar quem está começando a aprender Espanhol. Nela
                            compartilho expressões básicas, cumprimentos, e frases do dia a dia, com tradução e pronúncia.
                            É um material leve, visual e ideal para quem quer começar agora!
                        </p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal1">Veja aqui
                            o meu projeto</button>
                    </div>
                </div>
            </div>
            <!-- Projeto 2 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLldS3MNdS8dcie0JG3ShNZN3sfwBvW1kX6A&s" class="card-img-top" alt="Imagem do projeto de aula de espanhol">
                    <div class="card-body">
                        <h5 class="card-title">Aprenda Espanhol com Música!</h5>
                        <p class="card-text">Desenvolvi esse site para ensinar espanhol usando musicas populares. Quem o visita pode ver
                            letras traduzidas, ouvir as musicas e aprender novas palavras e expressões de forma divertida. Ideal para 
                            adolescentes e adultos que desejam aprender espanhol de maneira leve e envolvente.
                        </p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal2">Veja aqui
                            o meu projeto </button>
                    </div>
                </div>
            </div>

            <!-- Projeto 3 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="https://pt.quizur.com/_image?href=https://img.quizur.com/f/img640772b9caad08.04630344.jpg?lastEdited=1678209727&w=600&h=600&f=webp" class="card-img-top" alt="Imagem do projeto de quiz interativo">
                    <div class="card-body">
                        <h5 class="card-title">Quiz: Você entende Espanhol!
                        </h5>
                        <p class="card-text">Esse é um quis interativo com perguntas de vocabulário, gramático e expressões comuns do idioma.
                            Desenvolvido para ajudar iniciantes a testar seus conhecimentos e aprender brincando!
                        </p>
                        <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal3">Veja aqui
                            o meu projeto</button>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Modal 1 -->
    <div class="modal" id="modal1" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Meu Guia de Espanhol para Iniciantes</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>Este projeto é uma página web criada com HTML e CSS para ajudar iniciantes no aprendizado do espanhol. 
                    O objetivo é oferecer um espaço simples e amigável onde os visitantes possam aprender frases básicas, 
                    cumprimentos, vocabulário essencial e dicas úteis para começar a se comunicar em espanhol.</p>
                    <p>A estrutura do site foi feita com HTML para organizar o conteúdo de forma clara e acessível, incluindo 
                    seções como saudações, perguntas comuns e expressões do dia a dia. O CSS é utilizado para deixar a 
                    página visualmente atrativa, com cores suaves, boa tipografia e um design responsivo que funciona bem 
                    em celular ou computador.</p>
                    <p>O conteúdo é organizado de maneira didática: cada bloco apresenta uma expressão em espanhol, sua tradução 
                    para o português e a pronúncia explicada de forma simples. Isso permite que qualquer pessoa comece a 
                    praticar o idioma sem complicação. A ideia é tornar o aprendizado leve, visual e divertido.</p>
                    <p>Esse projeto mostra como é possível ensinar usando ferramentas básicas da web, tornando o conhecimento 
                    acessível para todos. E como aluna do ensino médio, acredito que compartilhar o que aprendemos é uma 
                    das melhores formas de crescer — e ajudar outras pessoas a crescerem também!</p>
                    <img src="img/projeto-1.png" class="https://espanholdeverdade.com.br/wp-content/uploads/2021/06/small-flag-of-spain-on-a-map-background-with-selective-focus-650x650.jpg"
                        alt="Imagem representativa do projeto de Guia para Inicianrtes">
                </div>
                <div class="modal-footer">
                    <a href="https://femascheti.github.io/minhas-leituras/">Ver projeto ao vivo</a>
                    <a href="https://github.com/femascheti/minhas-leituras">Ver código do projeto</a>
                </div>
            </div>
        </div>
    </div>
    <!-- Modal 2 -->
    <div class="modal" id="modal2" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Aprenda Espanhol com Música</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>Este projeto é uma página web interativa que usa músicas populares para ajudar no aprendizado 
                        do espanhol. A ideia é tornar o estudo do idioma mais divertido e envolvente, associando 
                        vocabulário e expressões do dia a dia a canções conhecidas.
                    </p>
                    <p>O site foi desenvolvido com HTML, CSS e JavaScript. O HTML organiza o conteúdo como o nome da
                         música, letra original, tradução e curiosidades sobre os artistas ou trechos importantes.
                          O CSS estiliza a página com um visual colorido, leve e jovem, além de torná-la responsiva
                           para celulares.</p>
                    <p>O JavaScript permite interações como destaque automático das palavras aprendidas na música,
                         troca entre letra original e traduzida, e até um pequeno quiz sobre o vocabulário após ouvir 
                         a canção. Isso deixa o aprendizado mais ativo e prático.</p>
                    <p>Como aluna do ensino médio apaixonada por idiomas, acredito que aprender pode (e deve!) ser 
                        divertido. Usar música é uma maneira incrível de praticar espanhol sem nem perceber que está 
                        estudando — e é exatamente isso que este projeto oferece!
                    </p>
                    <img src="img/projeto-2.png" class="img-fluid w-100"
                        alt="Imagem representativa do projeto de Aprenda Espanhol com Música">
                </div>
                <div class="modal-footer">
                    <a href="https://femascheti.github.io/tecnicas-computacionais-refletindo-sobre-ia/">Ver projeto ao
                        vivo</a>
                    <a href="https://github.com/femascheti/tecnicas-computacionais-refletindo-sobre-ia">Ver código do
                        projeto</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal 3 -->
    <div class="modal" id="modal3" tabindex="-1">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Quiz: Você entende espanhol?</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    <p>Este projeto é uma aplicação web interativa, desenvolvida com HTML, CSS e JavaScript, que 
                        funciona como um quiz para testar seus conhecimentos básicos de espanhol. O objetivo é 
                        ensinar de forma divertida e leve, ajudando as pessoas a fixarem vocabulário, expressões 
                        comuns e gramática básica.</p>
                    <p>A estrutura foi construída com HTML, organizando o conteúdo em seções como tela de início, 
                        perguntas, opções de resposta e a pontuação final. O CSS foi usado para deixar o layout 
                        limpo, colorido e fácil de navegar, com um visual atrativo tanto no computador quanto no 
                        celular. O design é pensado para ser jovem e acessível.</p>
                    <p>O JavaScript dá vida ao quiz, permitindo que o usuário interaja com as perguntas e receba o 
                        resultado ao final. O código permite que cada resposta seja analisada automaticamente, e ao 
                        final, o usuário recebe um feedback sobre seu desempenho, junto com dicas para melhorar seu 
                        espanhol.</p>
                    <img src="img/projeto-3.png" alt="Projeto 3" class="img-fluid w-100">
                </div>
                <div class="modal-footer">
                    <a href="https://scratch.mit.edu/projects/951732825/">Ver projeto ao vivo</a>
                </div>
            </div>
        </div>
    </div>
    <footer class="container py-5">
        <h2>ENTRE EM CONTATO COMIGO!</h2>
        <div>
            <i class="bi bi-github"></i>
            <a href="https://github.com/ferreirac07">GitHub</a>

        </div>
        <p class="my-5 text-center">© Copyright 2024. Produzido por Camile Ferreira.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script> 
</body>
<div style="background-color: #e763ac; padding: 30px; text-align: center;">
  <h2 style="margin: 30; font-weight: bold;"></h2>
</div>
</html>
