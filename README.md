# CriAugu — Site institucional

Site estático (HTML/CSS/JS puro, sem build) da CriAugu — Tecnologia & Design.

## Estrutura

- `index.html` — página única, todas as seções
- `logo-wordmark.png` / `logo-wordmark-light.png` — logo para nav (dark/light)
- `logo-tagline.png` / `logo-tagline-light.png` — logo com tagline para footer (dark/light)

## Deploy

Site 100% estático — qualquer hospedagem que sirva arquivos HTML funciona.
Sem dependências, sem etapa de build.

## Tema

Light/dark via toggle no nav, com preferência salva em `localStorage` e
fallback para `prefers-color-scheme` do navegador.
