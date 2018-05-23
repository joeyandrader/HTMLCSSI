# HTMLCSSI
Curso HTML5 e CSS3 I: Suas primeiras páginas da Web / https://cursos.alura.com.br/course/introducao-html-css

<p align="center">
  <img src="https://givingdata.com/wp-content/uploads/2013/07/html-css-js.png">
</p>

<!-- GUI AQUI:

    Estava pensando que cada ">" era um título ou algo do tipo
    Acho que rola você colocar 8.5, 8.6 e 8.7 só dentro do 8.5 explicando direitin

    Isso pode ter acontecido para outras coisas, se vocÊ ver que não faz sentido pode juntar itens.

-->
# Aula 1: Iniciando HTML
## 1.1 Aplicando o DocType na Pag HTML (Define a versão mais recente do HTML)
  ### 1.1.1 O que é DocType e para o que serve?
    Doctype é uma instrução de qual tipo de documento HTML iremos trabalhar na pagina web.

    Doctype serve para definir a versao do HTML, como HTML 4.1 e HTML5
  ### 1.1.2 Como aplicar o doctype?
  Para aplicar basta por...
  ```<!DOCTYPE html>```
  Primeiro de tudo, antes da tag ```<html>```

## 1.2 Atribuindo Tags HTML (Estrutura onde ficara todos os conteudo do site)

Colocamos todo o conteudo do site dentro de algumas tags: 

```html 
<!DOCTYPE html>
<html> 
    <head>
    <meta charset="UTF-8">
    <title>Titulo da pagina</title>
    <link rel="stylesheet" type="text/css" href="estilo.css">
    </head>
    <body>
    </body>
</html>
```
## 1.3 Entendo as diferença entre as 3 TAGS

## HTML

> A tag HTML informa ao navegador que este é um documento HTML

>Representa também a raiz de um documento HTML

> É um receptiente para outros elementos, exceto para o <!DOCTYPE>

```html
 <html>
     Conteudo
 </html>
```

## HEAD

> A tag HEAD reprensenta um contêiner para conteudos introdutorios e conjuntos de links da sua pagina.

>Informando icones para pagina , titulos e autorias.

```html
<html>
    <head>
    <meta name="description" content="Descrição do meta dentro da tag HEAD">
        <meta charset="utf-8">
        <title>Titulo site</title>
    </head>
</html>
```

## BODY

> A tag BODY é o corpo do elemento. onde vai conter todo o seu codigo de uma estrutura html.
> Como texto, hiperlinks, imagens, tabelas, listas etc.

```html
<html>
    <head>
    <meta name="description" content="Descrição do meta dentro da tag HEAD">
        <meta charset="utf-8">
        <title>Titulo site</title>
    </head>
    <body>
      The content of the document......
    </body>
</html>
```

## 1.4 Atribuindo Tag LINK  REL (diz que tipo de conteúdo que queremos referenciar com ela)

> A tag "rel" define um atributo na qual aquela classe ta se referindo

>Neste exemplo, o rel indica que o documento referenciado é uma folha de estilo:

```html
<link rel="stylesheet" href="css/estilo.css">
```


## 1.5 Atribuindo Tag LINK > href (diz onde esse conteúdo se encontra)
  ```html
 TAG LINK

 <link> : define um link entre um documento e um recurso externo. usada para chamar uma folha de estilo externas.
 ```
 > Exemplo da tag Link
 ```html
 <head>
   <link rel="stylesheet" type="text/css" href="estilos.css">
</head>
 ```
> O atributo href especifica o URL da página para onde o link vai. ou a folha de estilo externa

> Neste Exemplo o href mostra onde o arquivo estilo.css está.

```html
<link rel="stylesheet" href="css/estilo.css">
```
>Na pasta CSS onde a folha estilo.css se encontra

## 1.6 Atribuindo Tag META > charset="utf-8" (indicando que nossa página usa a codificação de caracteres UTF-8)
```html
TAG META

<meta> : Fornece dados sobre o documento HTML
geralmente sao usados para especificar as descrições da pagina, as palavras-chaves, o autor do documento
```
> Mais Exemplos de metas:
 ```html
 <head>
  <meta charset="UTF-8">
  <meta name="description" content="Curso Alura HTML">
  <meta name="keywords" content="HTML5,CSS3,JavaScript">
  <meta name="author" content="Joey Andrade">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
 ```
