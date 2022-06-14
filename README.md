# HTML_CSS_cursoEmVideo
curso HTML5 &amp; CSS3 do canal Curso em Vídeo.   

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
* < !DOCTYPE hmtl>
* < html lang="pt-br">
*    < head> (essa é a area de configuracao)
*        < meta charset="UTF-8">
*        < meta name="viewport"
*        content="width=device-width, initial-scale=1.0">
*        < title>
*            titulo da pagina
*        < /title>
*    < /head>
*    < body>
*    (aqui fica o corpo do site)
*        < h1>Olá, Mundo! < /h1>
*    < /body>
*< /html>


## COMANDOS HTML
Aberturas de tag ( demonstrada em " < > " ) na maioria das vez a tag deve ser fechada ( < / >)

* Exemplos de titulos: < h1 > exemplo de título < /h1 > 
* Exemplo de paragrafo: < p > exemplo de paragrafo < /p >
* Exemplo de imagem: < img src="foto.png" alt="exemplo de foto" >
dentro da tag onde não tem fechamento, essa tag de imagem possui PARAMETROS ( SRC , ALT) seus valores estão entre aspas ( " " ).
- SRC = origem da foto ( seu titulo)
- ALT = texto alternativo

## COMANDOS CSS

Seletores demarcam as linhas a serem executadas.
Aseguir exemplo de declaração, onde informamos a font, o tamanho da font e a cor: 

* h1{
    font-family: Arial; (declaração)
    font-size: 20pt;
    color: blue;
} 
cada declaração é um conjuto de propriedade e valores
- Propriedade: font-family, font-size, color 
- valores: Arial, 20pt, blue