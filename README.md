# Website Institucional Responsivo - Gabinete do Vereador

> Um site estático de várias páginas desenvolvido com HTML e CSS puros, focado em design responsivo e estrutura semântica.

Este projeto foi criado como um exercício prático para aplicar e demonstrar habilidades fundamentais de desenvolvimento front-end. O objetivo era construir um site institucional funcional, limpo e que oferecesse uma boa experiência de usuário tanto em desktops quanto em dispositivos móveis.

---

### ✨ Key Features (Principais Funcionalidades)

* **Layout com Sidebar Fixa:** Utiliza um menu lateral para navegação principal em telas maiores, um padrão comum em dashboards e sites institucionais.
* **Design Totalmente Responsivo:** O layout se adapta fluidamente a telas menores. Em dispositivos móveis, a sidebar se transforma em um menu horizontal no topo para otimizar o espaço e a usabilidade.
* **Navegação Multi-página:** O site é composto por três páginas interligadas (`Início`, `Contato` e `Login`), demonstrando a estruturação de um projeto web completo.
* **Estrutura Semântica de HTML:** O código utiliza tags HTML5 semânticas (`<main>`, `<h2>`, `<ul>`, etc.), o que melhora a acessibilidade e a otimização para motores de busca.
* **Incorporação de Mídia Externa:** A página inicial inclui vídeos do YouTube incorporados de forma responsiva.

---

### 🧠 Desafios Técnicos e Soluções

O principal desafio técnico foi garantir que a experiência do usuário fosse consistente em todos os dispositivos.

> **Problema:** Um layout com sidebar fixa funciona bem em desktops, mas consome muito espaço em telas de celular, prejudicando a visualização do conteúdo principal.
>
> **Solução:** Implementei **Media Queries** em CSS. Para telas com largura máxima de 780px, as seguintes regras são aplicadas:
> 1.  A `sidebar` abandona a posição fixa e se torna um bloco de largura total no topo da página.
> 2.  Os itens do menu são reorganizados em um layout flexível (`display: flex`) para se alinharem horizontalmente.
> 3.  A margem do conteúdo principal (`<main>`) é ajustada para ocupar o espaço que antes era da sidebar, garantindo o uso completo da tela.

---

### 🛠️ Tecnologias Utilizadas

Este projeto foi construído do zero utilizando apenas tecnologias web fundamentais, sem o uso de frameworks.

* **HTML5:** Para a estruturação e semântica do conteúdo.
* **CSS3:** Para estilização, layout (Flexbox) e responsividade (Media Queries).

---

### 🚀 Como Visualizar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/cristianogomesdpf/Gabinete
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd Gabinete
    ```
3.  **Abra o arquivo `index.html`:**
    Basta abrir o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).
