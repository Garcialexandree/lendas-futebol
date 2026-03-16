# # ⚽ Lendas do Futebol - Perfil Interativo

Este é um projeto de front-end interativo que apresenta perfis detalhados de três ícones do futebol mundial: Neymar Jr., Lionel Messi e Cristiano Ronaldo. O foco principal foi a criação de uma interface dinâmica, responsiva e com controle rigoroso de elementos multimédia.

## 🚀 Demonstração
(https://garcialexandree.github.io/lendas-futebol/)

## 🛠️ Desafios Técnicos & Soluções

### 1. Gestão de Áudio e Vídeo (YouTube Iframes)
*Problema:* Ao trocar de aba entre os jogadores, o vídeo do jogador anterior continuava a ser reproduzido em segundo plano, gerando uma confusão de áudio.
*Solução:* Implementei uma lógica em JavaScript que deteta a troca de contexto e reinicia o atributo src de todos os iframes. Isso força o encerramento imediato do processo de buffering e áudio do vídeo anterior.

### 2. Tabelas Responsivas sem Scroll
*Problema:* Tabelas de estatísticas costumam "vazar" da tela em dispositivos móveis, criando barras de rolagem horizontais desagradáveis.
*Solução:* Utilizei table-layout: fixed combinado com border-spacing e media queries. A tabela foi transformada num sistema de "cards" de dados que se ajustam automaticamente à largura do smartphone, mantendo a legibilidade.

### 3. Feedback do Utilizador (UX/UI)
*Problema:* Interfaces estáticas podem parecer "mortas".
*Solução:* - *Som de UI:* Utilização da *Web Audio API* para gerar sons de clique sintetizados via código, sem necessidade de carregar ficheiros MP3 externos.
- *Transições:* Uso de classes CSS combinadas com opacity e transform: translateY para criar um efeito de entrada suave.
- *Visual:* Efeitos de Glow (brilho) dinâmicos que mudam de cor conforme a identidade visual de cada jogador.

## 🧰 Tecnologias Utilizadas
- *HTML5*: Estruturação semântica.
- *CSS3*: Animações, Flexbox e Design Responsivo.
- *JavaScript (Vanilla)*: Manipulação de DOM, Web Audio API e lógica de controlo de media.
- *Google Fonts & Font Awesome*: Tipografia e ícones.

## ✒️ Autor
* *Alexandre Garcia* - Desenvolvimento e Design
![Demonstração do Projeto](./demo.gif.gif)
# Acesse o link do site https://lendasdofut.netlify.app
