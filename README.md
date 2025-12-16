<div align="center">
  <img src="./assets/Logo.svg" alt="Logo Alura Books" width="300">

  <h1>📚 Alura Books</h1>

  <p>
    Front-end de um e-commerce de livros de tecnologia, com foco em responsividade e interatividade via CSS.
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
    <img src="https://img.shields.io/badge/SwiperJS-6332F6?style=for-the-badge&logo=swiper&logoColor=white">
    <img src="https://img.shields.io/badge/Mobile%20First-orange?style=for-the-badge">
  </p>
</div>

---

## 📖 Descrição

O **Alura Books** é uma página de e-commerce responsiva dedicada à venda de livros de desenvolvimento e tecnologia, desenvolvida através da formação front-end da Alura!

O projeto foi desenvolvido com foco na metodologia **Mobile First**, garantindo uma experiência fluida em dispositivos móveis e adaptando-se para telas maiores (tablets e desktops) através de Media Queries.

...

---

## 🛠️ Funcionalidades e Diferenciais Técnicos

Este projeto destaca o uso avançado de CSS e HTML semântico:

### 1. Menu Hambúrguer "Pure CSS" (Checkbox Hack)
A interatividade de abrir e fechar o menu no mobile foi construída **sem JavaScript**.
Utilizou-se a técnica do `input type="checkbox"` oculto, onde o estado `:checked` altera a visibilidade da lista de menu através de seletores de irmãos (`~`).

### 2. Integração com SwiperJS
Implementação da biblioteca SwiperJS para criação do carrossel de livros ("Lançamentos" e "Mais Vendidos"), com configuração de paginação e navegação responsiva.

### 3. Arquitetura CSS Modular
O CSS foi dividido em múltiplos arquivos para facilitar a manutenção e escalabilidade, importados no arquivo principal.

### 4. Layout Responsivo
Mobile: Layout verticalizado, menu oculto (hambúrguer) e elementos ocupando 100% da largura;

Tablet/Desktop (min-width: 1024px): Menu expandido, grid de produtos ajustado e tipografia escalada.

### 5. Design System
O projeto utiliza variáveis CSS (:root) para manter a consistência visual;

Cores: Uso de degradês (var(--azul-degrade)) e paleta definida (Laranja, Azul e Branco);

Tipografia: Família Poppins para textos principais e Josefin Sans para títulos, importadas via Google Fonts.

## 💻 Desenvolvido por:

**Gabriela Prestes Farias**
| Desenvolvedora Front-end |
**LinkedIn:** https://www.linkedin.com/in/gabriela-prestes-farias/