## 1.7 Adicionando title na Aba do Navegador.. dando um titulo ao nosso site
```html
 TAG TITLE

<title> : Define um titulo para seu documento HTML, é necessária em todos os documentos HTML.

define um título na barra de ferramentas do navegador
fornece um título para a página quando ela é adicionada aos favoritos
exibe um título para a página nos resultados do mecanismo de pesquisa

Nota que você NÃO pode ter mais de um elemento <title> em um documento HTML.
```
> Exemplo da tag Title
 ```html
 <head>
  <title>Minha pagina Web</title>
</head>
 ```
## 1.8 Diferenças entre tags "p", "strong" e  "em" , e ultilizando na pagina HTML.

## 1.8.1 TAG "p"
> A tag "p" usada geralmente para criaçoes de paragrafos. como o exemplo abaixo.
```html
    A tag <p>Paragrafo</p>
```
> Podemos atribuir varios paragrafos ao conteudo HTML

## 1.8.2 TAG "strong"
> Ja com a tag "strong" define um texto, conteudo importante. alem de deixar o texto em "NEGRITO" por assim dizer..
```html
    <strong> Conteudo importante da pagina e negrito </strong>
```
## 1.8.3 TAG "em"

>A tag "em" enfatiza um texto da pagina HTML, alem de deixar o texto "ITALICO" por assim dizer..

```html
    <em> Conteudo infatizado e italico </em>
```

## 1.9 Iniciando Blog index.
> Criando documento de Blog e index... Verificar no repositorio do github

# Aula 2: Introdução ao CSS
## 2.1 Criando estilo na pagina HTML bio e blog

>Entendo a criação de estilo inline onde voce pode por um estilo na propria linha html

>Exemplo :
```html
 <h1 style:font-size:16px"> Bom Trabalho </h1>
```
## 2.2 Atribuindo estilo a uma tag especifica:

>Vocè também pode por um estilo para um seletor especifica como o exemplo abaixo:

```html
<style type="text/css">
    h1 {
    	font-size:16px;
    }
</style>
```
>Assim todos os atributos que possuir a tag H1 vai ter o tamanho da fonte de 16px.

## 2.3 Atribuindo Tag "p" com estilo
>Podemos atribuir um elemento inline na tag "p" ou especifica-la na folha de estilo usando.

```html
<style type="text/css">
    p {
    	font-size:16px;
    }
</style>
```
OBS: Tema de um conteudo do alura.

## 2.4 Criando Estilo separado em um novo arquivo!!! css/estilo.css
>Como dito, voce pode criar um novo arquivo .. nomear e por a extensão .css no fim do arquivo.

```
style.css
```

> E por fim chamar esse arquivo dentro do seu documento HTML.

## 2.5 Chamando estilo atravez da tag 

>Semanticamente falando ao usar o link para chamar a sua folha de estilo dará a voce mais organizacão, e nao deixa seu documento HTML sujo e bagunçado com varios codigos css.. assim facilita mais na hora de trabalhar o estilo do seu site... vamos dividir as coisas e deixar mais organizados, por favor ne.. :stuck_out_tongue:

>Para chamar sua folha de estilo basta fazer igual o exemplo abaixo:

```html
<link rel="stylesheet" href="css/estilo.css">
```
## 2.6 Adicionando e alterando fontes a elementos de texto, com fonte principal e fontes secundaria(Caso o usuario nao tiver a primeira fonte)

> Podemos atribuir varios tipos de fontes para o nosso site... a principal e a secundaria..
```html
<style type="text/css">
    h1 {
    	font-family: "Time New Roman" serif;
    }
</style>
```
>Como o exemplo acima, vimos que a fonte "Time New Roman" é a primeira fonte a ser chamada ao vizualizar nosso site, Caso o nosso usuario nao tiver essa fonte, ele entao entrará no...

>Fonte Secundaria. que seria qualquer fonte do tipo serif... ou outra que você definir.

## 2.7 Entendendo as cores em RGB...
<p align="center">
  <img src="https://dicasdeprogramacao.com.br/images/entenda-como-funcionam-os-codigos-de-cores-rgb/cores-rgb.jpg" width="150" heigth="150">
</p>

 >As cores RGB = RED, GREEN e BLUE que no português seria, Vermelho, Verde e Azul.3

 >Apartir dessa combinação é possiveis criar diversas cores para seu conteudo HTML com numeros que varia de 0 a 225.

 >O branco é quando se tem o maior valor para as 3 cores, ou seja, 255 para Red, Green e Blue. E o preto é formado quando se tem o valor 0 para essas 3 cores.

 ```html 
  <style type="text/css">
    body {
         background-color: RGB(255, 255, 255);
    }
</style>
 ```

## 2.8 Cores mais especificas hexadecimal, #FFF, #EE8...

