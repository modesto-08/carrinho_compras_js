# 🛒 Carrinho de Compras em JavaScript

### 📌 Sobre o Projeto

Este projeto é uma página web desenvolvida com **HTML5, CSS e JavaScript**, com o objetivo de simular um **Carrinho de Compras** interativo. 
A página foi construída utilizando uma estrutura base em HTML (com templates ocultos), estilização própria em CSS e toda a lógica de exibição, seleção de itens e cálculos feita dinamicamente através do JavaScript.

### 🚀 Tecnologias Utilizadas

- [x] HTML5
- [x] CSS3 (Estilos próprios)
- [x] JavaScript (Manipulação de DOM e lógica de carrinho)
- [x] Google Fonts (Hepta Slab e Lato)
- [x] Material Icons (Ícones do Google)

### 🎯 Funcionalidades (Status)

- [x] Exibição dinâmica de produtos na tela principal
- [x] Janela modal interativa para detalhes do produto
- [x] Seleção de tamanhos/variações para o mesmo item
- [x] Controle de quantidade (adicionar e remover na modal)
- [x] Adição do item ao carrinho
- [x] Menu lateral (carrinho) interativo e retrátil
- [x] Ajuste de quantidade direto no carrinho
- [x] Cálculo automático em tempo real de Subtotal, Desconto e Total
- [x] Layout adaptável para dispositivos móveis (mobile) e desktop
- [ ] Persistência de dados (salvar carrinho no LocalStorage para não perder ao recarregar a página)
- [ ] Integração com API de pagamento / Finalização de compra real
- [ ] Filtro de produtos por categoria na tela inicial

### 🖼️ Estrutura da Página

* **Modelos Ocultos (`.models`):** Templates HTML base usados pelo JavaScript para gerar os produtos e os itens do carrinho dinamicamente.
* **Cabeçalho (`header`):** Contém o botão de abrir o carrinho em versões mobile e o contador de itens.
* **Área Principal (`main`):** Onde a lista de produtos disponíveis é renderizada.
* **Barra Lateral (`aside`):** O carrinho de compras em si, mostrando os itens selecionados, valores e o botão de finalizar compra.
* **Janela Modal (`.modelsWindowArea`):** Tela sobreposta exibida ao clicar em um produto, contendo imagem ampliada, descrição, seletor de tamanhos, preço e botão de adicionar ao carrinho.

### 📱 Responsividade

O projeto utiliza marcações e classes específicas para adaptação visual, garantindo que o grid de produtos, a janela modal e o menu lateral do carrinho se ajustem perfeitamente tanto em telas grandes quanto em smartphones.

### ⚙️ Como Executar

1. Baixe a pasta completa do projeto.
2. Certifique-se de que a estrutura de pastas está correta (arquivo principal na raiz e as pastas `/css` e `/js` organizadas).
3. Abra o arquivo `index.html` em qualquer navegador web.

### 💡 Objetivo

Praticar:
* Estruturação de templates com HTML
* Estilização de modais e menus laterais com CSS puro
* Manipulação do DOM (Document Object Model) usando JavaScript
* Lógica de programação aplicada a sistemas de e-commerce (cálculos de carrinho, arrays e objetos)

