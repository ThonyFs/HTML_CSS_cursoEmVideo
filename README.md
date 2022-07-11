# HTML_CSS_cursoEmVideo
curso HTML5 &amp; CSS3 do canal Curso em Vídeo.   

* https://www.w3schools.com/charsets/ref_utf_symbols.asp (link para pag de simbolos)
* mockflow.com (projetar a pag web)
* https://erikasarti.com/html/dingbats-simbolos-desenhos/ (simbolos) 
* https://emojipedia.org/ (link para pag de emoji)
* https://unsplash.com/ ( biblioteca de imagens com licenças)
* www.pexels.com (biblioteca de imagens com licenças)
* https://iconarchive.com/ (biblioteca de icones)
* https://www.favicon.cc/ (pag para criar icones)
* https://favicon.io/ (pag para gerar icone)
* https://www.iana.org/assignments/media-types/media-types.xhtml (lista de todos os medias type)
* https://handbrake.fr/ (ferramenta para converter videos)
* https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/13%20-%20Cores.pdf (pdf referente a cores)
* https://color.adobe.com/pt/create/color-wheel (gerenciar paleta de cores)
* http://www.paletton.com/ (gerenciador de paleta de cores com simulador de pag web)
* chrome web store > colorzilla (plugin para coletar cores de paginas web)
* chrome web store > Fonts Ninja (plugin capturar fonts de site)
* https://fonts.google.com/ (site de fontes externas)
* https://www.whatfontis.com/ (captura font de fotos)
* https://www.dafont.com/pt (download de fonts)
<hr>

## ESTRUTURA BASICA HTML
* Informar: < !DOCTYPE html>
* < html lang="pt-br"> informa que o site será em portugues < /html>
* < head> < /head>  
* < meta charset="UTF-8"> informa que o site e compativel com caracteres UTF-8
* < meta name="viewport" <br>
 content="width=device-width, initial-scale=1.0"> (informa que o site sera reproduzido em scala de 100% da tela) <br>
* < title> < /title> titulo da pagina
* < body> < /body>

<hr>

# Exemplo da estrutura basica:
< !DOCTYPE hmtl> <br> 
< html lang="pt-br"> <br>
....  < head> (essa é a area de configuracao) <br>
....  < meta charset="UTF-8"> <br>
....  < meta name="viewport" <br>
content="width=device-width, initial-scale=1.0"> <br>
....  < title> titulo da pagina < /title > <br>
....  < /head> <br>
....  < body> (aqui fica o corpo do site) <br>
....  < h1>Olá, Mundo! < /h1> <br>
....  < /body> <br>
  < /html>
<hr>

## COMANDOS HTML
Aberturas de tag ( demonstrada em " < > " ) na maioria das vez a tag deve ser fechada ( < / >)

* < hr> para criar um linha horizontal, essa tag não necessita fechamento.
* Exemplos de titulos: < h1 > exemplo de título < /h1 > 
* Exemplo de paragrafo: < p > exemplo de paragrafo < /p >
* Exemplo de imagem: < img src="foto.png" alt="exemplo de foto" >
dentro da tag onde não tem fechamento, essa tag de imagem possui PARAMETROS ( SRC , ALT) seus valores estão entre aspas ( " " ).
- SRC = origem da foto ( seu titulo)
- ALT = texto alternativo
* < br> para quebrar linha em um paragrafo
* utilize "&lt ;" e "&gt ;" para implementar os sinais < > na execução. <br>
* Para adicionar emoji: <br>
.... Vamos adicionar alguns emoji: <br>
.... &#x1F47D; &#x1F596; <br>
para declarar o emoji utilizamos, "&#x" seguido do codigo do emoji obtido no site e " ; " no final .
* Para adicionar simbolos: <br>
Utiliza-se " & " + nome do simbolo ou " &# " + numero do simbolo disponivel no link <br>
* Para adicionar um FAVICON: <br>
Utilize os link informado se precisar gerar ou criar um icon <br>
na área < head> digite __LINK__ e escolha "link:favicon", no atributo "href" inclua o nome do arquivo .icon .
<hr>

## Tags HTML

