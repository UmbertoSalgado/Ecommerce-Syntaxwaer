# SyntaxWear - Tênis e Sneakers Online

SyntaxWear é uma landing page para um e-commerce de tênis e sneakers, projetada para ser moderna, responsiva e visualmente atraente.

## Visão Geral

Este projeto consiste em uma única página (landing page) que apresenta a marca SyntaxWear e seus produtos. A página é totalmente responsiva e se adapta a diferentes tamanhos de tela, desde dispositivos móveis até desktops.

## Funcionalidades

- **Design Responsivo:** A interface se ajusta para proporcionar uma ótima experiência em qualquer dispositivo.
- **Menu de Navegação:** Menu principal que se transforma em um menu hambúrguer em telas menores.
- **Seção de Destaque (Hero):** Uma grande imagem de banner com um título e botões de chamada para ação.
- **Categorias de Produtos:** Seção que exibe as diferentes categorias de tênis (Casual, Esporte, Moderno, Futurista).
- **Grid de Produtos:** Uma grade de imagens que destaca os produtos em destaque.
- **Rodapé:** Inclui um formulário de inscrição para newsletter, links de navegação e ícones de redes sociais.

## Tecnologias Utilizadas

- **HTML5:** Para a estrutura da página.
- **CSS3:** Para a estilização, utilizando recursos modernos como:
  - **CSS Grid Layout:** Para o layout da grade de produtos.
  - **Flexbox:** Para o alinhamento e distribuição dos elementos.
  - **Variáveis CSS:** Para manter a consistência dos estilos.
  - **Media Queries:** Para a responsividade.
- **Google Fonts:** Para a tipografia do site.

## Estrutura do Projeto

```
Ecommerce-Syntaxwaer/
├── index.html
├── README.md
└── src/
    ├── css/
    │   ├── base.css
    │   ├── reset.css
    │   ├── variables.css
    │   └── components/
    │       ├── footer.css
    │       ├── header.css
    │       ├── hero.css
    │       ├── product-category.css
    │       └── product-grid.css
    └── images/
        ├── banners/
        ├── favicons/
        ├── icons/
        ├── logo/
        └── produtos/
```

### Descrição dos Arquivos

- **`index.html`**: O arquivo principal que contém toda a estrutura da página.
- **`src/css/`**: Pasta que armazena todos os arquivos de estilo.
  - **`reset.css`**: Um reset de CSS para garantir a consistência entre os navegadores.
  - **`variables.css`**: Define as variáveis de CSS utilizadas no projeto (cores, fontes, etc.).
  - **`base.css`**: Estilos básicos para o corpo da página e elementos comuns.
  - **`components/`**: Contém os arquivos CSS para cada componente da página (cabeçalho, rodapé, etc.).
- **`src/images/`**: Pasta que armazena todas as imagens do site, organizadas em subpastas.

## Como Utilizar

Para visualizar o site, basta abrir o arquivo `index.html` em seu navegador de preferência.

```bash
# Clone o repositório (opcional)
git clone https://github.com/seu-usuario/Ecommerce-Syntaxwaer.git

# Navegue até a pasta do projeto
cd Ecommerce-Syntaxwaer

# Abra o arquivo index.html no navegador
```

## Autor

Este projeto foi desenvolvido como parte do curso DevQuest.
