# Recrutamento — Representante Comercial · JVF Máquinas

Landing page de recrutamento para a vaga de **Representante Comercial Externo** (máquinas de linha amarela) da JVF Máquinas. Página estática de arquivo único, pronta para publicar na Vercel (ou qualquer host estático).

## Estrutura

- `index.html` — página completa (HTML + CSS + JS inline). Sem build.
- `logo.png` — logo da JVF (usado no header e footer, e como favicon).

## Formulário

As candidaturas são enviadas via [Formspree](https://formspree.io). Antes de publicar:

1. Crie um formulário no Formspree e copie o ID (ex.: `xldjabcd`).
2. Em `index.html`, localize `const FORMSPREE_ID = "SEU_FORMSPREE_ID";` e substitua pelo seu ID.

Enquanto o ID não for configurado, o formulário roda em **modo demo** (mostra a mensagem de sucesso sem enviar de fato).

Campos capturados: nome, e-mail, WhatsApp, estado (UF), tempo de experiência em vendas B2B,
setores de experiência, tamanho da carteira ativa, link do currículo e carta de apresentação.
O currículo é enviado como **link compartilhável** (Google Drive / Dropbox / OneDrive).

E-mail alternativo de contato: `recrutamento@jvfmaquinas.com.br`.

## Deploy na Vercel

Publique a pasta como projeto estático (sem framework). A Vercel serve o `index.html` na raiz automaticamente.

## Design

Tema escuro "cósmico" com horizonte dourado, seguindo o design system da marca
(preto `#000`/`#1A1A1A`, âmbar `#FFA726`/`#FFB84D`, fonte Inter, cards glassmorphism).
