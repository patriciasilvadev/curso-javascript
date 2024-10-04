Não pule, anote tudo, use duas telas, pratique, compartilhe!

# Módulo A 

## Aula 01 - O que o JavaScript é capaz de fazer?


JavaScript (JS) é uma linguagem de programação essencial para a web, usada principalmente para adicionar interatividade a sites e páginas. Ela permite:

* Tornar as páginas web dinâmicas e interativas.
* Manipular o DOM (Document Object Model), ou seja, modificar elementos de uma página HTML em tempo real.
* Capturar e validar dados de formulários, sem a necessidade de enviar ao servidor.
* Fazer requisições assíncronas (AJAX) para atualizar conteúdos sem recarregar a página.
* Criar animações, efeitos visuais, e transições de conteúdo.
* Trabalhar com APIs externas, como Google Maps, redes sociais, etc.
* Desenvolver aplicações web dinâmicas (SPA - Single Page Applications) com frameworks como React, Angular e Vue.js.
* Criar jogos e gráficos interativos com bibliotecas como p5.js e Three.js.


**Diferença entre cliente e servidor na Internet**

**Cliente:** O dispositivo (computador, tablet, smartphone) usado para acessar uma aplicação web por meio de um navegador. Ele envia solicitações para o servidor.

**Servidor:** Um computador remoto que recebe e processa solicitações de clientes, enviando de volta os dados necessários, como páginas HTML, arquivos ou respostas de APIs. O servidor geralmente contém a lógica de backend e os bancos de dados.

**Para que servem HTML5, CSS3 e JavaScript?**

**HTML5:** Marcações de hipertexto para estruturar o conteúdo de páginas web (ex: títulos, parágrafos, imagens, vídeos, etc.).
**CSS3:** Linguagem usada para estilizar e definir o layout das páginas web, controlando cores, tamanhos, margens, animações, etc.
**JavaScript:** Linguagem de programação que adiciona interatividade, manipulação de eventos e dinamicidade às páginas web, como descrito anteriormente.

**Quatro sites que utilizam JavaScript**

* Facebook - Utiliza JavaScript para a interatividade e atualização em tempo real da página.
* Google - Usa JavaScript em quase todos os seus serviços, como o Google Maps e o Gmail.
* Netflix - JavaScript é utilizado para streaming e navegação pela plataforma.
* Amazon - Usa JavaScript para oferecer uma experiência de compra dinâmica e interativa.

_A prática leva a perfeição, e o erro a excelência_

**Como desabilitar o JavaScript no Google Chrome:**
1. Abra o Google Chrome.
2. Clique no ícone de três pontinhos no canto superior direito da tela.
3. Selecione Configurações.
4. Na seção de Privacidade e Segurança, clique em Configurações do site.
5. Role até encontrar a opção JavaScript e clique nela.
6. Desabilite a opção Permitido (recomendado) para desativar o JavaScript.

**Alguns comandos aplicados no console**

Esses comandos abaixo podem ser executados diretamente no console do navegador para manipular o conteúdo e estilo de uma página

* Para para mudar a cor de fundo do site
```
document.body.style.background = 'black'
```

* Para deixar o logo em tons de cinza
Supondo que o logo tenha um ID ou classe, você pode usar CSS para aplicar o efeito de escala de cinza
```
document.querySelector('#logo').style.filter = 'grayscale(100%)';
```

* Para mudar o título da notícia. 
Supondo que o título da notícia esteja dentro de um elemento HTML com um ID ou classe, você pode alterar o texto assim:
```
document.querySelector('.titulo-noticia').innerText = 'Novo título da notícia';
```

---

## Aula 02 - Como chegamos até aqui?

A história da internet e das tecnologias web evoluiu de maneira rápida e fascinante. Vamos entender como tudo se desenvolveu:

- **1970 - Surgimento da Internet:**
  A internet começou como um projeto militar nos EUA chamado **ARPANET**, que ligava computadores em rede. O objetivo era permitir a troca de informações entre instituições militares e acadêmicas de forma rápida e segura. Ao longo dos anos, ela foi se expandindo até se tornar a base da internet que conhecemos hoje.

- **1993 - Surgimento do HTML e da WWW:**
  O **HTML (Hypertext Markup Language)** foi criado por **Tim Berners-Lee**. Ele criou a linguagem para construir páginas web que podiam ser visualizadas em navegadores. No mesmo ano, surgiu a **World Wide Web (WWW)**, que permitia a interligação de páginas através de links, possibilitando a navegação na internet como conhecemos hoje.

- **1995 - Surgimento do JavaScript:**
  **Brendan Eich**, trabalhando para a empresa **Netscape**, criou o **JavaScript**.


Aqui estão as respostas detalhadas para suas perguntas:

