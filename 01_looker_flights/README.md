# Projeto de Visualização de Dados em Looker - Case Flights

## Sobre o projeto:
- O presente projeto  é resultado de um dos módulos do curso Analista de Dados da Escola Britânica de Artes Criativas e Tecnologia (EBAC), e corresponde ao meu primeiro dashboard criado, a fim de entender como criar métricas e criar dashboards no Looker;  
- A base de dados escolhida foi o dataset 'flights' da biblioteca Seaborn, que informa o número de passageiros em voos de avião que ocorreram entre 1949 a 1960 separados por mês;
-  Também houve uma etapa de extração, transformação e carregamento (ETL) em linguagem Python a fim de preparar os dados para serem entendidos pela plataforma escolhida, o Looker Data Studio. A coluna 'month' teve de ser transformada de texto para número, e houve a criação de uma chave temporal no formato YYYY-MM através da concatenação das colunas 'year' e 'month';
-  Foi criado um campo parse_date para a coluna 'year-month' no Looker;
- A métrica criada foi a soma de passageiros em um determinado ano.

## Principais insights percebidos:
- Na área do gráfico, é possível perceber uma distribuição bimodal em cada ano, com pico no mês de março e outro maior no mês de julho, e um pico discreto no mês de dezembro. Isso é relacionado a períodos de feriados e férias, em que há maior demanda de vôos.
- Também é evidente que o número de passageiros foi crescente a cada ano, o que indica que houve maior possibilidade de acesso das pessoas a custear passagens de avião.

## Dashboard:
[Você pode manipular o dashboard aqui!](https://colab.research.google.com/drive/1Co6RQ6QxAPodyYcmIru0dPqQQYxDfWHY?usp=sharing)

![alt text](https://github.com/ayportella/dataviz/blob/main/01_looker_flights/flights_dashboard_image.PNG)
