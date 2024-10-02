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



dicas de aprendizagem
js versus ecmascript
requisitos de software
primeiros scripts em js