### 1. **Qual empresa criou o JavaScript?**
   O **JavaScript** foi criado pela empresa **Netscape Communications** em 1995. O desenvolvedor **Brendan Eich** foi o responsável por desenvolver a linguagem em apenas 10 dias, com o objetivo de permitir que páginas web fossem dinâmicas e interativas dentro do navegador **Netscape Navigator**, que era muito popular na época.

### 2. **Java e JavaScript possuem alguma relação?**
   Apesar dos nomes parecidos, **Java** e **JavaScript** não têm uma relação direta. São duas linguagens de programação completamente diferentes:
   - **Java** é uma linguagem orientada a objetos, desenvolvida pela **Sun Microsystems** (agora parte da Oracle) em 1995. É usada para desenvolver aplicativos de grande escala, incluindo aplicativos desktop, mobile e enterprise.
   - **JavaScript**, por outro lado, foi criado como uma linguagem de script para tornar as páginas da web mais interativas. JavaScript é mais focado no frontend (embora, com o surgimento de tecnologias como Node.js, ele também seja usado no backend).

   O nome **JavaScript** foi escolhido por razões de marketing, já que **Java** estava muito popular na época, mas a semelhança termina no nome.

### 3. **O ECMAScript tem a ver com JavaScript?**
   Sim, **ECMAScript** e **JavaScript** estão diretamente relacionados. **ECMAScript** é o nome oficial do padrão que define como o JavaScript deve funcionar. A primeira padronização ocorreu em **1997**, sob a organização **ECMA International**. JavaScript é uma implementação desse padrão.

   A relação é a seguinte:
   - **JavaScript** é o nome usado para a implementação da linguagem nos navegadores e na web.
   - **ECMAScript** é o nome técnico do padrão que as várias implementações de JavaScript seguem. Toda atualização significativa da linguagem JavaScript, como ES6 (lançada em 2015), é formalmente uma atualização do ECMAScript.

### 4. **Sabia que o WhatsApp é criado em JavaScript?**
   Sim, o **WhatsApp** utiliza **JavaScript** extensivamente em seu desenvolvimento, especialmente no **WhatsApp Web**. Ele foi construído usando uma tecnologia chamada **Node.js**, que permite que o JavaScript seja executado no servidor (backend). Isso permite que o WhatsApp ofereça a versão web do aplicativo e manuseie comunicação em tempo real com seus servidores.

Em resumo:
- **JavaScript** é a linguagem usada para adicionar interatividade à web.
- **Java** e **JavaScript** não têm ligação, apesar do nome.
- **ECMAScript** é o padrão que define como JavaScript deve ser.
- O **WhatsApp Web** e outros sistemas de backend do WhatsApp são escritos em JavaScript utilizando o Node.js.

---

## Aula 03 - Dando os primeiros passos

Nesta aula, são fornecidas dicas importantes para começar a aprender **JavaScript** e, mais especificamente, como desenvolver suas habilidades na programação. Vamos destrinchar o conteúdo:

### 1. **Dicas para aprender JavaScript de forma eficiente:**
   - **Não pule, assista tudo:** Cada detalhe conta no aprendizado de programação, então é importante seguir todas as aulas com atenção para não perder nenhum conceito.
   - **Anote tudo:** Fazer anotações enquanto estuda ajuda a fixar o conteúdo e é útil para consultar mais tarde.
   - **Use duas telas:** Ter duas telas facilita muito o aprendizado, pois você pode manter o vídeo da aula em uma tela e o editor de código ou navegador na outra, permitindo praticar simultaneamente.
   - **Leia livros e guias:** Além de assistir às aulas, ler livros e guias é uma ótima forma de aprofundar o conhecimento e aprender com diferentes abordagens e exemplos.
   - **Pratique:** A prática é essencial para aprender a programar. Quanto mais você codificar, mais rápido você vai absorver os conceitos.
   - **Compartilhe:** Compartilhar seu conhecimento com outros, seja em grupos de estudo ou redes sociais, ajuda a reforçar o que aprendeu e, possivelmente, aprender com os outros.
   - **Crie projetos:** A melhor maneira de consolidar o aprendizado é aplicando-o. Crie pequenos projetos (páginas web, jogos simples, etc.) para colocar em prática o que você aprendeu.

### 2. **Bibliografia recomendada:**
   Estes dois livros são clássicos e altamente recomendados para quem está aprendendo ou deseja se aprofundar em **JavaScript**:

   - **"JavaScript: O Guia Definitivo"** de David Flanagan:
     Esse livro é uma referência muito completa e técnica, ideal para aqueles que querem entender a fundo todos os aspectos da linguagem JavaScript, desde o básico até conceitos avançados.
   
   - **"JavaScript: Guia do Programador"** de David Flanagan:
     Focado em práticas para desenvolvedores, este livro apresenta exemplos práticos, técnicas e dicas sobre como escrever código JavaScript de maneira eficiente e eficaz.