> Além disso a outras formas mais faceis de definir uma cor a sua pagina HTML...
 
 ```html 
  <style type="text/css">
    body {
         background-color: #FFFFFF;
    }
</style>
 ```
 > Uma cor pode ser especificada usando um valor hexadecimal

>Aqui voce encontra varias cores em Hexadecimal:
<a href="https://site112.com/tabela-cores-html" target="_blank">Tabelas de cores em Hexadecimal</a>

> e por fim podemos usar nomes em Inglês da propria cor.
> 
 ```html 
  <style type="text/css">
    body {
         background-color: blue;
    }
</style>
 ```

# Aula 3: Aprofundando no HTML

> Aprofundamos mais no codigo HTML. Abaixo outras formas de ultilizar tags no nosso HTML.

## 3.1 Atribuindo links em textos 

Explicar o que é link absoluto
Explicar o que é link relativo
```html
<a href=""> (links absolutos , links relativos)
```
## 3.2 Adicionando IMG na pagina 
explicar o que é a tag IMG

```html
<img src=""> exemplo de como colcoar
```
## 3.3 Tag alt="" tornando a pagina mais acessivel a deficientes visuais.
Explicar pq isso deixa a página mais acessível
Explicar o que acontece quando colocamos o alt

```html
    <h1> Colocar um exemplo de alt em uma imagem </h1>
```
## 3.4 Atribuindos citaçoes com tags ```<blockquote>``` e tag ```<cite>```
Explicar o que é o **blockquote**
Explicar para o que serve **blockquote**
Explicar o que é o **cite**
Explicar para o que serve **cite**

## 3.5 HTML e Semântica ```<main>```: conteúdo principal da página
Explicar o que é a semântica
Explicar o que é a semântica main 
Explicar pq é bom fazer isso

## 3.6 outras tags importantantes com semântica
- ```<header>```: cabeçalho da página ou de uma região dela
- ```<header>```: 
- ```<footer>```: mesma ideia da tag <header> para o rodapé
- ```<aside>```: conteúdo auxiliar ao conteúdo principal, como links relacionados ao conteúdo
- ```<article>```: conteúdo que, por si só, já tem um sentido completo, como um post de um blog ou uma notícia
- ```<section>```: parte/seção de uma página ou texto

```html 
    exemplo usando todas as coisas acima (header, footer, aside, article, section)
```


## 3.7 Listas com tag ```<ul>``` e ```<li>```
O que é uma lista
O que é a **ul** e a **li** (diferencça entre elas)
```html
    Exemplo de uma lista de compras
```
## 3.8 Criando entidades no HTML
O que é uma entidade no HTML
```html
Exemplo do $copy
```

## 3.9 Seletores de descendência
O que são seletores de descendência
Explicar exemplo da "nav a, main h1"
Mostrar exemplo com código


# Aula 4: O navegador trabalhando ao nosso favor

## 4.1 Abrindo inspetor de paginas no google crhome
Explicar como fazer isso (pode ser por texto mesmo)
Mostrar o comando no chrome para fazer isso (```ctrl+...```)

## 4.2 Atribuindo e editando propriedades do HTML e CSS

Explicar que da para mudar  o html e css da página local
Explicar como fazer isso

## 4.1 Resolvendo ou procurando erros de digitação onde o inspetor mostra em casos dificeis.

Explicar o que é o inspetor
Explicar como fazer isso


## 4.1 Usando o inspetor a nosso favor para melhor criação de uma pagina HTML, CSS

Explicar como fazer isso e as vantagens de usar o inspetor


## 4.1 Alterando a página pelo próprio navegador

Explicar como fazer isso

## 4.1 Atribuindo estilo pelo proprio elemento do inspetor, ou alterando tags

Explicar como fazer isso

# Aula 5: Aprimorando o Layout

## 5.1 Aplicando Espaçamento entre elementos ultilizando Padding , margin
 - ```Margin```: controla o espaço entre elementos de blocos.
 - ```Padding```: controla o espaço entre o conteúdo de um elemento e sua borda.

Exemplo com código
Colocar uma imagem explicando isso

## 5.2 Propriedades Width , Height que controla apenas o tamanho de um elemento

Explicar o que é width 
Explicar o que é Height
Exemplo com código
```css
    .minhaDiv {
        height: "4324"
    }
```
## 5.1 Propriedades Box-Sizing controla apenas como a largura e a altura de um elemento deve ser calculada.

Explicar o que é box-sizing
Colocar uma imagem que explica
Colocar exemplo com código

## 5.1 Propriedades Line-height controla apenas a altura entre as linhas de texto da página

Explicar o que é Line-sizing
Colocar uma imagem que explica
Colocar exemplo com código

