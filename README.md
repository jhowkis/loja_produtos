# 🛍️ Store Beautiful - E-Commerce & Site Institucional

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)](#-próximos-passos)
[![Licença](https://img.shields.io/badge/Licença-MIT-blue?style=for-the-badge)](#-licença)

Bem-vindo ao repositório do **Store Beautiful**! Este projeto é um website institucional e e-commerce estático moderno desenvolvido com **HTML5**, **CSS3**, **Bootstrap 5** e **Bootstrap Icons**. O site foi redesenhado para garantir total responsividade, excelente usabilidade em dispositivos móveis e uma navegação intuitiva para produtos de beleza, perfumaria e estética.

---

## 📌 Sumário

- [📖 Visão Geral](#-visão-geral)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [📄 Documentação das Páginas](#-documentação-das-páginas)
  - [1. Página Inicial (`index.html`)](#1-página-inicial-indexhtml)
  - [2. Catálogo de Produtos (`produtos.html`)](#2-catálogo-de-produtos-produtoshtml)
  - [3. Contato e Feedback (`contato.html` / `feedback.html`)](#3-contato-e-feedback-contatohtml--feedbackhtml)
- [🛠️ Tecnologias e Recursos Utilizados](#️-tecnologias-e-recursos-utilizados)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔮 Próximos Passos](#-próximos-passos)
- [📷 Créditos de Mídia](#-créditos-de-mídia)
- [📝 Licença](#-licença)

---

## 📖 Visão Geral

O **Store Beautiful** foi idealizado para entregar uma experiência de compras fluida e elegante. Com a recente integração do **Bootstrap 5**, a plataforma conta com uma _Navbar_ fixa com indicador de carrinho, carrosséis interativos, _grid system_ dinâmico para listagem de produtos com paginação via JavaScript e um fluxo completo de envio de mensagens com página de confirmação (_Feedback_).

---

## 📁 Estrutura do Projeto

```text
loja_produtos/
├── assets/
│   ├── css/
│   │   └── style.css            # Estilos customizados, tema de cores e variáveis
│   └── images/
│       ├── favicon/             # Favicon e ícones do manifesto web
│       └── produtos/            # Imagens dos produtos do catálogo
├── database/                    # Estrutura e scripts de banco de dados (futuro)
├── php/                         # Lógica e scripts backend (futuro)
├── index.html                   # Página principal (Hero, Destaques e Carrossel)
├── produtos.html                # Catálogo completo com paginação dinâmica em JS
├── contato.html                 # Formulário de atendimento e mapa interativo
├── feedback.html                # Tela de confirmação de envio de mensagem
├── sobrenos.html                # Página institucional "Quem Somos"
├── politica_privacidade.html    # Termos de privacidade
├── termos_uso.html              # Termos e condições de uso
├── trocas_devolucoes.html       # Política de trocas e devoluções
└── README.md                    # Documentação oficial do repositório
```

---

## 📄 Documentação das Páginas

### 1. Página Inicial (`index.html`)

Ponto de entrada da loja, focado em conversão e apresentação da marca:

- **Barra de Navegação (`<nav>`):** _Navbar_ responsiva do Bootstrap com menu _collapsible_ para dispositivos móveis, links de navegação principal, opções de login/cadastro e ícone de carrinho de compras com _badge_ de notificação numerada.
- **Hero Banner:** Seção principal com chamada de destaque (_Call to Action_), aplicando gradientes suaves e botão de direcionamento para o catálogo.
- **Seção Institucional:** Breve introdução sobre a essência da marca e botão para a página _Quem Somos_.
- **Carrossel de Produtos em Destaque:** Implementação do componente _Carousel_ do Bootstrap com controles manuais e indicadores, exibindo coleções de produtos organizadas em cartões (_Cards_) responsivos.
- **Rodapé Institucional (`<footer>`):** Organizado em colunas com informações de contato, links institucionais e atalhos para redes sociais.

### 2. Catálogo de Produtos (`produtos.html`)

Exibe o catálogo completo da loja com uma experiência limpa e organizada:

- **Grid System Responsivo:** Layout adaptável em colunas (`row-cols-1 row-cols-sm-2 row-cols-md-3 row-cols-lg-5 g-4`) que ajusta automaticamente a quantidade de itens por linha de acordo com o tamanho da tela.
- **Cards de Produtos:** Cada item exibe imagem com formato proporcional (`object-fit-cover`), _badge_ indicando a categoria (Perfumaria, Skincare, Maquiagem, Acessórios), título, descrição sucinta, preço destacado e botão de compra.
- **Paginação Dinâmica em JavaScript:** Sistema no próprio cliente que divide os 20 produtos cadastrados em páginas de 10 itens cada. A alternância entre páginas atualiza a exibição em tempo real e realiza rolagens suaves (_smooth scroll_) para o topo da lista.

### 3. Contato e Feedback (`contato.html` / `feedback.html`)

Fluxo completo de comunicação do cliente com a loja:

- **Formulário de Atendimento (`contato.html`):** Coleta de dados como Nome Completo, E-mail, Telefone, Assunto (_dropdown_) e Mensagem com campos obrigatórios (`required`).
- **Cards Informativos:** Exibição clara de e-mail de suporte, telefone comercial e horários de atendimento.
- **Localização Interativa:** Incorporação do Google Maps via `<iframe>` responsivo (`ratio ratio-16x9`), indicando o endereço físico da loja.
- **Página de Confirmação (`feedback.html`):** Após o envio do formulário, o usuário é redirecionado para a tela de _Feedback_, que exibe uma mensagem amigável de sucesso com ícone do Bootstrap Icons, aviso de envio de e-mail de confirmação e botões para retornar à página principal ou continuar navegando pelos produtos.

---

## 🛠️ Tecnologias e Recursos Utilizados

- [**HTML5**](https://developer.mozilla.org/pt-BR/docs/Web/HTML): Marcação semântica e acessível.
- [**CSS3**](https://developer.mozilla.org/pt-BR/docs/Web/CSS): Estilização customizada e variáveis globais em `assets/css/style.css`.
- [**Bootstrap 5.3**](https://getbootstrap.com/): Framework Front-End para _Grid System_, utilitários, carrossel, modal, formulários e navegação responsiva.
- [**Bootstrap Icons**](https://icons.getbootstrap.com/): Conjunto de ícones vetoriais modernos para os botões, navegação, suporte e tela de feedback.
- **JavaScript (Vanilla):** Manipulação do DOM para a paginação de produtos sem necessidade de dependências externas.

---

## 🚀 Como Executar o Projeto

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/jhowkis/loja_produtos.git
   ```
2. **Acessar o diretório:**
   ```bash
   cd loja_produtos
   ```
3. **Executar o projeto:**
   - Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
   - _Dica:_ Utilize a extensão **Live Server** do VS Code para visualizar atualizações em tempo real durante o desenvolvimento.
4. **Demonstração Online (GitHub Pages):**
   - [Acessar Store Beautiful no GitHub Pages](https://jhowkis.github.io/loja_produtos/)

---

## 🔮 Próximos Passos

- [x] Integração do framework **Bootstrap 5** para responsividade total.
- [x] Implementação da paginação dinâmica de produtos via JavaScript.
- [x] Criação da página de retorno/feedback de formulário (`feedback.html`).
- [ ] Implementação de carrinho de compras interativo em JavaScript (adicionar/remover itens e calcular total).
- [ ] Conexão da lógica de backend com PHP e banco de dados para processamento real do formulário de contato e catálogo de produtos.

---

## 📷 Créditos de Mídia

- **Imagens dos Produtos:** Obtidas gratuitamente em alta resolução no [PxHere](https://pxhere.com) e no [Pexels](https://www.pexels.com/pt-br/).
- **Ícones e Favicon:** Estruturado com suporte a Web App Manifest e [Bootstrap Icons](https://icons.getbootstrap.com/).

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

---

_Desenvolvido por **Store Beautiful** &copy; 2026. Todos os direitos reservados._
