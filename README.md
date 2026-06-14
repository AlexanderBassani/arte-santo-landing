# ArteSanto 2026 — Site

Site do festival **ArteSanto 2026** — "Onde o folclore vira arte".
Feira de artesanato e economia criativa do Espírito Santo · 08 a 13 de setembro · Praça do Papa, Vitória/ES.

## Estrutura

```
site/
├── index.html          ← página principal (versão atual)
├── index v2.html       ← mesma da index.html (cópia de trabalho)
├── index v1.html       ← versão 1 antiga (layout azul)
├── img/                ← banners, logos, fotos e recortes
├── fonts/              ← Bronova, Mark My Words, Montserrat
└── banners/preview.html ← galeria dos banners (celular / tablet / desktop)
```

## Como abrir

Abra o `index.html` em qualquer navegador. Tudo é local — não precisa de servidor.
As fontes e imagens são carregadas das pastas `fonts/` e `img/`.

## Publicar no GitHub

```bash
git init
git add .
git commit -m "ArteSanto 2026 — site"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git
git push -u origin main
```

A cada alteração:

```bash
git add .
git commit -m "descrição da mudança"
git push
```

### Hospedar grátis (GitHub Pages)
No repositório: **Settings → Pages → Branch: main → /(root) → Save**.
O site fica disponível em `https://SEU-USUARIO.github.io/SEU-REPO/site/`.

---
© 2026 ArteSanto · Todos os direitos reservados.