### 3. **Guias de referência gratuitos:**
   Além dos livros, é sempre bom consultar recursos online, que são constantemente atualizados. Dois dos melhores guias de referência gratuitos são:

   - **Mozilla Developer Network (MDN):**
     O **MDN Web Docs** é uma das melhores fontes online para aprender **JavaScript** (e outras tecnologias da web, como HTML e CSS). Ele tem exemplos, explicações detalhadas e tutoriais.
     - Link: https://developer.mozilla.org

   - **ECMA (ECMAScript Standard):**
     A organização **ECMA International** é responsável pelo padrão oficial do **JavaScript**, chamado **ECMAScript**. Você pode consultar diretamente os documentos oficiais e o guia da linguagem.
     - Link: https://www.ecma-international.org/publications-and-standards/

### 4. **Requisitos para começar a programar em JavaScript:**

Para começar a praticar **JavaScript**, você precisa de algumas ferramentas básicas:

   - **Navegador:**
     O JavaScript é executado principalmente nos navegadores, como **Google Chrome**, **Firefox**, ou **Edge**. Esses navegadores possuem um console embutido, onde você pode escrever e testar códigos JavaScript em tempo real. O Chrome DevTools, por exemplo, é uma ferramenta poderosa para depuração e testes.
   
   - **Editor de código:**
     Para escrever código de maneira eficiente, é recomendável usar um **editor de código** especializado, como o **Visual Studio Code (VS Code)**, **Sublime Text**, ou **Atom**. Esses editores oferecem recursos como realce de sintaxe, sugestões de código e integração com o terminal, facilitando o desenvolvimento.

   - **Node.js:**
     **Node.js** é um ambiente de execução de **JavaScript** no lado do servidor. Com ele, você pode executar códigos JavaScript fora do navegador, criar servidores, manipular arquivos, e desenvolver aplicativos backend. Node.js expande muito o que você pode fazer com JavaScript, permitindo criar aplicações completas.


## Aula 04 - Criando seu primeiro Scripts

```html
<script>
    // Meu primeiro comando em JavaScript

    window.alert('Ola, mundo!');
    
    window.confirm('Está gostando de Javascript?');
    
    window.prompt('Agora Digite seu nome:');
</script>
```

### 1. <script>
  - A tag `<script>` é usada para incluir ou escrever código JavaScript em uma página HTML. O código dentro dessa tag será executado pelo navegador quando a página for carregada.
  - Nesse caso, o código JavaScript está sendo escrito diretamente no arquivo HTML. Alternativamente, você poderia usar a tag `<script>` para vincular um arquivo externo de JavaScript.

### 2. **Comentário (`// Meu primeiro comando em JavaScript`)**
   - **Comentário**: `//` é utilizado para adicionar comentários no código. Comentários são ignorados pelo navegador e servem para explicar o código ou fazer anotações para o programador. 
   - Neste caso, o comentário é "Meu primeiro comando em JavaScript".

### 3. **`window.alert('Ola, mundo!')`**
   - **`window.alert()`** é uma função que exibe uma **caixa de alerta** no navegador com uma mensagem.
   - Neste caso, a caixa de alerta vai mostrar o texto **"Ola, mundo!"**. O usuário verá uma janela popup com essa mensagem e precisará clicar em "OK" para fechar a caixa.

### 4. **`window.confirm('Está gostando de Javascript?')`**
   - **`window.confirm()`** exibe uma **caixa de confirmação** com uma mensagem e dois botões: **OK** e **Cancelar**.
   - A pergunta que será exibida é **"Está gostando de Javascript?"**. Dependendo da resposta do usuário, o comando pode retornar `true` (se o usuário clicar em **OK**) ou `false` (se o usuário clicar em **Cancelar**). 
   - Nesse código, o retorno de `true` ou `false` não está sendo armazenado ou utilizado, mas poderia ser usado para tomar decisões no código.

### 5. **`window.prompt('Agora Digite seu nome:')`**
   - **`window.prompt()`** exibe uma **caixa de diálogo** com uma mensagem e um campo de texto, onde o usuário pode digitar algo.
   - Neste caso, a mensagem exibida será **"Agora Digite seu nome:"**, e o usuário poderá digitar seu nome ou outro valor.
   - O valor que o usuário digitar será retornado como uma string. Neste código, o valor digitado não está sendo armazenado, mas poderia ser salvo em uma variável para uso posterior.

---

### Resumo do que o código faz:
1. Mostra um alerta simples com a mensagem "Ola, mundo!".
2. Exibe uma caixa de confirmação perguntando se o usuário está gostando de JavaScript, onde ele pode escolher entre "OK" ou "Cancelar".
3. Abre uma caixa de prompt que pede para o usuário digitar seu nome.

O código não armazena os resultados do `confirm()` e `prompt()`, mas isso pode ser feito com variáveis, por exemplo:

```javascript
let resposta = window.confirm('Está gostando de Javascript?');
let nome = window.prompt('Agora Digite seu nome:');
```

Esses valores poderiam ser usados para personalizar a interação com o usuário.