* < strong> - Negrito
* < em> - Italico
* < big> - grande
* < small> - pequeno
* < mark> - marca texto
* < del> - texto riscado
* < ins> - sublinhado
* < sup> - sobrescrito
* < sub> - subscrito
* < address> - informar endereço
* < code> - codigo fonte
* < pre> - mantem o texto pre definido, como esta escrito
* < blockquote> - citações entre aspas
* < blockquote cite=" "> citações de links
* < abbr title = "..."> < /abbr> - abreviação
* < bdo dir=".."> < /dbo> ( ltr/rtl) - inverter texto
* < ol> < li> < /li> < /ol> - lista ordenadas ( <ol type = ".. "1, A, a, I, i>) (podendo informar o inicio com start=".."(numerico))
* < ul> < li> < /li> < /ul> - listas não ordenadas( type =".." disc, circle, square)
* < dl> - listas de definição, dentro da tag acompanha: < dl> < dt> .. < /dt> < dd> .. < /dd>
* < dt> - definição de termo
* < dd> - definição de descrição
* < a href="link" target="_blank / _self" rel="external"> - adicionar link externo que abre em nova aba do navegador (_self para atuar na mesma pag)
* < A href="link" target="_black / _self" rel="external / nofollow"> - link de pagina interna. para retornar, o caminho deve conter " ../arquivo" 
* < a href="livro/livro_pdf.pdf" target="_blank" download="livro_pdf" type="application/pdf"> - utilizado para download(type, verificar no link informado)
* < picture> source:media:type (source media="(max-width:1000px)" srcset="arquivo" type="image/png"(extensao da foto) -adicionar o source do tamanho menor pro maior, media="(MAX-width:1000)
* < audio src="arquivo.mp3" controls autoplay> - utilizado para colocar audio <br>
para informar alternativas caso o navegado não aceite mp3: <br>
 < audio controls autoplay loop> <br>
  < source src="../midia/go.mp3" type="audio/mpeg"> (se não funcionar esse, tenta o proximo) <br>
  < source src="../midia/go.ogg" type="audio/ogg"> <br>
  < source src="../midia/go.wav" type="audio/wav"> <br>
 < /audio>
* < video width="400" poster="arquivo(foto para ilustrar antes do plau" controls autoplay loop> - adicionar videos, aparece foto antes do play <br>
 < source src="arquivo.mp4/m4v/ogg" type="video/mp4/ogg/webm"> (um para cada video) <br>
 < /video>

<hr>

## COMANDOS CSS
  
  <hr>
  * ORGANIZANDO O CONTEUDO: GROUPING tags : <br>
  - header : Cabeçalho <br>
  - nav : Navegação, links <br>
  - main: Principal <br>
  - section: Sessões <br>
  - article: Artigo <br>
  - footer: Roda-pé <br>
  
  
  
  
  
* ID personalizado: <br>
  (id: HTML e CSS é : # ) (classe: HTML: class / CSS: . ) <br>
  (pseudo-class é: " : ") (pseudo-elemento é : " :: ") <br>
  (childrem(filho) é : " > ") <br>
  
 identifica o seletor com: id="principal(pode utilizar outro nome)" e no style utiliza o seletor personalizado. <br>
 É possivel colocar mais de uma classe no mesmo seletor, apenas separar com "espaço" o mesmo para ID, ex: id="principal" class="destaque" <br>
 
  <hr>
  
* Pseudo-classes identifica um estado especial de um elemento. <br>
 :hover (quando passa mouse por cima), :visited (quando visita o link), :active (quando clica no elemento), :checked, :empty e :focus <br>
  
 * Pseudo-elemento permite que formate um pedaço especifico do elemento referenciado. <br>
 ::before (aparete algo antes), ::after (aparece alfo depois) , ::first-letter, ::first-line. <br>
 - content: ' ' ; para escrever algo apos o elemento <br>
  <hr>
  
* Trabalhando com DIV: <br>
  É possivel trabalhar manipular DIV com pseudo-classes e pseudo-elementos. dentro da DIV você pode colocar seletores como " < h1> ou < p> <br>
  utilizando pseudo-classe: <br>
  div:hover{ color: black; } (ao passar o mouse em cima ela tera uma ação) <br>
  div:hover > h1 ou p{ display: block; color: blue;  } <br>
  <br>
  Assim manipulamos o que há dentro da div. <br>
  
  <hr>
  
* tipos de caixa : <br>
  box-level: (sempre se inicia em linha nova e ocupa a largura inteira; ) EX: DIV; H1; P; MAIN; HEADER; NAV; ARTICLE; ASIDE; FOOTER; FORM; VIDEO <br>
  inline-level: (sempre inicia na mesma linha e ocupa o tamanho do conteudo do elemento e não quebra linha; ) EX: SPAN; A; CODE; SMALL; STRONG; EM; SUP - SUB; LABEL; BUTTON; INPUT; SELECT;  <br>
  MEDIDAS DAS CAIXAS: <br>
border-width: 3px; <br>
border-style: solid; <br>
border-color: darkslategray; <br>
  <br>
padding-top: 10px; <br>
padding-right: 4px; <br>
padding-bottom: 4px; <br>
padding-left: 10px; <br>
  <br>
margin-top: 10px; <br>
margin-right: 10px; <br>
margin-bottom: 40px; <br>
margin-left: 10px; <br>
  <br>
outline-width: 5px (borda dentro da margin) <br>
outline-style: dashed; <br>
outline-color: black; <br>
  <br>
*  SIMPLIFICANDO: pode informar somente padding , margin, width e seus valores na orde sentido horario: top/ rigth/ bottom/ left <br>
  Se informar apenas DOIS valores ele identifica que é : TOP e BOTTOM / RIGTH e LEFT <br>
  na MARGIN por informar rigth e left com : AUTO para centralizar  <br>
  <br>
  - border-style: dotted (borta pontilhada) ; dashed (borda tracejada); solid (linha continua); groove ( margem 3d); <br>
<hr>
 
* display: none( para não aparecer na tela) ; block (para aparecer na tela)
* background-image: radial-gradient(circle,  #0400F2 70%, #000000); (colorir fundo com diversas cores no formato de circulo) <br>
* background-color: rgb(248, 185, 114); (colorir fundo) <br>
* border-radius: 20px; (bordas arredondadas) <br>
* box-shadow: 5px 5px 15px #eb8b0db7; (sombras da caixa) <br>
* display: inline-block; (alinhando blocos) <br>
* border: 1px solid black; (SHORTDAND: criando bordas) <br>
* heigth: 200px; (altura) <br>
* width: 700px; (tamanho da caixa; largura) <br>
* padding: 10px;  (distancia da caixa do texto; preenchimento) <br>
* margin: auto; (centraliza a caixa e ajuste automatico; da borda para fora; ) <br>
* outline:  ; (traçado por fora da borda)
* text-align: justify; (alinhamento do texto) <br>
* text-decoration: underline; ( texto sublinhado) <br>
* text-shadow:2px 2px 6px #eb8b0db7 ; ( sombra do texto) <br>
* font-style: ; ( estilo de fonte, italico) <br>
* font-weight: ; (peso da fonte, negrito; normal; italico) <br>
* font-size: 20px; (tamanho da fonte, UTILIZAR " em " ou " px " , "1em" = "16px") <br>
* font-family: Arial, Helvetica, sans-serif; (fonte dos textos) <br>
* text-indent: 30px; (espaço do paragrafo) <br>
* color: blue (cor letra) <br>
  

  
* shorthand: oredem: font-style-> font-wight-> font-size-> font-family ( essa ordem deve ser adicionada no FONT) <br>
  EX: font: italic bolder 3em 'work sans', sans-serif ; <br>
  
* Download de font: <br>
 Após download, salve a font no servidos e declare ela da seguinte forma: (URL deve ser no nome do arquivo, identico) <br>
   @font-face { <br>
            font-family:'Centurion' ; <br>
            src: url('The Centurion.otf') format('opentype'), url('The Centurion .ttf') format('truetype'); <br>
            font-weight: normal; <br>
            font-style: normal; <br>
        } <br>
* tipos de format: <br>
-opentype (otf) <br>
-truetype (otf) <br>
-embedded-opentype <br>
-truetype-aat (apple advanced typography) <br> 
-svg <br>


<hr>
 
 ### VARIAVEIS
 
 * : root é uma pseudo-classe que é a raiz do documento, criando variaveis para facilitar, criando variaveis globais: <br>
 :root{ <br>
        --cor01: #c5ebd6; <br>
        --cor02: #83e1ad; <br>
        --cor03: #3ddc84; <br>
        --cor04: #2fa866; <br>
        --cor05: #063d1e; <br>
<br>
        --font-destaque: 'Bebas Neue', cursive; <br>
        --font-padrao: 'Arial', Helvetica, sans-serif; <br>
        --font-android: 'idroid'; <br>
    } <br>

<hr>

### INTERNO 

Seletores demarcam as linhas a serem executadas, dentro do HEAD: 
Aseguir exemplo de declaração, onde informamos a font, o tamanho da font e a cor.  <br>
cada declaração é um conjuto de propriedade e valores: <br>
- Propriedade: font-family, font-size, color <br>
- valores: Arial, 20px, blue <br>
<hr> 
< head> <br>
... <br>
 < style> <br>
        body{ <br>
            background-color: yellowgreen; <br>
            font-family: Arial, Helvetica, sans-serif; <br> 
            font-size: 20px; <br>
            } <br>
        h1{ <br>
            color: blueviolet; <br>
            background-color: chocolate; <br>
        } <br>
        h2{ <br>
            color: brown; <br>
        } <br>
        p{ <br> 
            text-align: justify; <br>
        } <br>
    < /style> <br>
 < /head> <br>
} <br>
<hr>

### EXTERNO

Cria-se um arquivo .CSS com todas as definições de  Style, nos arquivos HTML faz uma ponte referenciando no LINK:CSS 
com o nome do arquivo css. EXEMPLO: <br>
<hr>
nome do arquivo: style.css<br>

@charset "UTF-8"; <br>
 <br>
body{ <br> 
    background-color: yellowgreen; <br>
    font-family: Arial, Helvetica, sans-serif; <br>
    font-size: 20px; <br>
    } <br>
h1{ <br>
    color: blueviolet; <br>
    background-color: chocolate; <br>
} <br>
h2{ <br>
    color: brown; <br>
} <br>
p{ <br>
    text-align: justify; <br>
} <br>


