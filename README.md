# Resumo diario de noticias

Site estatico para publicar o boletim diario de noticias em GitHub Pages.

## Estrutura

- `index.html`: pagina inicial com a ultima edicao e links para o historico.
- `archive/`: edicoes HTML diarias.
- `pdf/`: PDFs diarios.

## Retencao

A automacao diaria deve manter apenas os ultimos 30 dias de arquivos em `archive/` e `pdf/`.

## Publicacao

Este diretorio pode ser publicado pelo GitHub Pages usando a branch principal e a pasta `/site`.
