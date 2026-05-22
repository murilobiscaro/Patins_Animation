# Patins Animation 

Este projeto é um estudo focado exclusivamente em **CSS moderno**, explorando técnicas avançadas de transições, animações de entrada e interações visuais sem a necessidade de bibliotecas externas ou JavaScript.

link de acesso: https://murilobiscaro.github.io/Patins_Animation/

## 🚀 Destaques do Projeto

O foco principal desta aplicação é demonstrar como o CSS evoluiu para lidar com animações complexas de forma nativa e performática.

### 1. Scroll-Driven Animations
Na seção de galeria, utilizamos as propriedades `animation-timeline: view()` e `animation-range`. Isso permite que os elementos surjam na tela baseando-se no progresso do scroll do usuário, criando uma experiência fluida de "revelação" de conteúdo.

### 2. Animações de Texto (Keyframes)
O cabeçalho principal utiliza animações de ciclo infinito com `keyframes` para alternar palavras, utilizando `translateY` e cálculos de tempo precisos para criar um efeito de "carrossel vertical" de texto.

### 3. Interações e Micro-interações
- **Hover Effects:** Transições suaves de escala (`scale`) e opacidade.
- **Figcaptions:** Uso de `transform: translateY` para revelar legendas de fotos durante o hover.
- **Logos Dinâmicos:** Rotações e efeitos aplicados via CSS Nesting.

### 4. Background Gradients Animados
Implementação de gradientes lineares que se movem suavemente em loops, aumentando o dinamismo visual das seções.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica.
- **CSS3 Moderno:**
  - **Nesting:** Uso do seletor `&` para uma hierarquia de código mais limpa e legível.
  - **Variáveis (Custom Properties):** Gerenciamento centralizado de cores e tipografia.
  - **CSS Grid:** Layout complexo na galeria com `grid-template-areas`.
  - **Keyframes & Transitions:** Controle total sobre o tempo e a curva de aceleração dos movimentos.

## 📂 Estrutura de Estilos

O projeto utiliza uma arquitetura modular para os estilos:
- `global.css`: Resets e variáveis.
- `gallery.css`: Lógica de grid e animações de scroll.
- `hero.css`: Animações complexas de texto e entrada de imagens.
- `banner.css`: Animações infinitas de fundo e scroll lateral.

## 🚧 Planejamento Futuro (Roadmap)

Este projeto é uma versão inicial focada em design visual e CSS. As próximas etapas incluem:

- [ ] **Responsividade:** Adaptação do layout para dispositivos móveis e tablets (Media Queries).
- [ ] **Interatividade com JavaScript:** Adição de comportamentos dinâmicos, como filtros na galeria ou carrinho de compras funcional.
- [ ] **Acessibilidade:** Refinamento de atributos ARIA e foco de teclado.

---
Desenvolvido como parte de um estudo sobre animações web.
