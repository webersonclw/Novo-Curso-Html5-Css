<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Outras Formatações</title>
</head>
<body>
    <h1>Imagem Dinamica</h1>
    <p>Tente abrir esse site em varios dispositivos diferentes ou simplesmente aumente e diminua o tamanho do seu navegador</p>

    <picture>
        <source media="(max-width: 750px)" srcset="imagens/foto-p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="imagens/foto-m.png" type="image/png">
        <img src="imagens/foto-g.png" alt="Imagem Flexivel">
    </picture>
    
    <h1>Reproduzindo Audio</h1>
        <p>Vamos aprender a reproduzir audio em Html.</p>
        <audio preload="metadata" autoplay controls loop>
            <source src="midias/09-911.mp3" type="audio/mpeg">
            <source src="midias/09-911.mp3" type="audio/ogg">
            <source src="midias/09-911.mp3" type="audio/wav">
            <p>Infelizmente seu navegador não consegue reproduzir audio. <a href="midias/09-911.mp3"> Clique aqui para baixar o arquivo Mp3</a></p>
    </audio>
    
    <h1>Usando Links Externos</h1>
<p>Voce pode acessar meu <a href="https://github.com/webersonclw" target="_blank" rel="external"> repositorio publico do GitHub</a></p> <!--esse comando (target="_blank" rel="external">) faz com que se abra outra aba no navegador, assim não fechando sua aba de navegção principal-->
<p>Voce Tambem pode acessar o meu <a href="https://www.youtube.com/channel/UCmk7O5LVGCR6QK4YSXa89-g" target="_blank" rel="external"> canal do YouTube</a></p>
    <h1>Outras Formatações</h1>
    <h2>Codigo-Fone</h2>
    <p>O comando <code>document.getElementById('TEST')</code> é escrito em liguagem javaScript</p>
<pre> <!--pre faz com que o texto seja printado do mesmo geito que foi digitado-->
    <code>
num = int(input('Digite um Numero'))
if num % 2 == 0:
    print(f'O numero {num} é PAR')
else:
    print(f'O numero {num} é IMPAR')
print('FIM DO PROGRAMA')
    </code>
</pre>
<h2>Citações </h2>
<p>Como diria o pai de um amigo: <q> computador é um burro muito rapido</q></p> <!--usar o (q) para citações não aspas direto-->
<h2>Citações Diretas</h2>
<p>Segundo Jeff Nobel, no seu livro HTML para leigos</p>
<blockquote cite="https://books.google.com.br/books?id=E8ZtDwAAQBAJ&printsec=frontcover&hl=pt-BR&source=gbs_ge_summary_r&cad=0#v=onepage&q&f=false"> 
    A diferençã dos elemntos  do livro parece ser muito bo segundo o autor deste livro
</blockquote>
<h2>Abreviações</h2>
<p>Estou aprendendo javaScrip <abbr title="HiperText Markup language">HTML</abbr>,<abbr title="Cascading Style Sheets "> CSS </abbr> muito top</p>
<h2>Texto Ivertido</h2>
<p><bdo dir="rtl">Estou aprendendo a fazer sites.</bdo></p>
    
<h1>Trabalhando com listas</h1>
<h2>Listas Ordenadas</h2>
<ol type="1"><!--start="3" serve para estartar a numeração apartir de um ponto, tipo apartir do numero 5(esses do tipo A, a, I, i)-->
    <li>Acordar</li>
    <li>Ligar para Pedro</li>
    <li>Tomar cafe</li>
    <li>Escovar os dentes</li>
    <li>Trabalho</li>
    <li>Almoço</li>
    <li>Cafe Tarde</li>
    <li>Voltar para casa</li>
    <li>Academia</li>
    <li>Voltar casa</li>
    <li>Jantar</li>
</ol>
<h2>Lista não ordenada</h2>
<ul type="square"> <!--tipos são disc, circle, square-->
    <li>Leite</li>
    <li>Pão</li>
    <li>Tomate</li>
    <li>Alface</li>
    <li>Arroz</li>
    <li>Feijão</li>
    <li>Manteiga</li>
</ul>
    </ul>
<h2>Minhas Linguagens Favoritas</h2>
<ol>
    <li>Antigas</li>
    <ol type="a">
        <li>Cliper</li>
        <li>Visual</li>
        <li>Fortran</li>
        <li>Delphi</li>
    </ol>
    <li>Novas</li>
    <ol type="a">
        <li>PHP</li>
        <li>Python</li>
        <li>JAvaScript</li>
        <li>Kotlin</li>
    </ol>
</ol>
<h2>Meus Jogos FAvoritos</h2>
<ol>
    <li>NES</li>
    <ul type="square">
        <LI>Mario Bros</LI>
        <ul type="circle">
            <li>Mario: lost levels</li>
            <li>Mario Bros 3</li>
        </ul>
        <li>Ninja Gaiden</li>        
    </ul>
    <li>SNES</li>
    <ul type="square">
        <li>Mario</li>
        <li>Donkey kong</li>
    </ul>
    <li>Playstatin</li>
    <ul type="square">
        <li>Final Fantasy</li>
        <li>Castlevania</li>
    </ul>
</ol>
<h2>Lista de Definições</h2>
<dl>
    <dt>HTML5</dt>
    <dd>Linguagem de marcação para criação do conteudo do site</dd>
    <dt>CSS</dt>
    <dd>Linguagem de marcação para criação do desing de um site</dd>
    <dt>JavaScript</dt>
    <dd>Linguargem de programação de interatividade de um site</dd>
</dl>
    <h1>Link para donwload </h1>
    <ul>
        <li><a href="livros/Curriculum-Programador.pdf" download="Meu Curriculun.pdf" type="application/pdf"> Baixar o Livro em PDF</a></li>
        <li><a href="livros/Curriculum-Programador.rar"> Livro Compactado em .RAR</a></li>
    </ul>

</body>
</html> 
