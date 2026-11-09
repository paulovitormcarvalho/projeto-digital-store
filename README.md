# Digital Store 🛍️

Projeto final de **Front-end** desenvolvido durante o curso **Geração Tech 4.0 / Digital College**. A aplicação simula a interface de um e-commerce de calçados, com catálogo de produtos, pesquisa, filtros e página de detalhes, utilizando **React** e **Vite**.

### 🔗 Acesse o projeto

- **Site publicado:** [digital-store-paulo-vitor.vercel.app](https://digital-store-paulo-vitor.vercel.app/)
- **Código-fonte:** [github.com/paulovitormcarvalho/projeto-digital-store](https://github.com/paulovitormcarvalho/projeto-digital-store)
- **Design de referência:** [Digital Store no Figma](https://www.figma.com/design/4mBmKhzGQnIY0MczhpdQ2v/DRIP-STORE---DIGITAL-COLLEGE--Copy---Copy-?node-id=101-2)

## 🎯 Objetivo

Aplicar os fundamentos de desenvolvimento Front-end na construção de uma aplicação web com **componentes reutilizáveis**, **navegação entre páginas**, **manipulação de dados em JavaScript** e **layout responsivo**, seguindo os requisitos do projeto Digital Store.

## 🛠️ Tecnologias utilizadas

- **React e JSX:** construção de interfaces por componentes.
- **JavaScript:** lógica de apresentação, filtros e manipulação dos produtos.
- **React Router DOM:** navegação entre páginas e rotas dinâmicas.
- **Vite:** ambiente de desenvolvimento e build de produção.
- **CSS3:** estilos, Flexbox, Grid e media queries.
- **ESLint:** análise estática do código.
- **Vercel:** hospedagem e publicação da aplicação.

## ✨ Funcionalidades

### Página inicial
- Carrossel de imagens em destaque.
- Seção de coleções em destaque.
- Listagem de oito produtos em alta.
- Links para navegar pelo catálogo e acessar os detalhes de produtos.

### Listagem de produtos
- Pesquisa de produtos a partir do campo de busca.
- Filtragem por marca, categoria e gênero.
- Ordenação por menor ou maior preço.
- Exibição da quantidade de produtos encontrados.
- Opção de limpar os filtros selecionados.

### Visualização do produto
- Galeria de imagens com navegação e miniaturas.
- Nome, descrição, avaliações e preços do produto.
- Exibição condicional do preço promocional.
- Seleção visual de tamanho e cor.
- Seção de produtos recomendados.

### Layout e navegação
- Cabeçalho e rodapé compartilhados entre páginas.
- Navegação com React Router.
- Layout adaptável a diferentes tamanhos de tela.
- Telas demonstrativas de cadastro, entrada e pedidos.

> **Observação:** este é um projeto acadêmico de Front-end. Os produtos e preços são dados de exemplo armazenados localmente. Não há API, banco de dados, autenticação real, carrinho persistente nem processamento de compras. Os formulários e a ação de compra são demonstrativos.

## 🚀 Como executar localmente

### Pré-requisitos

- [Node.js](https://nodejs.org/) e npm instalados.
- Git instalado (para clonar o repositório).

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/paulovitormcarvalho/projeto-digital-store.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd projeto-digital-store
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o ambiente de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Abra no navegador o endereço indicado no terminal (normalmente `http://localhost:5173`).

### Comandos disponíveis

| Comando | Finalidade |
| --- | --- |
| `npm run dev` | Inicia o servidor de desenvolvimento. |
| `npm run lint` | Executa as verificações do ESLint. |
| `npm run build` | Gera a versão de produção na pasta `dist/`. |
| `npm run preview` | Permite visualizar localmente o build gerado. |

## 🧭 Rotas principais

| Rota | Página |
| --- | --- |
| `/` | Página inicial. |
| `/products` | Catálogo, pesquisa e filtros. |
| `/produtos` | Rota alternativa para o catálogo. |
| `/product/:id` | Detalhes de um produto. |
| `/categorias` | Acesso demonstrativo às categorias. |
| `/meus-pedidos` | Página demonstrativa de pedidos. |
| `/entrar` | Interface demonstrativa de login. |
| `/cadastro` | Interface demonstrativa de cadastro. |

Exemplo de pesquisa pela URL: `/products?filter=tenis`.

## 📁 Organização do projeto

```text
src/
├── assets/              # Recursos visuais
├── components/          # Componentes reutilizáveis
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Section.jsx
│   ├── ProductCard.jsx
│   ├── ProductListing.jsx
│   ├── Gallery.jsx
│   ├── BuyBox.jsx
│   └── ProductOptions.jsx
├── data/
│   └── products.js      # Dados demonstrativos dos produtos
├── pages/
│   ├── HomePage.jsx
│   ├── ProductListingPage.jsx
│   ├── ProductViewPage.jsx
│   └── Layout.jsx
├── utils/
│   └── prices.js        # Formatação e lógica de preços
├── App.jsx              # Definição das rotas
├── main.jsx             # Ponto de entrada do React
├── index.css
└── styles.css

public/                   # Imagens públicas utilizadas na loja
```

O projeto utiliza **props** e **children** para compor a interface, **arrays e `map()`** para listar produtos, **hooks do React** para gerenciar interações e **`Intl.NumberFormat`** para apresentar valores em reais.

## 🌐 Deploy

A aplicação está publicada na **Vercel**:

**https://digital-store-paulo-vitor.vercel.app/**

A publicação é feita a partir do repositório do GitHub. O arquivo `vercel.json` configura o redirecionamento necessário para que as rotas do React Router funcionem ao acessar ou atualizar diretamente uma URL interna.

## 🎨 Referências e créditos

- [Repositório-base do projeto — Digital College](https://github.com/digitalcollegebr/projeto-digital-store)
- [Layout de referência no Figma](https://www.figma.com/design/4mBmKhzGQnIY0MczhpdQ2v/DRIP-STORE---DIGITAL-COLLEGE--Copy---Copy-?node-id=101-2)

## 👨‍💻 Autor

**Paulo Vitor**
GitHub: [@paulovitormcarvalho](https://github.com/paulovitormcarvalho)

Projeto acadêmico desenvolvido para avaliação final da disciplina de Front-end.
