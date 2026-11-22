# Missão Espacial

Jogo de plataforma espacial desenvolvido como uma aplicação web estática.

## Executar localmente

Abra `index.html` diretamente no navegador ou utilize qualquer servidor estático, por exemplo:

```sh
npx serve .
```

## Deploy na Vercel

O projeto não depende de frameworks ou processo de build. Importe o repositório na Vercel e mantenha estas configurações:

- Framework Preset: `Other`
- Build Command: vazio
- Output Directory: vazio
- Install Command: vazio

A Vercel servirá o `index.html` na raiz do projeto automaticamente. O arquivo `vercel.json` adiciona cabeçalhos de segurança e configura URLs sem barra final.