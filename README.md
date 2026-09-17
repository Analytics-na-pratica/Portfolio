# Portfólio — Marcelo Analytics

Site estático de uma página só (`index.html`), sem build, sem dependências pagas.

## Como colocar no ar (grátis, GitHub Pages)

1. Crie um repositório novo no GitHub (ex: `marcelo-portfolio`).
2. Suba o arquivo `index.html` para a raiz do repositório (pode adicionar depois `cv-marcelo.pdf`).
3. No repositório: **Settings → Pages → Source → Deploy from branch → `main` / `root`**.
4. Em alguns minutos o site fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.
5. (Opcional, ainda grátis) Domínio próprio: compre o domínio onde preferir e aponte o DNS para o GitHub Pages — o GitHub explica o passo a passo em Settings → Pages → Custom domain.

## O que precisa ser preenchido

- **Contato**: e-mail, LinkedIn, YouTube e GitHub já preenchidos.
- **Currículo**: o botão "Baixar currículo" aponta para `cv-marcelo.pdf` — coloque esse arquivo na mesma pasta do `index.html`.
- **Vídeos**: cada vídeo é um card com um número, um link pro YouTube e um ícone de play — sem imagem de capa (thumbnail) carregada de fora, pra não depender de conexão externa. Pra adicionar um novo, na seção `<div class="video-list">` do `index.html`, copie um bloco `<article class="video-item">...</article>` inteiro, troque o link `https://youtu.be/ID_DO_VIDEO`, o número (`01`, `02`...) nos dois lugares e o título.
- **Artigos**: a seção está deixada em aberto ("os primeiros artigos ainda estão sendo escritos"). Troque esse texto por cards de verdade quando tiver o primeiro artigo pronto. Se quiser um blog de verdade (várias páginas, não só cards), é um próximo passo separado — dá pra fazer com Markdown + GitHub Pages, sem custo.

## Estrutura

Tudo está em um único `index.html` (HTML + CSS + JS inline) — fácil de hospedar, fácil de editar, sem etapa de build.
