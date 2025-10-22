# Página simples estática elaborada para prática. 

Esse repositório contém uma página estática (index.html) + CSS para reset estilização e assets de imagens. Essa página é intencionalmente simples, sem JS necessário. 

## O que há no repositório: 

- index.html — A página de marcação completa da landing page (hero/banner, course modules, pequenas sessões promocionais, footer).
- assets/css/reset.css — CSS Reset utilizado no projeto.
- assets/css/style.css — estilização da página
- assets/images/* — Logos e imagens ilustrativas utilizadas na página.

**Você pode acessar resultado por aqui:** <https://rug-gieri.github.io/Lading-page-DIO/>

## Seções principais em index.html
- Header banner (logo, título, descrição, CTA button)
- Course content (`#course-content`) — Descrição simples e 3 módulos
- Transform message (`#transform-world`) — Uma frase curta de slogan
- Professional challenges (`#professional-challenges`) — image + parágrafo
- Footer — DIO logo e link para dio.me

## Observações

- Não é necessário JavaScript para os recursos existentes.
- Este projeto é minimalista por natureza — perfeito para aprendizado ou para personalização.
- Acessibilidade: mantenha os atributos alt para imagens (já presentes em index.html).

Contato do Proprietário: @Rug-gieri

***
### ====== In English ======

# Lading-page-DIO

Simple static landing page built for the "Trilha de CSS - DIO" exercise.

This repository contains a single static page (index.html) plus CSS reset/style and image assets. The page is intentionally small and focused — no frameworks, no JS required.

What is in this repo
- index.html — the full landing page markup (hero/banner, course modules, small promotional sections, footer).
- assets/css/reset.css — CSS reset used by the project.
- assets/css/style.css — page styling.
- assets/images/* — logos and illustrative images used by the page.

Main sections in index.html
- Header banner (logo, title, description, CTA button)
- Course content (`#course-content`) — short description and three modules
- Transform message (`#transform-world`) — a short slogan line
- Professional challenges (`#professional-challenges`) — image + paragraph
- Footer — DIO logo and link to dio.me

Quick start (very simple)
1. Clone or download the repo.
2. Open index.html in your browser:
   - double-click index.html, or
   - serve it (optional) using a static server: `python -m http.server 8000` then visit http://localhost:8000

How to make the most common changes
- Change header text or modules: edit index.html (title, paragraphs and the `.modules-list` blocks).
- Update CTA button to link to the DIO sign-up page:
  Replace the current <button> with an anchor, for example:
  ```html
  <a class="cta" href="https://dio.me" target="_blank" rel="noopener">Quero me inscrever</a>
  ```
  Or add a small script to handle click navigation if you prefer to keep a <button>.
- Replace images: swap files in `assets/images/` and keep the filenames used in the HTML, or update the `src` paths in index.html.
- Styling: edit `assets/css/style.css`. The reset is in `assets/css/reset.css`.

Notes
- No JavaScript is necessary for the existing features.
- This project is minimal by design — perfect for learning or forking to customize.
- Accessibility: keep alt attributes for images (already present in index.html).

Contact
Owner: @Rug-gieri
