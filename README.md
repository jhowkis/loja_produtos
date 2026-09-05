# 🛍️ Store Beautiful - Meu Primeiro Site Web

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)](#-próximos-passos)

Bem-vindo ao repositório do **Store Beautiful**! Este projeto marca a criação do meu primeiro site estático, construído com foco nas melhores práticas de **HTML5 semântico**, acessibilidade e estruturação organizada de páginas web.

---

## 📌 Sumário

- [Visão Geral](#-visão-geral)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Páginas do Site](#-páginas-do-site)
  - [1. Página Inicial (`index.html`)](#1-página-inicial-indexhtml)
  - [2. Catálogo de Produtos (`produtos.html`)](#2-catálogo-de-produtos-produtoshtml)
  - [3. Página de Contato (`contato.html`)](#3-página-de-contato-contatohtml)
- [Recursos e Tecnologias Utilizadas](#-recursos-e-tecnologias-utilizadas)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Próximos Passos & Melhorias](#-próximos-passos--melhorias)
- [Licença](#-licença)

---

## 📖 Visão Geral

O **Store Beautiful** é uma plataforma institucional e catálogo e-commerce fictício desenvolvido para consolidar conceitos fundamentais do desenvolvimento web front-end. O site é composto por três páginas principais totalmente interligadas, apresentando informações sobre a empresa, seus produtos em destaque e canais de atendimento ao cliente.

---

## 📁 Estrutura do Projeto

A organização dos arquivos e pastas do projeto segue a seguinte estrutura:

```text
meu-primeiro-site/
├── assets/
│   └── images/
|       └── produtos/ # Imagens ilustrativas dos produtos
│       └── favicon/
│           ├── favicon.ico
│           └── web-app-manifest-192x192.png
├── index.html          # Página principal (Home / Sobre / Destaques)
├── produtos.html       # Catálogo completo de produtos com modal interativo
├── contato.html        # Formúlário de contato, localização e FAQ
└── README.md           # Documentação do projeto
```

---

## 📄 Páginas do Site

### 1. Página Inicial (`index.html`)
- **Banner Promocional:** Destaque para ofertas de lançamento com chamadas para ação (*Call to Action*).
- **Sobre Nós:** Apresentação da empresa e seus valores fundamentais (**Inovação**, **Qualidade** e **Compromisso**).
- **Produtos em Destaque:** Exibição inicial dos principais itens (*Produto Alfa*, *Produto Beta*, *Produto Gama*).
- **Rodapé Institucional:** Links de redes sociais e dados gerais de contato.

### 2. Catálogo de Produtos (`produtos.html`)
- **Exibição em Cards:** Artigos organizados com suporte a `<figure>` e `<figcaption>` para otimização visual e SEO.
- **Carregamento Otimizado:** Uso do atributo `loading="lazy"` para alta performance no carregamento de imagens.
- **Modal Nativo HTML5:** Implementação da tag `<dialog>` para simular a ação de compra (preparado para futura integração com JavaScript e PHP).

### 3. Página de Contato (`contato.html`)
- **Formulário Interativo:** Campos estilizados para coleta de Nome, E-mail e Mensagem com validação nativa (`required`).
- **Informações Institucionais:** Endereço físico, telefone e horário de funcionamento utilizando a tag semântica `<address>`.
- **Mapa Incorporado:** Integração com *Google Maps* via `<iframe>` para navegação facilitada.
- **Seção FAQ (Perguntas Frequentes):** Acordeão interativo sem JavaScript usando a combinação de elementos `<details>` e `<summary>`.

---

## 🛠️ Recursos e Tecnologias Utilizadas

- **HTML5 Semântico:** Utilização rigorosa das tags `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<dialog>`, `<address>`, `<details>` e `<footer>` para garantia de excelente acessibilidade e indexação SEO.
- **Formulários e Inputs:** Elementos de validação nativa de tipo `email`, `text` e áreas de texto multi-linha.
- **Componentes Nativos:**
  - Janela Modal nativa via `<dialog>`.
  - Acordeão expansível nativo via `<details>/<summary>`.
- **Favicon & Web App Manifest:** Configuração de ícones de navegação e suporte inicial a PWA.

---

## 🚀 Como Executar o Projeto

1. **Clonar ou Baixar o Repositório:**
   ```bash
   git clone https://github.com/seu-usuario/meu-primeiro-site.git
   ```
2. **Abrir no Navegador:**
   Navegue até a pasta do projeto e abra o arquivo `index.html` diretamente em qualquer navegador moderno (Google Chrome, Firefox, Edge, Safari).
3. **Servidor Local (Opcional):**
   Caso esteja utilizando o Visual Studio Code, recomenda-se a extensão **Live Server** para recarregamento automático das páginas durante alterações.

---

## 🔮 Próximos Passos & Melhorias

- [ ] **Estilização CSS3:** Adicionar suporte a CSS responsivo (*Flexbox*, *CSS Grid*, variáveis de cor e tipografia moderna).
- [ ] **Interatividade JavaScript:** Expandir funcionalidades da janela modal `<dialog>` e validação de formulários.
- [ ] **Integração Backend (PHP):** Conectar o formulário de contato ao envio real de e-mails e gestão de banco de dados.
- [ ] **Responsividade Mobile:** Garantir otimização perfeita em dispositivos móveis e tablets.

---

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais como parte do meu primeiro aprendizado em desenvolvimento web. Sinta-se livre para explorar, estudar e utilizar como referência!

link para banco de imagens produtos https://pxhere.com/pt/photo/634760

---

*Desenvolvido por **Store Beautiful** &copy; 2026. Todos os direitos reservados.*