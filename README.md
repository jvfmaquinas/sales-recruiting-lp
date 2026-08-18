# Recrutamento — Representante Comercial · JVF Máquinas

Landing page de recrutamento para a vaga de **Representante Comercial Externo** (máquinas de linha amarela) da JVF Máquinas. Página estática de arquivo único, pronta para publicar na Vercel (ou qualquer host estático).

## Estrutura

- `index.html` — página completa e **autocontida** (HTML + CSS + JS + logo embutido como data URI). Sem build e sem dependências externas de imagem.
- `logo.png` — arquivo-fonte do logo (o logo já está embutido no `index.html`; este arquivo fica como referência/edição futura).

## Formulário

As candidaturas são enviadas via [Formspree](https://formspree.io), já configurado com o ID `xaewldzr`
(`const FORMSPREE_ID = "xaewldzr";` em `index.html`). Para trocar o destino, basta editar esse ID.

Campos capturados: nome, e-mail, WhatsApp, estado (UF), tempo de experiência em vendas B2B,
setores de experiência, tamanho da carteira ativa, link do currículo e carta de apresentação.
O currículo é enviado como **link compartilhável** (Google Drive / Dropbox / OneDrive).

E-mail alternativo de contato: `recrutamento@jvfmaquinas.com.br`.

## Deploy na Vercel

Publique a pasta como projeto estático (sem framework). A Vercel serve o `index.html` na raiz automaticamente.

## Design

Tema escuro "cósmico" com horizonte dourado, seguindo o design system da marca
(preto `#000`/`#1A1A1A`, âmbar `#FFA726`/`#FFB84D`, fonte Inter, cards glassmorphism).
