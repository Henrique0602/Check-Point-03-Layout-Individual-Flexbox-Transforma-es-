#  Check-Point 03 – Layout Individual: Flexbox & Transformações 🍷💡

##  Descrição

Este projeto é uma página única inspirada na temática da Vinharia Agnello, desenvolvida como parte do Check-point 03 da disciplina. O objetivo é aplicar o uso de Flexbox, pseudo-classes e transformações CSS para construir uma interface.

---

## Desenvolvido por

Henrique Farah Brigo

---

## Links

-  Repositório GitHub: [https://github.com/usuario/repositorio-checkpoint03](https://github.com/Henrique0602/Check-Point-03-Layout-Individual-Flexbox-Transforma-es-)
-  GitHub Pages: https://usuario.github.io/repositorio-checkpoint03

---

## Recursos Utilizados

### Flexbox

Utilizado para estruturar e alinhar elementos em:

- `.header-content` – Alinhamento horizontal do logo e menu
- `.product-cards` – Exibição dos cards de produto
- `.history-content` – Layout lado a lado de imagem e texto
- `.footer-content` – Centralização dos elementos do rodapé

### Pseudo-classes

- `:hover` nos links do menu com destaque de cor e animação
- `:hover` em botões com mudança de cor e escala
- `:hover` nos cards de produto com elevação e rotação sutil
- `::after` nos links do menu para criar uma linha animada ao passar o mouse

### Transformações CSS

- `transform: scale(1.05)` no botão `.btn` para efeito de zoom ao passar o mouse
- `transform: translateY(-10px) rotate(1deg)` nos `.card` para efeito de destaque visual no hover

---

## Estrutura do Projeto

```bash
checkpoint03-flexbox/
│
├── index.html
├── README.md
└── css/
    └── flex-style.css
