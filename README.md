# 5dataglowup_11

Desafio: realizar uma análise de dados sobre futebol a partir de dados históricos disponíveis no site https://fbref.com/en/comps/24/history/Serie-A-Seasons.

Passo a passo da solução:

1. Coleta dos dados em formato .txt através da fonte.
2. Concatenação dos arquivos .txt de cada ano de campeonato em um único arquivo .txt.
3. Criação de hipóteses com base nos dados disponíveis.
4. Limpeza dos dados e derivação de atributos usando o Python.
5. Análise exploratória dos dados com o Power BI a partir de filtros interativos e segmentações.
6. Validação das hipóteses geradas na etapa 3.

Premissas:

1. A análise contempla exclusivamente o campeonato brasileiro série A.
2. A análise contempla exclusivamente as tabelas entre os anos de 2014 a 2022.
3. A análise destaca os resultados obtidos pelos clubes como mandante e como visitante.
4. A análise destaca os resultados dos 15 clubes de maior torcida do país segundo pesquisa do instituto AtlasIntel realizada em abril de 2023 (mais detalhes em: https://ge.globo.com/futebol/noticia/2023/04/25/maiores-torcidas-do-brasil-pesquisa-atlas-mostra-flamengo-corinthians-e-sao-paulo-no-top-3.ghtml).

Hipóteses relacionadas aos pontos ganhos dos clubes:

1. Todo ano o clube que mais pontua como visitante é campeão: verdadeira.
2. Todo ano o clube que mais pontua como mandante é campeão: falsa. Em 2016 o clube que mais pontuou como mandante foi o Santos (47) e o campeão foi o Palmeiras, em 2020 foi o Atlético Mineiro (46) e o campeão foi o Flamengo e em 2022 foi o Internacional (44) e o campeão foi o Palmeiras.
3. O clube que mais somou pontos no geral é o clube que mais vezes foi campeão: verdadeira. Palmeiras é o clube com mais títulos (3) e mais pontos somados no geral (595).
4. O clube que mais somou pontos como visitante é o clube que mais vezes foi campeão: verdadeira. Palmeiras é o clube com mais títulos (3) e mais pontos somados como visitante (247).

Hipóteses relacionadas às vitórias dos clubes:

5. Todo ano o clube que mais vence é campeão: verdadeira.
6. O clube que mais venceu no geral é o clube que mais vezes foi campeão: falsa. O Flamengo é o clube com mais vitórias no geral (173) e o Palmeiras é o clube com mais títulos (3).

Hipóteses relacionadas aos empates dos clubes:

7. O clube que mais empatou no geral nunca foi campeão: verdadeira. O São Paulo é o clube que mais empatou (108).
8. O clube campeão do ano nunca ficou entre os 5 clubes que mais empataram: verdadeira. O Palmeiras de 2022 foi o campeão que mais chegou próximo de ficar entre 5 clubes que mais empataram, ficando na 8ª posição.
9. O clube campeão do ano nunca empatou mais de 10 vezes: falsa. O Palmeiras em 2018 e em 2022 ultrapassou a marca, fazendo 11 e 12 empates respectivamente.

Hipóteses relacionadas aos gols dos clubes:

10. O clube com maior saldo de gols é o clube com mais títulos: falsa. O flamengo é o clube com maior saldo de gols (172) e o Palmeiras é clube com mais títulos (3).
11. O clube com mais gols marcados é o clube com mais títulos: falsa. O flamengo é o clube com mais gols marcados (534) e o Palmeiras é o clube com mais títulos (3).
