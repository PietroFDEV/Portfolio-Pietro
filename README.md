# Portfólio — Pietro Favoreto

Portfólio pessoal, single-file, publicado no GitHub Pages.

- **`index.html`** — o site inteiro (HTML + CSS + JS inline, sem build).
- **`src/images/work/`** — screenshots dos projetos usados nos cards de "Trabalhos".
- **`src/images/profile.png`** — foto usada na seção "Sobre".

## Como rodar localmente

Abra `index.html` no navegador, ou sirva a pasta:

```
npx serve .
```

## Editar conteúdo

- **Trabalhos:** blocos `<article class="work-item">` em `index.html`. Cada card aponta
  para um screenshot em `src/images/work/` e faz preview ao vivo via `data-preview`.
- **Atualizar screenshots:** capture o site em 1440×900 (retina 2×), redimensione para
  1600 px de largura e salve como `.jpg` (qualidade ~82) em `src/images/work/`.
- **Posts do LinkedIn:** seção `#writing`. Instruções para colar o `<iframe>` de
  "Incorporar este post" estão no comentário do HTML dessa seção.
- **Tema:** claro por padrão, com alternância manual (botão na navegação) e respeito
  ao `prefers-color-scheme`. Animações desligam com `prefers-reduced-motion`.
