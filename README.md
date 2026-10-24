# 🛍️ Catálogo de Produtos

Aplicativo desenvolvido com **React Native, Expo e TypeScript**, como parte dos meus estudos em Desenvolvimento Mobile.

O projeto tem como objetivo aplicar conceitos de JavaScript moderno, manipulação de arrays, componentes reutilizáveis e comunicação entre componentes através de Props.

## 🚀 Funcionalidades

- Listagem de produtos filtrados por categoria.
- Consulta de um produto específico pelo ID.
- Exibição da quantidade total de produtos cadastrados.
- Cálculo do valor total dos produtos.
- Botão interativo para consultar o catálogo.
- Interface organizada em componentes reutilizáveis.

## 🛠️ Tecnologias utilizadas

- React Native
- Expo
- TypeScript
- JavaScript (ES6+)
- Expo Router

## 📚 Conceitos aplicados

- **Objetos e arrays:** organização dos dados dos produtos.
- **Arrow Functions:** definição das funções e componentes.
- **Template Strings:** exibição dinâmica de informações.
- **Desestruturação:** acesso às propriedades dos objetos e Props.
- **map():** renderização dos produtos.
- **filter():** filtragem por categoria.
- **find():** localização de um produto pelo ID.
- **reduce():** cálculo do valor total.
- **Props:** comunicação entre componentes pai e filho.
- **Pressable:** interação com o usuário.

## 📱 Como executar o projeto

**1. Clone o repositório:**

```bash
git clone URL_DO_REPOSITORIO
```

**2. Entre na pasta do projeto:**

```bash
cd CatalogoProdutos_N1
```

**3. Instale as dependências:**

```bash
npm install
```

**4. Inicie o Expo:**

```bash
npx expo start
```

O aplicativo pode ser executado no navegador ou em um ambiente compatível com Expo.

## 📂 Organização do projeto

```text
src/
├── app/
│   ├── index.tsx
│   └── _layout.tsx
└── components/
    ├── Produto.tsx
    └── Resumo.tsx
```

- **index.tsx:** tela principal, dados e operações do catálogo.
- **Produto.tsx:** componente responsável por exibir as informações dos produtos.
- **Resumo.tsx:** componente que apresenta a quantidade e o valor total.
- **_layout.tsx:** configuração de navegação da aplicação.

## 🎯 Objetivo

Consolidar conhecimentos de Desenvolvimento Mobile por meio de uma aplicação prática, explorando organização de código, reutilização de componentes e manipulação de dados.

---

💻 Projeto desenvolvido para fins acadêmicos e de aprendizado.
