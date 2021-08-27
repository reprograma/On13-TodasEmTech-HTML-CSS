# On13-HTML-CSS

Online-13 | Front-end | 2021 | Fundamentos de HTML e CSS

>Aula dia 28 de Agosto, sobre HTML e CSS Básico

<img src="https://user-images.githubusercontent.com/77210732/130670724-60f812c2-72ed-47ed-a4f4-e66eebd6e926.gif">


## AULA 28 AGOSTO, SÁBADO, 9H - 17H

---
---

### **CONTEÚDO AULA MANHÃ 9h - 12h**

- [x] **Preparando estrutura de desenvolvimento juntas**
  - [x] Criando pastas e arquivos
- [x] **Introdução e revisão - HTML**
  - [x] O que é linguagem de marcação de hipertexto? `<!DOCTYPE html>`
  - [x] Elementos `<head>` e `<body>`
- [x] **Intervalo** - 15min
  - [x] Elementos HTML: tags (etiquetas) e atributos
  - [x] Tags semânticas, como e porque usá-las! (:
    - [x] `<header>` `<nav>` `<footer>` `<main>` `<section>` `<article>` `<ul>` `<ol>` `<li>` `<aside>` `<button>` `<h1>` `<h2>` `<h3>` ...
  - [x] `<a>` - links em âncora, e seu atributo `href`
- [x] **Introdução CSS**
  - [x] CSS - Folha de estilo em cascata
    - [x] Diferentes formas de adicionar estilo à página
      - [x] A tag e atributo `<style>`
      - [x] Importar arquivo style.css através da tag `<link>`
      - [x] Importando fontes externas (ex.: Google Fonts) - um outro uso da tag `<link>`
  - [x] Estilizando o CSS juntas - propriedades básicas `color` `bg-color` `font-size` `font-family`
  - [x] Seletores CSS - `.class` `#id` `elemento` `atributo`
  - [x] Especificidade com seletores, propriedades CSS e efeito cascata
  - [x] Pseudo-seletores, ex: - `:hover`

---
### **CONTEÚDO AULA TARDE 13h - 17h**

- [x] **Dúvidas da manhã**
- [x] **Box-sizings (tamanho das caixas) e displays**
  - [x] Blocos `<div>` e elementos em linha `<span>`, `<img>`
  - [x] Displays block, inline, inline-block
  - [x] Mexendo em bordas, margens, preenchimentos e conteúdo  
         - [x] `border` `margin` `padding` `width` `height`  
         - [x] border-box vs content-box
- [x] **Reset básico - mexendo nos estilos padrão de página**
- [x] **Display flex - o famoso Flexbox**
  - [x] Mães `<div>`as e filhas `<div>`inhas. Display na mãe, mexe as filhas.
  - [x] Algumas propiedades e seus valores: `justify-content` `align-items` `align-content` `flex-direction` 
- [x] **Intervalo** - 15min
- [x] **Codando juntas**
- [x] **Retirar dúvidas, deixar o exercício para concluir até sexta e falar sobre materiais e jogos disponíveis :)**

---
### **AULA 24 MARÇO, QUARTA, 20h-22h**

- [x] **Meu primeiro formulário**
  - [x] Elementos `<form>` `<input>` `<label>` `<textarea>` `<select>` `<option>` `<button>`
  - [x] atributos `type` `for` `name` `placeholder`
- [x] **Tirar dúvidas da semana**


---
---
## Link do Dontpad da Aula


