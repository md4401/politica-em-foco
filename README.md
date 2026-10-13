# Política em Foco

MVP de agregador de notícias políticas brasileiras, com interface responsiva, busca e agrupamento heurístico de manchetes sobre acontecimentos semelhantes.

## Publicação na Netlify

1. Extraia este ZIP.
2. Envie os arquivos e a pasta `netlify` para a raiz do repositório GitHub `politica-em-foco` (não envie a pasta externa `politica-em-foco`).
3. Na Netlify, use **Add new project > Import an existing project > GitHub** e selecione `politica-em-foco`.
4. Deixe o comando de build vazio e use `.` como diretório de publicação.
5. Publique. A função serverless consulta o RSS do Google Notícias quando o usuário acessa ou atualiza o feed.

## Limitações

O agrupamento é aproximado (palavras em comum nos títulos), não uma verificação editorial de identidade de eventos. Pode separar o mesmo acontecimento em grupos diferentes ou juntar assuntos relacionados. Links RSS do Google Notícias podem redirecionar ao veículo. A disponibilidade das fontes depende do RSS. Não há armazenamento persistente, monitoramento em segundo plano ou verificação de fatos.
