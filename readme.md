# 📦 Cartão de Visualização do Produto

Este é um projeto simples e elegante de um **Cartão de Produto Responsivo**, inspirado em um desafio do Frontend Mentor. A página exibe um produto com imagem, descrição, preço atual e antigo, além de um botão de adicionar ao carrinho.

---

## 🎯 Objetivo

Criar um cartão de produto responsivo com foco em:

- ✅ Boas práticas de **HTML semântico**
- ✅ Estilização moderna com **CSS puro**
- ✅ Layout **mobile-first** e adaptação para telas maiores com **media queries**
- ✅ Organização de código em **arquivos separados (HTML, CSS e imagens)**

---

## 🗂️ Arquitetura do Projeto

```
/src
 ├── css
 │    ├── style.css         # Estilo base (mobile-first)
 │    ├── media.css         # Estilo para telas maiores (desktop)
 │
 ├── images
 │    ├── favicon-32x32.png # Favicon da página
 │    ├── image-product-mobile.jpg # Imagem para dispositivos móveis
 │    ├── image-product-desktop.jpg # Imagem para desktops
 │    ├── icon-cart.svg     # Ícone do botão de adicionar ao carrinho
 │
index.html                  # Estrutura HTML da página
LICENSE                     # Licença do projeto
README.md                   # Descrição do projeto
```

---

## 🖥️ Características

✅ **Layout responsivo**

- Mobile-first (estilo definido em `style.css`)
- Quebra para o layout desktop em **600px+** com `media.css`

✅ **HTML semântico**

- Uso de `<main>`, `<article>`, `<figure>` e `<button>` para melhor acessibilidade e SEO.

✅ **Design elegante**

- Tipografia moderna com as fontes [Fraunces](https://fonts.google.com/specimen/Fraunces) e [Montserrat](https://fonts.google.com/specimen/Montserrat).
- Cores suaves e harmônicas (definidas com variáveis CSS).

---

## 📱 Responsividade

- 📱 **Mobile**: layout em coluna com imagem acima do texto.
- 💻 **Desktop (600px+)**: layout em linha com a imagem à esquerda e texto à direita.

---

## 🚀 Como visualizar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   ```
2. Abra o arquivo `index.html` no seu navegador.

ou

1. Acesse a página do projeto clicando [aqui](https://charlesson-mp.github.io/product-preview-card-component/)

---

## 📜 Licença

Este projeto está licenciado sob a licença [MIT](./LICENSE).

