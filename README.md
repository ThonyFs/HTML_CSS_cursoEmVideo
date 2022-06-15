# HTML_CSS_cursoEmVideo
curso HTML5 &amp; CSS3 do canal Curso em Vídeo.   

* https://www.w3schools.com/charsets/ref_utf_symbols.asp (link para pag de simplos) 
* https://emojipedia.org/ (link para pag de emoji)
* https://unsplash.com/ ( biblioteca de imagens com licenças)
* www.pexels.com (biblioteca de imagens com licenças)

## ESTRUTURA BASICA HTML
* primeira linha, informar: < !DOCTYPE html>
* tag< html lang="pt-br"> informa que o site será em portugues < /html>
* tag< head> < /head>  
* tag< body> < /body>
* tag< meta charset="UTF-8"> informa que o site e compativel com caracteres UTF-8
* tag< meta name="viewport"
        content="width=device-width, initial-scale=1.0"> 
informa que o site sera reproduzido em scala de 100% da tela
* tag< title> < /title> titulo da pagina

# Exemplo da estrutura basica:
<!DOCTYPE hmtl> <br> 
< html lang="pt-br"> <br>
..  < head> (essa é a area de configuracao) <br>
..  < meta charset="UTF-8"> <br>
..  < meta name="viewport" <br>
..   content="width=device-width, initial-scale=1.0"> <br>
..  < title> titulo da pagina < /title > <br>
..  < /head> <br>
..  < body> (aqui fica o corpo do site) <br>
..  < h1>Olá, Mundo! < /h1> <br>
..  < /body> <br>
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
* &lt ; &gt ; para implementar os sinais < > na execução. <br>
* Para adicionar emoji: <br>
        Vamos adicionar alguns emoji: <br>
        &#x1F47D; &#x1F596; <br>
        para declarar o emoji utilizamos, "&#x" seguido do codigo do emoji obtido no site e " ; " no final .
        
## COMANDOS CSS

Seletores demarcam as linhas a serem executadas.
Aseguir exemplo de declaração, onde informamos a font, o tamanho da font e a cor: 

* h1{ <br>
    font-family: Arial; (declaração) <br>
    font-size: 20pt; <br>
    color: blue; <br>
} 
cada declaração é um conjuto de propriedade e valores
- Propriedade: font-family, font-size, color 
- valores: Arial, 20pt, blue
