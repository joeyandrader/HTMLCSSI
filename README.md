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
## 1. Aplicando o DocType na Pag HTML (Define a versão mais recente do HTML)
  ### 1.1 O que é DocType e para o que serve?
    Doctype é uma instrução de qual tipo de documento HTML iremos trabalhar na pagina web.

    Doctype serve para definir a versao do HTML, como HTML 4.1 e HTML5
  ### 1.2 Como aplicar o doctype?
  Para aplicar basta por...
  ```<!DOCTYPE html>```
  Primeiro de tudo, antes da tag ```<html>```

## 2. Atribuindo Tags HTML (Estrutura onde ficara todos os conteudo do site)

Colocamos todo o conteudo do site dentro de algumas tags: 

```html 
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
## 3. Entendo as diferença entre as 3 TAGS

tag

## 4. Atribuindo Tag LINK  REL (diz que tipo de conteúdo que queremos referenciar com ela)

explicar o que é o link rel como ela funciona (o que é **rel** e o que é **href**)

```html
<link rel="dlinksdd" href="fdssdfsdf">
```


## 5. Atribuindo Tag LINK > href (diz onde esse conteúdo se encontra)
## 6. Atribuindo Tag META > charset="utf-8" (indicando que nossa página usa a codificação de caracteres UTF-8)
Explicar aqui o que é META

```html
<head>
    <meta> Colocar aqui Exemplo de meta
</head>
```
## 7. Adicionando title na Aba do Navegador.. dando um titulo ao nosso site
Explicar aqui onde que costumamos colocar
```Exemplo de como fazer```
## 8. Tags HTML (Informa ao Navegador de qual lingaguem se trata, sendo assim HTML)

Explicar aqui para que isso serve...
Mosrtrar um exemplo de como fazer isso

## 9. Tags HEAD (serve para agrupar informações para o navegador entender melhor nosso site)

Explicar o que você quis dizer em agrupar
```html
<html DOC..>
    <head>
        <meta> Exemplo dos paranue que o navegador usa para entender melhor o nosso site
    </head>
</html>
```

## 10. Tags BODY (serve para agrupar as informações que queremos mostrar para os usuários)

Explicar o que você quis dizer com agrupar as informações?
Falar
 que o body é geralmente onde colocamos tudo
## 11. Diferenças entre tags ```<p>``` = Paragrafos,  ```<strong>``` = Formatação em Negrito, ```<em>``` = Italico,  e atribuindo a pag html

O título já extá bem explicadinho (talvez passar para "11. Algumas tags" e aqui colocar a explicação de cada)
```html
    <h1> Explicação dessas tretas </h1>
```
## 12. Iniciando Blog index.

# Aula 2: Introdução ao CSS
## 2.1 Criando estilo na pagina HTML bio e blog
Entendo a criação de estilo inline, Exemplo: 
```html
 <h1 style:font-size:16px"> Bom Trabalho </h1>
```
## 2.2 Atribuindo estilo a uma tag especifica Exemplo:
```html
<style type="text/css">
    h1 {
    	font-size:16px;
    }
</style>
```
## 2.3 Atribuindo Tag <p> com estilo
## 2.4 Criando Estilo separado em um novo arquivo!!! css/estilo.css
## 2.5 Chamando estilo atravez da tag 
Explicar pq é melhor colocar o css em um arquivo diferente
```html
<link rel="stylesheet" href="css/site.css">
```
## 2.6 Adicionando e alterando fontes a elementos de texto, com fonte principal e fontes secundaria(Caso o usuario nao tiver a primeira fonte)

```html
<style type="text/css">
    h1 {
    	font-family: "Time New Roman" serif;
    }
</style>
```
## 2.7 Entendendo as cores RGB(255,255,255) Vermelho, Verde, Azul,...
Explicar aqui que toda cor pode ser criada a partir a combinação destas 3 cores
Explicar aqui a ordem dentro do RGB (**R**ed, **G**reen, **B**lue)
## 2.8 Cores mais especificas hexadecimal, #FFF, #EE8...

O que são essas cores
Quanto maior a cor mais clara ou mais esscura ?
Explicar o que é hexadecimal (decimal vai de zero a 10 hexadecimal vai de 0 a F (ou seja, 16: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F))
Quanto mais próximo do zero mais escuro, quando mais próximo F mais claro (ou seja, #FFF é branco e #000 é preto)

Segue a ordem do RGB (ou seja, se você colocar #F00 daria a cor vemelha)
Explicar que cores seriam #0F0 e #00F

# Aula 3: Aprofundando no HTML


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
