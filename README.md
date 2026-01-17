# Landing Page - God of War


Esta é uma landing page temática para o jogo God of War (2018), desenvolvida como parte de um desafio técnico. O projeto foi construído do zero, desde o protótipo no Figma até a codificação e a implantação, com o design responsivo "Mobile First".

A página apresenta informações sobre a saga, os personagens e o jogo principal, com elementos interativos como carrosséis e modais para criar uma experiência imersiva para o usuário.

## 🚀 Como Rodar o Projeto

Este projeto é uma aplicação web estática, então você só precisa de um navegador para executá-lo.

1.  Copie o codigo html, css e java script e as fotos usadas
2.  Cole na sua pasta
3.  Abra o .html e clique em live server, se não tiver, baixe a extensão

---

O código está organizado da seguinte forma:

-   index.html: O esqueleto da página. Contém toda a estrutura semântica dos componentes, como o header, as seções (hero, saga, personagens, epílogo) e o footer.

-   style.css: A aparência visual do site. O código segue a metodologia Mobile First, com estilos base para celular e adaptações para telas maiores . As principais seções de estilo são:
    -   Estilos Gerais e Reset: Define a aparência base do site.
    -   Componentes (Mobile First): Estilização individual de cada seção (`.header`, `.secao-hero`, `.card-jogo`, `.modal`, etc.).
    -   Design Responsivo (Desktop): Contém as regras que adaptam o layout para telas maiores.

-   script.js: O "cérebro" da interatividade. Suas principais funcionalidades são:
    -   Menu Hambúrguer: Controla a abertura e o fechamento do menu de navegação no modo mobile, incluindo a funcionalidade de fechar ao clicar fora.
    -   Sistema de Modais: Lógica genérica que controla a abertura e o fechamento de todos os modais da página, identificando qual modal abrir com base no botão que foi clicado (`data-modal-id`).

---

Projeto desenvolvido por Arthur Piloto.

-   GitHub: [@ArthurPilotob](https://github.com/ArthurPilotob)
-   LinkedIn: [Arthur Piloto]

