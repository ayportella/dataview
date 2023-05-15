# Projeto de Visualização de Dados em Looker - Case Fórmula 1

## Sobre o projeto:
- Este projeto fez parte de um Desafio chamado '#5DataGlowUp' que acontece no Linkedin, promovido por Heitor Sasaki, que ocorreu em abril de 2023;
- Os dados correspondem a corridas que aconteceram entre 1950 a 2019, com informações como ano de ocorrência, rodada, nome da corrida, data, circuito, número, posição, nome e sobrenome dos pilotos, nacionalidade, escuderia, resultados em grids e voltas, entre outros;
- Houve a manipulação da tabela original, com criação de uma nova coluna chamada 'Country' a partir de 'nationality' para ser usada em um mapa interativo. Além disso, a tabela .xls foi transformada em arquivo .csv e incorporada ao Looker Data Studio;
![alt text](https://github.com/ayportella/dataviz/blob/main/03_looker_formula1/tabela_dados.PNG)
- Os resultados eram livres, e eu decidi usar um dashboard para extrair insights em relação à história da Fórmula 1;
- Foram adicionados como controles de 'drop-down list' as informações de 'season' e 'round', a fim de filtrar por esses dois tipos de informação.

## Principais insights percebidos:
- O número de escuderias era relativamente pequeno, menos de dez entre as décadas de 50 a início de 70, com um salto significativo no final de 70 até início de 90, e estabilidade em 10 escuderias nos anos seguintes;
- A maioria dos pilotos era dos países do Reino Unido, França e Itália em 1950. O Brasil já entra em 1951, com Chico Landi pela Ferrari, e pilotos americanos e argentinos também mostram essa disseminação do interesse pelo esporte além dos europeus;
- Os anos entre 1988 a 1993 eram os mais assistidos pelos brasileiros com as disputas entre Sena e Prost;
- O ano de 1994 foi conhecido como o annus horribilis da F1 devido ao número de acidentes e mortes, e houve uma importante demanda de maior sofisticação dos veículos e maior uso da tecnologia, e apenas as maiores escuderias se mantiveram na F1;
- A variação do número de voltas entre os anos 1950 a 1960 era impressionante, podendo chegar a 200 voltas (!). Isto é relacionado às 500 milhas de Indianápolis! Desde então elas não fazem mais parte da Fórmula 1, e sim da Indy.

## Dashboard
[Você pode ver o dashboard aqui!](https://lookerstudio.google.com/u/0/reporting/7fa0f42c-f92e-4537-b232-8f6f8813b61c/page/ZZaOD)

![alt text](https://github.com/ayportella/projects_dataviz/blob/main/03_looker_formula1/dashboard_formula1.PNG)



