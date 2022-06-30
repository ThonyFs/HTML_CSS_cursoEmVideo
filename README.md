# HTML_CSS_cursoEmVideo
curso HTML5 &amp; CSS3 do canal Curso em Vídeo.   

* https://www.w3schools.com/charsets/ref_utf_symbols.asp (link para pag de simbolos) 
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
* < video width="400" poster="arquivo" controls autoplay loop> - adicionar videos <br>
 < source src="arquivo.mp4/m4v/ogg" type="video/mp4/ogg/webm"> (um para cada video) <br>
 < /video>

<hr>

## COMANDOS CSS
font-size: 20px; (tamanho da fonte) <br>
background-image: radial-gradient(circle,  #0400F2, #000000); (colorir fundo com diversas cores no formato de circulo) <br>
background-color: rgb(248, 185, 114); (colorir fundo) <br>
border-radius: 20px; (bordas arredondadas) <br>
box-shadow: 5px 5px 15px #eb8b0db7; (sombras da caixa) <br>
width: 700px; (tamanho da caixa) <br>
padding: 10px;  (distancia da caixa do texto) <br>
margin: auto; (centraliza a caixa e ajuste automatico) <br>
text-align: justify; (alinhamento do texto) <br>
text-shadow:2px 2px 6px #eb8b0db7 ; ( sombra do texto) <br>
font-family: Arial, Helvetica, sans-serif; (fonte dos textos) <br>
color: blue (cor letra) <br>



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


