[![Formação Rocketseat](https://img.shields.io/badge/Forma%C3%A7%C3%A3o-Rocketseat-8257e5?style=for-the-badge&logo=rocketseat)](https://www.rocketseat.com.br/)

---

#  TehcNews - Portal de notícias

Este é um projeto de estudo desenvolvido para praticar conceitos avançados de **CSS Grid** e a metodologia **Utility CSS**. O objetivo principal foi construir a interface de um portal de notícias focado em tecnologia.

---

## Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

- **HTML5**: Estruturação semântica de conteúdo.
- **CSS3**: Estilização avançada.
  - **CSS Grid Layout**: Para o posicionamento complexo dos elementos.
  - **CSS Variables**: Para facilitar a manutenção de cores e tipografia.
  - **Utility-first CSS**: Aplicação de classes utilitárias para agilizar a estilização.
- **Google Fonts**: fonte "Archivo".

## Conceitos Estudados

O desenvolvimento desta página permitiu o aprofundamento em tópicos fundamentais do Front-end:

* **Grid Template Areas**: Organização do layout principal dividindo em áreas nomeadas (`featured`, `weekly`, `ai`, `aside`).
* **Utility CSS**: Criação de classes globais e reutilizáveis (ex: `.grid`, `.gap-16`, `.text-lg`) para evitar repetição de código.
* **Nesting CSS**: Uso da sintaxe moderna de aninhamento nativo do CSS para uma escrita mais limpa.
* **Design de Interfaces**: Trabalhando com hierarquia visual, sobreposição de texto em imagens (`figcaption` com gradiente) e alinhamento de componentes de navegação.

---

## Variáveis de estilização
```css
:root {
    --brand-color-light:#60A5FA;
    --brand-color-dark:#1D4ED8;
    --bg-color:#0F172A;
    --stroke-color:#1E293B;
    --text-color-primary: #F1F5FF;
    --text-color-secondary: #CBD5E1;

    --font-family: "Archivo", sans-serif;
    --h1: 800 24px/135% var(--font-family); 
    --h2: 800 16px/140% var(--font-family); 
    --h3: 800 14px/140% var(--font-family);
    --text-span: 600 14px/145% var(--font-family);
    --text: 400 16px/140% var(--font-family); 
    --text-sm: 400 14px/160% var(--font-family); 
}

```

Este projeto foi desenvolvido para fins de estudo.

Feito com 💜 pela **[Rocketseat](https://www.rocketseat.com.br/)**.
