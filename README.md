# AgroRisk HLB — GitHub Pages

Esta versão mantém a ideia visual do seu site, mas troca os valores aproximados pelo conteúdo das matrizes do arquivo `Matriz de favorabilidade v5(1).xlsx` e pelas fórmulas do `Matriz de risco.pptx`.

## Arquivos
- `index.html` — aplicação web
- `matriz.json` — cópia estruturada das tabelas usadas pela aplicação

## Publicar no GitHub Pages
1. Crie um repositório no GitHub, por exemplo `matriz-risco-greening`.
2. Substitua o `index.html` antigo pelo novo `index.html`.
3. Se quiser manter os dados separados, envie também `matriz.json`.
4. Vá em **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`.
7. Salve e aguarde o GitHub publicar.

Como seu endereço atual já é `https://peeazzy.github.io/matriz-risco-greening/`, se você usar o mesmo repositório, a URL continua a mesma.

Observação: o HTML usa Tailwind, Chart.js e Google Fonts por CDN, portanto a página precisa de internet para carregar esses recursos.