## 5.1 Atribuindo Bordas nos elementos, Tipos de bordas e espaçamentos e cores

Explicar o que é essas bordas
Colocar exemplo com código
Colocar uma imagem de como fica

# Aula 6: Construindo uma base sólida

## 6.1 Aplicando estilo de Reset.css na pagina , resetando estilos padroes de navegadores.

Explicar que temos um estilo padrão do css no navegador
Pq temos que resetar? Importância disso
Como fazer (para fazer isto basta criar um ....)
Exemplo de código

## 6.2 Entendendo e atribuindo ordem de estilo, e o que pode afetar.

Pq a ordem importa
Mostrar um exemplo de dando merda

## 6.1 Entendo sobre conflitos no css.

O que é conflito no css
Como eles ocorrem
Como evitar

# Aula 7: Um pouquinho de posicionamento

## 7.1 Atribuindo Posicionamento em propriedades da pagina

Explicar um pouco melhor o que ele disse aqui

## 7.2 atribuindo css display
O que é o display
Exemplo

## 7.3 Display : inline, block , inline-block, none.
Qual a diferença entre inline, block, inline-block, none

Exemplo com código

# Aula 8: Mais seletores

## 8.1 Atribuindo novas funcionalidades ao css...

Quais novas funcionalidades?
Explicar cada uma delas
Colocar código

## 8.2 aplicando novas regras como CLASS e ID's

## 8.3 Verificando as diferenças entre os atributos class e id's

Qual a diferença entre ID e CLASS?
Pq usamos cada uma ?
Exemplo de código css

## 8.4 testando e aplicando na pagina html
<!-- GUI AQUI:

    Estava pensando que cada ">" era um título ou algo do tipo
    Acho que rola você colocar 8.5, 8.6 e 8.7 só dentro do 8.5 explicando direitin

    Isso pode ter acontecido para outras coisas, se vocÊ ver que não faz sentido pode juntar itens.

-->
## 8.5 Conflito entre classes e id.
Explicar um pouco mais sobre o conflito

```css
div {
    background-color: red;
}
div {
    background-color: blue;
}
```

## 8.6 Temos um conflito, porém Todos os elementos <div> terão fundo azul.
## 8.7 Assim ultilizando o critério de desempate é qual das classes aparece por último no arquivo CSS




# Aula 9: Nem tudo é o que parece

## 9.1 Atribuindo transformaçoes de texto em ultilizando text-transform uppercase e lowercase
Explicar cada um deles
Colocar código

## 9.2 Adicionando Image replacement: Dentro da folha de estilo:
O que é isso
exemplo 
```css
.github {
    background-image: url(github.png);
}
```
## 9.3 Display Blocks nos links

Pq colocou o displayu block ?
Explicar direitin e dar exemplo de código

## 9.4 Image replacement e ferramentas de buscas...
Explicar melhor o que é essas tretas

## 9.5 Aplicando e entendendo text-indent -9999 ou font-size 0px; ambos remove o texto..
Eplicar melhor aqui cada um deles individualmente
Exemplo de código


# Aula 10: Posicionamento mais a fundo

## 10.1 Tipos de conteudos flutuantes
O que são conteudos flutuantes
Exemplo de código

## 10.2 Float right e left "Posicionando elementos a direita e esquerda"
Explicar melhor float right e left
Colcoar imagem de como fica
Colocar código exemplo

## 10.3 Ultilizando box sizing- border box

O que são essas coisas
Exemplo com imagem
colocar código exemplo 

## 10.4 Propriedades  Clear . Left , right , both "Elimina espaço na esquerda, direita . ou em ambos"

Colocar explicação
Colocar o pq usamos isso (quando que é útil)
Exemplo do código
exemplo imagem


# Aula 11: Elementos onde queremos

## 11.1 Propriedades Position. ("Relative , absolute e fixed")

Explicar cada uma delas
Mostrar imagem
Exemplo de código

## 11.1 Relative , Realtivo a posição original do elemento
Explicar melhor aqui
mostrar imagem
Exemplo de código

## 11.1 Absolute , com ele podemos colocar um elemento onde quisermos na página

Explicar melhor o absolute
Mostrar códigoi
MOstrar imagme

## 11.1 Fixed , Fixamos um elemento independentemente da posição da rolagem da página no navegador.

Explicar melhor
Mostrar código
Mostrar imagem

## 11.1 Todas propriedades usam elementos como top , left , right , bottom.

Explicar melhor
Explicar o que é cada um (top = cima, left...)

# Aula 12: Desafios Finais

## 12.1 Testando conhecimento aprendindo durante todo o curso
##12.2 Criando a pagina "Portifolio"
