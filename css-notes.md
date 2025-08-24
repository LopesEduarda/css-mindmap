CSS (Cascading Style Sheets)
│
├── 📦 Box Model (tudo é uma caixa)
│     ├── Content → conteúdo (texto, imagem)
│     ├── Padding → espaço interno (entre conteúdo e borda)
│     ├── Border → borda da caixa
│     └── Margin → espaço externo (afasta caixas)
│
├── 🎯 Seletores
│     ├── Tag → p, div, h1
│     ├── Classe → .nome
│     ├── ID → #nome
│     ├── Descendente → div p
│     └── Universal → *
│
├── 📏 Propriedades
│     ├── Dimensões → width, height, max/min
│     ├── Espaçamento → margin, padding
│     ├── Cores → color, background
│     ├── Texto → font-size, font-family, text-align
│     ├── Bordas → border, border-radius
│     └── Sombras → box-shadow, text-shadow
│
├── 📐 Layout
│     ├── Display
│     │    ├── block
│     │    ├── inline
│     │    ├── inline-block
│     │    ├── flex
│     │    ├── grid
│     │    └── none
│     ├── Position
│     │    ├── static
│     │    ├── relative
│     │    ├── absolute
│     │    ├── fixed
│     │    └── sticky
│     └── Z-index → ordem de camadas
│
├── ⚡ Flexbox
│     ├── display: flex
│     ├── flex-direction (row/column)
│     ├── justify-content (eixo principal)
│     ├── align-items (eixo cruzado)
│     └── gap (espaço entre itens)
│
├── 🟦 Grid
│     ├── display: grid
│     ├── grid-template-columns
│     ├── grid-template-rows
│     └── gap
│
├── 📱 Responsividade
│     ├── Media Queries → @media (max-width: 768px) { ... }
│     ├── Unidades relativas
│     │    ├── % → relativo ao pai
│     │    ├── em/rem → relativo à fonte
│     │    ├── vw/vh → relativo à tela
│     │    └── px → fixo
│
├── 🎭 Pseudo-classes e Pseudo-elementos
│     ├── :hover → quando passa o mouse
│     ├── :focus → quando selecionado
│     ├── :nth-child(n) → filho específico
│     ├── ::before → insere antes
│     └── ::after → insere depois
│
├── 🎬 Transições & Animações
│     ├── transition → suaviza mudanças
│     └── @keyframes → cria animações
│
└── ✅ Boas Práticas
      ├── Pense em containers (pai/filhos)
      ├── Use margin fora e padding dentro
      ├── Prefira classes a IDs
      ├── Estruture: Reset → Layout → Componentes → Detalhes
      └── Pense mobile-first (responsividade)