[link para o arquivo dontpad](http://dontpad.com/On13-html-css);

### **Instruções para baixar o repositório**


**1.** Entrar no repositório e fazer o fork do repositório On13-TodasEmTech-HTML-CSS

   Link: [Repositório](https://github.com/reprograma/On13-TodasEmTech-HTML-CSS.git)

**2.** Clicar no botão CODE e copiar o link.


<img src="https://i.ibb.co/1J2MF22/git-fork.png" width="400" height="250" >

     
**3.** Abra o GitBash no seu desktop.
   
**4.** Siga os comando e seja feliz :)

   **4.1**  Digite o comando:
 ``` 
        pwd
 ```

   **4.2**  Caminhe até o desktop:
 ```
        cd desktop
 ```

   **4.3** Clone o repositório remoto na sua máquina:
 ```
       git clone link-do-repositorio 
 ```

   **4.4** Entre na pasta clonada:
 ```
       cd On13-TodasEmTech-HTML-CSS
 ```

   **4.5** Crie uma branch com o seu nome:
 ```
       git checkout -b seu-nome
 ```

   **4.6** Digite o comando para abrir o projeto no vscode:
 ```
       code . 
 ```

### **Estrutura básica**

```
 📁 Nome-da-pasta
   |
   |-  📁 index.html
   |
   |-  📁 css
   |    |- 📁 style.css
   |
   |-  📄 imagens
   |    |- 📁 imagens.png
```
>Ou seja, uma pasta com um arquivo index.html **na raiz** e duas pastas: 
>uma css para inserção de nossos estilos "style.css e outra img, para inserção de nossas imagens.


### **Editores de texto**

Para se modificar um arquivo .html e .css, precisamos de editor de texto. Apesar de que um simples bloco de notas pode ser a ferramenta para criação desses arquivos, vários softwares foram lançados no mercado para gostos dos programadores, oferecendo facilidades e plugins para facilitar o desenvolvimento. Alguns famosos e notáveis são:

- [Sublime Text](https://www.sublimetext.com/);
- [Notepad++](https://notepad-plus-plus.org/);
- [Atom](https://atom.io/);
- O que vamos usar durante as aulas é o [Visual Studio Code](https://code.visualstudio.com/);

---

<img src="https://media.giphy.com/media/fuJPZBIIqzbt1kAYVc/giphy.gif" height="250">

_html é a estrutura_
_css é o estilo por cima_

## HTML

---

HTML é uma abreviação de **Hyper Text Markup Language** (linguagem de marcação em hipertexto). Ou seja, não se trata de uma linguagem de programação, pois não tem lógica (algoritmos, processos etc). Ele cria a **estrutura** de uma página ou aplicação web, determinando a separação de layout e seu conteúdo.

*Documentos .html possuem tags de estruturação básica:*

```html
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```

*Internamente, as tags html possuem uma anatomia básica também:*

```html
<nome-da-tag atributo="valor do atributo">
  conteúdo
</nome-da-tag>
```

*Tags autocontidas*

A tag img é um bom exemplo, porque ela não possui um conteúdo interno, ela é o próprio conteúdo. Ela recebe atributos específicos para determinar o caminho da imagem e a descrição dela.

```html
<nome-da-tag atributo="valor do atributo">
```
*Comentários em HTML:*

```html
<!-- Isso é um comentário. Comentários em qualquer linguagem são pedaços de código que são ignorados na renderização (na leitura do computador), mas são úteis para entendimento humano -->
```
#### *HTML Semântico*

Semântica é um estudo a respeito do significado/sentido de palavras, frases ou expressões dentro de um contexto.
No programação ela está relacionada ao significado de uma parte do código. EX: Qual a finalidade/função que esse elemento tem no HTML?
O HTML semantico torna as informações de do site bem explicadas para o computador, facilitando o entendimento de leitores de acessibilidade, e ajudando que mecanismos de pesquisa captarem palavras-chave importantes para influenciar as pesquisas da página.

<div>
   <img src="https://user-images.githubusercontent.com/77210732/130863949-3d8ffd2e-be8c-44dc-a80e-9b6f957e1e12.png"  height="300">
</div>
Fonte: medium.com/@eduagni/html5-entendendo-a-estrutura-e-a-sem%C3%A2ntica-db5f17808c7

|**TAGS HTML**|                                                                                                         |
|-------------|---------------------------------------------------------------------------------------------------------|
|html, head, body|Tags de estrutura                                                                           |
|link         |Utilizada para definir a relação entre o documento e algum recurso externo **(head)**                    |
|meta         |Utilizada para inserir metadados (informaçõe) a respeito de um documento HTML **(head)**                 |
|title        |Define o título do documento **(head)**                                                                  |
|main         |Representa o conteúdo de maior relevância dentro de uma página **(body)**                                |
|header       |Utilizada para representar o cabeçalho do documento **(body)**                                           |
|nav          |Utilizada para definir um conjunto de links de navegação **(body)**                                      |
|section      |Utilizada para criar seções dentro de um documento e geralmente contém um título **(body)**              |
|article      |Utilizada para fazer um artigo dentro de um conteúdo, geralmente se utiliza um título e são idependentes **(body)** |
|div          |tag de divisão **(body)**                                                                                |
|footer       |Utilizada para especificar o rodapé do conteúdo de um documento ou seção **(body)**                      |
|a            |Utilizada para inserir links  **(body)**                                                                 |
|H1 a h6, p   |Tags para definir textos. H1 a h6: Tags para títulos. p: Tag utilizada para inserir parágrafos **(body)**|
|img          |Utilizada para inserir imagem **(body)**                                                                 |
|aside        |Seções muitas vezes representadas como barras laterais, relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo|

[Clique para ver mais tags HTML](https://www.w3schools.com/tags/tag_comment.asp)

> **ATENÇÃO!**
> Não esqueçam de **indentar** o código! Isso ajuda na sua legibilidade, manutenção e colaboração com outros desenvolvedores.
> Para indentar, selecione a linha do código e aperte _tab_.

## CSS

---

CSS é abreviação de **Cascading Style Sheet** (folha de estilos em cascata). É a linguagem que define **estilos** para o HTML, portanto, não se trata de linguagem de programação. CSS tem "cascata" no nome, devido a sua forma de determinar a propriedade de um elemento - levando em consideração _hierarquia de seletores_ e de chamadas de estilo (inline, internal e external).

Há três formas para incluir o código CSS em um documento HTML:

**Inline**

```
<p style="color: blue">Parágrafo com fonte azul.</p>
<p>Esse outro parágrafo não é azul, a não ser que
exista <span style="color: red">CSS em outro lugar</span>.</p>
```

**Interno**

```
<head>
  <style type="text/css">
    seletor { propriedade: valor; }
  </style>
</head>
```

**Externo**

```
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="css/style.css" />
  </head>
</html>
```

Dentro do arquivo .css, a anatomia é:

```css
seletor {
  propriedade: valor;
}
```

Exemplo:

```css
p {
  color: red;
}
```

Comentários em CSS:

```css
/* Sou um comentário CSS */
```

#### Classes e id

Classes e ids são atributos que podem ser inseridos em qualquer tag dentro da tag **body**. Eles são **atributos de nomeação**, sendo class muito usada para referência em CSS e id para Javascript (apesar de que há outras boas práticas no mercado atualmente).
Uma diferença entre os dois é que podem haver várias classes com o mesmo valor, ao passo que ids devem ser **únicos**.

### *Método BEM*

<div >
   <img src="https://user-images.githubusercontent.com/77210732/130550473-b7a856e8-c92c-4e92-95a3-56d2dc7a0f44.JPG"  width="350" >
</div>

A sigla BEM significa block, element, modifier, que são os três pilares do método BEM. É uma metodologia de criação de nomes para classes, tornando esse processo mais prático, lógico, e rápido. Ela divide e pensa na arquitetura da interface em em blocos, elementos e modificadores.

### Esquema de nomenclatura

```
 bloco__elemento_monificado-nome_modificador-valor
```

* Nomes em letras latinas minúsculas.

* Palavras são separadas por um hífen ( -).

* O  elemento é separado do nome do bloco por um sublinhado duplo ( __).

* O  modificador é separado do nome do bloco ou elemento por um único sublinhado ( _).

* O valor do modificador é separado do nome do modificador por um único sublinhado ( _).

### *Os três pilares*


* **Bloco**: Não deve haver dois ou mais bloco com o mesmo nome, eles são independentes, pode conter outros blocos ou elementos.

<div>
   <img src="https://user-images.githubusercontent.com/77210732/130550794-7633a22c-4d2f-445e-a791-1423f5fdb0d8.JPG"  height="300">
</div>

Fonte: en.bem.info/methodology

<div>
   <img src="https://user-images.githubusercontent.com/77210732/130551006-f5a2b675-7e13-4901-ad3b-74895ee8c756.JPG"  height="300">
</div>

Fonte: en.bem.info/methodology
* **Elemento**: Está diretamente ligado a um bloco, não pode ser utilizado sem um bloco, depende de outras estruturas no código para existir.


<div>
   <img src="https://user-images.githubusercontent.com/77210732/130551063-7b33bced-600b-4589-85e7-47f0d5e9eb01.JPG"  width="500">
</div>

Fonte: en.bem.info/methodology

```
<form class= "search-form">  
    <input class="search-form__input">
  
    <button class="search-form__button">Pesquisar</button> 
</form>
```
  
* **Modificador**: é opcional, pode estar atrelado tanto a um bloco como a um elemento. Ele é usado para mudar a aparência, o comportamento ou o estado.
```
<div class="card">
  <p class="card__paragrafo">Este é um parágrafo</p>
  <p class="card__paragrafo card__paragrafo_vermelho">Este é um parágrafo vermelho</p>
</div>
```



### Nomenclaturas alternativas


* Tracinhos (--)
```
nome-do-bloco__nome-do-elemento--modificador
```
* Estilo CamelCase (inicia com a letra minúscula)
```
blockName-elemName_modName_modVal
```
* Estilo React (inicia com a letra maíuscula)
```
BlockName-ElemName_modName_modVal
```
* Seu sistema de nomenclatura

Você pode montar um próprio sistema de nomenclatura, desde que separe a interface em blocos, elementos, modificadores. Ou seja, seguindo a arquitetura do Método BEM.

|**Propriedades CSS**        |                                                                                  |
|----------------------------|----------------------------------------------------------------------------------|
|Propriedades de background: | background-imagem, background-color                                              |
|Propriedades de texto:      | text-align, font-family, font-size, text-decoration, font-size, text-transform   |
|Propriedades de layout:     | width, margin, padding, display (inline-block, flex, block)                      |
|Propriedade de cor:         |color                                                                             |
|Propriedade de decoração:   | box-shadow, border                                                               |

---

<img src="https://media.giphy.com/media/13FrpeVH09Zrb2/giphy.gif" height="300">

## _É comum e normal errar muitas vez o CSS, aprendê-lo é um joguinho de paciência_
## Criando um formulário

Um formulário no HTML é representado pela tag *form*:

```
<form>Esta é uma tag de formulário</form>
```

Esta tag pode receber alguns atributos específicos como o atributo **method**, que vai definir o método HTTP com que o formulário HTML irá lidar, que pode ser o método Get ou Post. Recebe tbm o atributo **action** que através de uma URL, vai definir o local para onde serão enviados os dados recolhidos nos formulários.
```
<form method="post" action="/receber_dados.php">
...
</form>
```


|**Algumas tags utilizadas dentro dos formulários**|                                                                    |
|----------------------------|------------------------------------------------------------------------------------------|
|input                       | Campo de entrada onde o usuário pode inserir dados                                       |
|label                       | Tag de rótulo/legenda para um campo do form                                              |
|textarea                    | Campo de entrada para texto de várias linhas                                             |
|fieldset                    | Difine um grupo de campos                                                                |
|legend                      | Título para um comjunto de campos                                                        |
|select                      | Define uma lista de opções selecionáveis                                                 |
|option                      | Define cada opção dentro do select                                                       |

### Exemplo de um formulário


<div>
   <img src="https://user-images.githubusercontent.com/77210732/130660579-6aa98045-fc21-4186-809b-09eaeeb3c8b9.png"  width="700">
</div>
<div>
   <img src="https://user-images.githubusercontent.com/77210732/130661691-72032d9b-81e8-405b-ae17-a550be4ab6dc.png"  width="500">
</div>




---
---

---

### Links úteis para estudo :)

- [Documentação HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML);
- [Documentação CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS);
- [Guia HTML para iniciantes](https://tableless.github.io/iniciantes/manual/html/);
- [Guia CSS para iniciantes](https://tableless.github.io/iniciantes/manual/css/);
- [Sobre HTML semântico](https://blog.geekhunter.com.br/voce-conhece-html-semantico/);
- [Tutorial sobre formulários HTML](https://www.homehost.com.br/blog/tutoriais/formulario-html/);
- [Sobre seletores CSS e pseudo-classes](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Getting_Started/Seletores);
- [Sobre a propriedade box-sizing](http://sergiolopes.org/css-box-sizing-border-box/);
- [Conceitos básicos de flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Conceitos_Basicos_do_Flexbox);
- [Ótimo site guia para estudos - desenvolvido por aluna da reprograma](https://calma-senhora.netlify.app/);
- [RGB, RGBA, Hexadecimal](https://serprogramador.com.br/artigos/topico/css/Como-entender-os-padroes-de-cores-RGB-RGBA-Hexadecimal);
- **Dicas de links sobre Display**
``` 
(https://developer.mozilla.org/pt-BR/docs/Web/CSS/display)
(https://www.maujor.com/tutorial/propriedade-css-display.php)
(https://www.w3schools.com/cssref/pr_class_display.asp)
(https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-block-98480c987950)
(https://medium.com/collabcode/pare-de-chutar-e-aprenda-como-funciona-o-display-inline-4ccb7b77371d#.jww2dont9)
(https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
``` 
  
**Dicas extra**
- [Sobre Lorem Ipsum](https://pt.lipsum.com/);
- [Nomes de cores Html-CSS](https://htmlcolorcodes.com/color-names/);
- [Extensão conta-gotas, visualiza cores utilizadas pelo site no inspetor de código](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=pt);
- [Extensão para visualizar fontes usadas pelo site](https://chrome.google.com/webstore/detail/fonts-ninja/eljapbgkmlngdpckoiiibecpemleclhh);



**Sites úteis para buscar por imagens e layout**

- [Google Fonts](https://fonts.google.com/);
- [Flat UI Colors - paleta de cores](https://flatuicolors.com/);
- [Coolors - paleta de cores](https://coolors.co/);
- [FlatIcon - download de icones](https://www.flaticon.com/);
- [FontAwesome - download de icones dentre outros](https://fontawesome.com/icons?d=gallery);
- [Unsplash - site para download imagens](https://unsplash.com/);
- [Imagens de Fundo - site para download imagens](https://imagens-de-fundo.blogspot.com/);
- [FreePik - Site para download de imagens](https://br.freepik.com/);
- [Nappy - site com imagens de pessoas negras e marrons](https://www.nappy.co/);
- [Canva - banco de imagens - possível modificar e personalizá-las](https://www.canva.com/);
- [Pixabay - banco de imagens](https://pixabay.com/);
- [Negativespace - banco de imagens](https://negativespace.co/);
- [Pexels - banco de imagens](https://www.pexels.com/pt-br/);

**Vídeos pra quem gosta de vídeos - estudos**

- [Background simples mas pode ser que não](https://www.youtube.com/watch?v=kU8oIbe5hLs&list=PLirko8T4cEmx5eBb1-9j6T6Gl4aBtZ_5x&index=9);
- [Flexbox in 15 Minutes - em inglês](https://www.youtube.com/watch?v=fYq5PXgSsbE);
- [Entenda o POSITION](https://www.youtube.com/watch?v=7svFaPgLCnc&t=61s);
- [Position in 9 Minutes - em inglês](https://www.youtube.com/watch?v=jx5jmI0UlXU);

**Jogos pra quem é de jogos - de CSS!! :)**

- [Flexbox Froggy - Jogo do Sapinho; pra aprender flexbox](https://flexboxfroggy.com/);
- [CSS Diner - Jantando com CSS; pra aprender sobre como usar seletores em CSS](https://flukeout.github.io/);
- [Flexbox Defense - Defendendo o CSS; outra forma de aprender flexbox](http://www.flexboxdefense.com/);

---





