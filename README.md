# 🛍️ Store Beautiful - Site Institucional & E-Commerce

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)](#-próximos-passos)
[![Licença](https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge)](#-licença)

Bem-vindo ao repositório do **Store Beautiful**! Este projeto é um website estático desenvolvido utilizando boas práticas de **HTML5 Semântico**, foco em acessibilidade, organização de ativos e arquitetura web clara. O site simula uma loja de produtos de beleza e estética com catálogo, modal nativo, formulário de contato e FAQ interativo.

---

## 📌 Sumário

- [ Visão Geral](#-visão-geral)
- [ Architecture & Estrutura de Arquivos](#-estrutura-de-arquivos)
- [ Páginas do Site e Análise Estrutural](#-páginas-do-site-e-análise-estrutural)
  - [1. Página Inicial (`index.html`)](#1-página-inicial-indexhtml)
  - [2. Catálogo de Produtos (`produtos.html`)](#2-catálogo-de-produtos-produtoshtml)
  - [3. Página de Contato (`contato.html`)](#3-página-de-contato-contatohtml)
- [🎯 Destaques Técnicos e Boas Práticas](#-destaques-técnicos-e-boas-práticas)
- [📊 Tabela do Catálogo de Produtos](#-tabela-do-catálogo-de-produtos)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔮 Próximos Passos e Melhorias](#-próximos-passos-e-melhorias)
- [📷 Créditos de Mídia](#-créditos-de-mídia)
- [📝 Licença](#-licença)

---

## 📖 Visão Geral

O **Store Beautiful** foi idealizado como uma plataforma institucional e catálogo e-commerce fictício. O objetivo do projeto é demonstrar o poder e a flexibilidade do **HTML5 nativo**, utilizando recursos modernos da linguagem (como tags semânticas de layout, formulários com validação nativa, janela modal via `<dialog>` e componentes sanfona via `<details>`) sem dependência inicial de frameworks pesados.

---

## 📁 Estrutura de Arquivos

A organização dos arquivos e pastas do projeto segue uma estrutura limpa e modular:

```text
loja_produtos/
├── assets/
│   └── images/
│       ├── favicon/
│       │   ├── favicon.ico
│       │   └── web-app-manifest-192x192.png
│       └── produtos/
│           ├── produto1.jpg
│           ├── produto2.jpg
│           ├── produto3.jpg
│           ├── produto4.jpg
│           └── produto5.jpg
├── index.html          # Página principal (Banner, Sobre Nós e Destaques)
├── produtos.html       # Catálogo completo com 5 produtos e Modal de Compra
├── contato.html        # Formúlário de atendimento, Endereço, Google Maps e FAQ
└── README.md           # Documentação completa do repositório
```

---

## 📄 Páginas do Site e Análise Estrutural

### 1. Página Inicial (`index.html`)
A página inicial atua como a vitrine da marca, atraindo o visitante com ofertas e introduzindo a identidade institucional:
* **Cabeçalho (`<header>`):** Logotipo com link e menu de navegação (`<nav>`) para seções internas e outras páginas.
* **Banner Promocional (`<section id="inicio">`):** Chamada para ação (*Call to Action - CTA*) destacando descontos de lançamento de até 40%.
* **Sobre Nós (`<section id="sobre">`):** Breve histórico da empresa e lista de valores institucionais (**Inovação**, **Qualidade** e **Compromisso**).
* **Produtos em Destaque (`<section id="produtos">`):** Três artigos (`<article>`) representando os carros-chefe (*Produto Alfa*, *Produto Beta* e *Produto Gama*), com imagens, legendas e links diretos para o catálogo.
* **Rodapé (`<footer>`):** Informações de contato direto, links para redes sociais e copyright.

### 2. Catálogo de Produtos (`produtos.html`)
Exibe a lista completa de itens disponíveis na loja com suporte a interação nativa:
* **Cards de Produtos (`<article>`):** Cada produto possui imagem com carregamento diferido (`loading="lazy"`), descrição em `<figcaption>`, preço formatado e botão de ação.
* **Navegação por Âncora:** Permite direcionamento direto a produtos específicos (ex: `produtos.html#Produto02`).
* **Modal Nativo HTML5 (`<dialog>`):** Acionado ao clicar no botão *Comprar*. Notifica o usuário sobre o status de desenvolvimento do sistema de checkout de forma acessível.

### 3. Página de Contato (`contato.html`)
Centraliza o atendimento e informações operacionais da empresa:
* **Formulário de Contato (`<form>`):** Coleta de *Nome*, *E-mail* e *Mensagem* com atributos de validação nativa (`required`, `type="email"`).
* **Informações Institucionais (`<address>`):** Endereço físico na Av. Paulista, telefone comercial e horário de funcionamento.
* **Localização Interativa (`<iframe>`):** Mapa incorporado via Google Maps para navegação simplificada.
* **FAQ / Perguntas Frequentes (`<details>` / `<summary>`):** Acordeão sanfona nativo para dúvidas recorrentes sobre prazos de entrega e formas de pagamento.

---

## 🎯 Destaques Técnicos e Boas Práticas

| Recurso | Tag/Atributo HTML | Descrição / Benefício |
| :--- | :--- | :--- |
| **Semântica Estrutural** | `<header>`, `<main>`, `<nav>`, `<section>`, `<article>`, `<footer>` | Melhora a indexação em motores de busca (SEO) e leitores de tela. |
| **Acessibilidade (a11y)** | `alt`, `aria-labelledby`, `<address>` | Garantia de leitura acessível para deficientes visuais e estruturação de dados de contato. |
| **Modal Nativo** | `<dialog id="meuModal">` | Interface de caixa de diálogo leve sem necessidade de bibliotecas externas de JS. |
| **Acordeão Sem JS** | `<details>` / `<summary>` | Expansão/retração de respostas no FAQ com performance máxima. |
| **Otimização de Imagens** | `loading="lazy"` | Carregamento sob demanda das imagens dos produtos, economizando dados e acelerando o carregamento. |
| **Validação NAtiva** | `required`, `type="email"`, `rows="5"` | Validação automática no envio de formulários diretamente no navegador. |

---

## 📊 Tabela do Catálogo de Produtos

| ID | Nome do Produto | Categoria / Descrição | Preço | Ação |
| :---: | :--- | :--- | :---: | :---: |
| `#Produto01` | **Produto 1** | Perfume de alta qualidade com fragrância duradoura | **R$ 99,90** | Modal de Compra |
| `#Produto02` | **Produto 2** | Maquiagem de alta qualidade com acabamento duradouro | **R$ 39,90** | Modal de Compra |
| `#Produto03` | **Produto 3** | Perfume tropical com fragrância intensa | **R$ 49,90** | Modal de Compra |
| `#Produto04` | **Produto 4** | Perfume amadeirado com notas sofisticadas | **R$ 59,90** | Modal de Compra |
| `#Produto05` | **Produto 5** | Loção corporal hidratante com aroma suave e refrescante | **R$ 69,90** | Modal de Compra |

---

## 🚀 Como Executar o Projeto

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/jhowkis/loja_produtos.git
   ```
2. **Navegar até a pasta:**
   ```bash
   cd loja_produtos
   ```
3. **Executar no Navegador:**
   - Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
   - Alternativamente, utilize a extensão **Live Server** no VS Code para recarregamento em tempo real.
4. **Acessar via GitHub Pages:**
   - [https://jhowkis.github.io/loja_produtos/](https://jhowkis.github.io/loja_produtos/)

---

## 🔮 Próximos Passos e Melhorias

- [ ] **Estilização com CSS3:** Criar uma identidade visual atraente usando CSS Grid, Flexbox, variáveis CSS e tipografia personalizada.
- [ ] **Design Responsivo:** Adaptar o layout para exibição fluida em dispositivos móveis, tablets e desktops (*Mobile First*).
- [ ] **Interatividade com JavaScript:** Integrar dinamismo ao modal de compras, carrinho de compras e validações personalizadas no formulário.
- [ ] **Integração Backend:** Conectar o formulário de contato e o fluxo de pedidos a um backend em PHP/Node.js com banco de dados.

---

## 📷 Créditos de Mídia

- **Imagens dos Produtos:** Obtidas gratuitamente em alta resolução no [PxHere](https://pxhere.com/pt/photo/634760).
- **Ícones e Favicon:** Estruturado com suporte a Web App Manifest.

---

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais de estudo e consolidação de conhecimentos em Desenvolvimento Web Front-End.

---

*Desenvolvido por **Store Beautiful** &copy; 2026. Todos os direitos reservados.*