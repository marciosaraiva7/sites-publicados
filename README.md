# sites-publicados

Páginas estáticas publicadas. A [página de gerenciamento](./index.html) lista cada site, permite escolher o que remover e faz **commit automático em `main`** na exclusão — o deploy do GitHub Pages sobe em seguida.

## Como excluir

1. Abra a página de gerenciamento (GitHub Pages ou `index.html` local).
2. Cole um [token GitHub](https://github.com/settings/personal-access-tokens/new) com **Contents: Read and write** neste repositório. O token fica só no navegador.
3. Marque as páginas, ou use **Excluir últimos 10** para limpar as mais recentes de uma vez.
4. Confirme. A exclusão vira um commit em `main`.
