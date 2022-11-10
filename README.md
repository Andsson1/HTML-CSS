<! DOCTYPE html>
<html lang="pt-br">
<head>

    <link rel="stylesheet icon"  href="icone.png">
    <script src="https://kit.fontawesome.com/80e6526c1c.js" crossorigin="anonymous"></script>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap" rel="stylesheet">



<link rel="stylesheet" href="aplicação3.css">
<title>HTML</title>
<meta charset="utf-8">
</head>

<body>



<div class="container_segundo">
<div class="menu">
    <ul>
        <li><a  style="    padding: 10px 11px 11px;"  href="file:///C:/Users/and/Desktop/trabalho/principal.html">Ínicio</li></a>
        <li><a  style="    padding: 10px 11px 11px;"  href="file:///C:/Users/and/Desktop/trabalho/tabela.html">Tabela de comparação</li></a>
        <li><a  style="    padding: 10px 11px 11px;"  href="file:///C:/Users/and/Desktop/trabalho/css.html">CSS</li></a>
        <li><a  style="    padding: 10px 11px 11px;"  href="file:///C:/Users/and/Desktop/trabalho/html.html">HTML</li></a>
        <li><a href="file:///C:/Users/and/Desktop/trabalho/feedback.html">Feedback</a></li>
    </ul>
</div>
</div>

<div class="container_logo_site">
    <div class="logotipo">
    <img class="imagem_logotipo" src="https://pbs.twimg.com/media/Cp_Gw0_XEAA337C.jpg" alt="">
</div>
</div>

<div class="container_html_css">
    <div class="container_meio">
    <div class="container_titulo">

       <i class="fab fa-html5"></i> <span>Oque é HTML?</span>

        </div>
        <br>
        <div class="texto_meio">
            Criada pelo britânico Tim Berners-Lee, o acrônimo HTML significa HiperText Markup Language, traduzindo ao português: Linguagem de Marcação de Hipertexto.  O HTML é o componente básico da web, ele permite inserir o conteúdo e estabelecer a estrutura básica de um website. Portanto, ele serve para dar significado e organizar as informações de uma página na web. Sem isso, o navegador não saberia exibir textos como elementos ou carregar imagens e outros conteúdos.
<br>
            Os hipertextos são conjuntos de elementos conectados. Esses podem ser palavras, imagens, vídeos, documento, etc. Quando conectados, formam uma rede de informações que permite a comunicação de dados, organizando conhecimentos e guardando informações.
            <br>
            Ao visitar uma página simples na web, você pode perceber que existem diferentes distribuições e tamanhos para títulos, parágrafos, imagens, vídeos e qualquer outro elemento. Essa estrutura é estabelecida através do HTML. No inicio da web, era comum encontrar sites apenas contendo textos e imagens simples, com estrutura básica e sem estilizações. Porém, nos dias atuais, muito dificilmente você encontrará sites que possuam apenas elementos HTML. Portanto, podemos considerar o HTML o “esqueleto” da sua página.
            <br>
            Imagine então que além do esqueleto, é necessário ter o corpo. Para isso, temos então as linguagens CSS e o JavaScript, que em conjunto com HTML, formam a base para todos os websites atuais. Veremos mais à frente o que significam essas linguagens.



    <div class="container_titulo">

        <i class="fab fa-html5"></i> <span>Como Funciona o HTML</span>

         </div>
         <br>
         <div class="texto_meio1">
            Através de um documento HTML, ou seja, um documento com a extensão .html ou .htm., o navegador faz a leitura do arquivo e renderiza o seu conteúdo para que o usuário final possa visualizá-lo. Os arquivos .html podem ser visualizados em qualquer navegador (como Google Chrome, Safari, ou Mozilla Firefox).
<br>
            Geralmente um site é composto por diversas páginas HTML, como por exemplo: um website que contenha três páginas (uma homepage, uma página de contato e uma página de produtos) receberá ao menos três documentos .html distintos, sendo uma para cada página do website.
     <br>
            O código pode ser escrito através de qualquer editor de texto, como o próprio bloco de notas. Cada página consiste em uma série de tags (também chamados de elementos) que podem ser considerados os blocos de construção das páginas. Portanto, esses blocos são a maneira com a qual o HTML faz a marcação dos conteúdos, criando a hierarquia e a estrutura do mesmo, dividido entre seções, parágrafos, cabeçalhos, e outros.


            <div class="container_titulo">

                <i class="fab fa-html5"></i> <span>Principais tags do HTML</span>

                 </div>
                 <br>
                 <div class="texto_meio2">
                    Atualmente existem mais de 140 tags, mas algumas delas quase não são utilizadas. Dentre as mais utilizadas temos:
<br>
                    head – local para declarar todas informações, como título e metadados da sua página;
                    <br>
                    title – define o título;
                    <br>
                    body – local para declarar todos os elementos que irão compor o corpo da página;
                    <br>
                    h1, h2, h3, h4, h5 e h6 – Tags para definir um título e subtítulos, variando de 1 a 6, sendo h1 o título mais importante e h6 o de menor importância;
                    <br>
                    p – Tag para definir um parágrafo.+;
                    <br>
                    a – Tag de link, junto ao atributo href=”” é responsável pela principal característica da web;
                    <br>
                    heade – define um cabeçalho;
                    <br>
                    sectio – define uma seção;
                    <br>
                    article – define um artigo;
                    <br>
                    div – define uma divisão;
                    <br>
                    footer – define um rodapé;
                    <br>
                    nav – define uma área de navegação (como menus);
                    <br>
                    table – define uma tabela;
                    <br>
                    ol – define uma lista ordenada;
                    <br>
                    ul – define uma lista não ordenada;
                    <br>
                    li – define o item de uma lista;
                    <br>
                    form – define um formulário;
                    <br>
                    input – define os campos do formulário;
                    <br>
                    textarea – define uma área para o usuário digitar um texto;
                    <br>
                    button – define um botão;
                    <br>
                     permite inserir uma imagem no seu documento.




        <div class="container_titulo">

            <i class="fab fa-html5"></i> <span>O que são tags</span>

             </div>
             <br>
             <div class="texto_meio3">
                Através de qualquer editor de texto, como o Sublime Text, o NotePad++ ou até mesmo o bloco de notas, é possível criar um documento com a extensão .html que será renderizado pelos navegadores.
<br>
                Conforme explicado anteriormente, este documento consiste em uma série de tags. As tags são códigos que definem toda a estrutura da página, tais como o seu tamanho, a fonte da letra, as cores, as quebras de linha e etc. A maioria dos elementos do documento HTML são compostos por uma estrutura de abertura e uma de fachamento, como <tag> e </tag>. Há também tags de estrutura única, como a  tag <br/> que realiza uma quebra de linha.
                <br>
                Digamos que você queria escrever um paragrafo, chamamos então a tag p, escrevemos o paragrafo e finalmente fechamos a tag com /p
                <br>
                Meu primeiro paragrafo.
                Dessa forma, ao salvar o arquivo com a extensão .html e abri-lo em um navegador, você verá o parágrafo escrito na tela do navegador.


</div>
</div>
</div>
</div>
</head>
</body>
