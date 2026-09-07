# 🛍️ Store Beautiful - Site Institucional & E-Commerce

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)](#-próximos-passos)
[![Licença](https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge)](#-licença)

Bem-vindo ao repositório do **Store Beautiful**! Este projeto é um website estático desenvolvido utilizando boas práticas de **HTML5 Semântico** e **CSS3 Moderno**, com foco em acessibilidade, sistema de design padronizado, responsividade para dispositivos móveis e arquitetura web limpa. O site simula uma loja de produtos de beleza e estética com catálogo, modal nativo, formulário de contato e FAQ interativo.

---

## 📌 Sumário

- [📖 Visão Geral](#-visão-geral)
- [📁 Estrutura de Arquivos](#-estrutura-de-arquivos)
- [📄 Páginas do Site e Análise Estrutural](#-páginas-do-site-e-análise-estrutural)
  - [1. Página Inicial (`index.html`)](#1-página-inicial-indexhtml)
  - [2. Catálogo de Produtos (`produtos.html`)](#2-catálogo-de-produtos-produtoshtml)
  - [3. Página de Contato (`contato.html`)](#3-página-de-contato-contatohtml)
- [🎯 Destaques Técnicos e Boas Práticas](#-destaques-técnicos-e-boas-práticas)
- [🎨 Sistema de Design & Estilização (CSS3)](#-sistema-de-design--estilização-css3)
- [📊 Tabela do Catálogo de Produtos](#-tabela-do-catálogo-de-produtos)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔮 Próximos Passos e Melhorias](#-próximos-passos-e-melhorias)
- [📷 Créditos de Mídia](#-créditos-de-mídia)
- [📝 Licença](#-licença)

---

## 📖 Visão Geral

O **Store Beautiful** foi idealizado como uma plataforma institucional e catálogo e-commerce fictício. O objetivo do projeto é demonstrar o poder e a flexibilidade das tecnologias web nativas (**HTML5 + CSS3**), utilizando recursos modernos como:
* Layouts estruturados com **Flexbox** e **CSS Grid**.
* Design System completo fundamentado em **Variáveis CSS (`:root`)**.
* Recursos interativos nativos (modal via `<dialog>` e componentes sanfona via `<details>`).
* Animações suaves (`@keyframes`), estados de foco acessíveis (`:focus-visible`) e suporte a acessibilidade motora (`prefers-reduced-motion`).

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
├── contato.html        # Formulário de atendimento, Endereço, Google Maps e FAQ
├── style.css           # Estilização global, Design System (Variáveis), Layouts e Responsividade
└── README.md           # Documentação completa do repositório