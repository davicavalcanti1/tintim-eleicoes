# tintim · Eleições 2026

Site estático de **eleicoes.tintim.online**: o mapa de todas as seções eleitorais do país (Presidente, 1º e 2º turno) e o relatório estatístico, com dados oficiais do TSE.

- `public/`: a página, o relatório (HTML e PDF) e os dados já processados.
- `Dockerfile` e `nginx.conf`: servem a pasta `public/` com compressão.

Os dados e o método vêm do estudo `estudo-2turno-2026`. Para atualizar, rode os scripts de lá (09 a 18), que regravam a pasta `public/`.
