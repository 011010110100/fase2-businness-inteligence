# Fase 2 - Business Intelligence e Analytics

Projeto desenvolvido para a disciplina de **Business Intelligence e Analytics**, com foco na análise de **cancelamentos de reservas hoteleiras**.

O projeto utiliza o conjunto de dados **Hotel Booking Demand**, contendo registros de reservas de um hotel urbano e de um resort.

## Objetivo

Analisar características associadas aos cancelamentos de reservas e desenvolver uma solução de Business Intelligence e Analytics que permita:

* acompanhar indicadores relacionados às reservas;
* identificar padrões associados aos cancelamentos;
* analisar as hipóteses definidas no projeto;
* criar um modelo preditivo para classificação de cancelamentos;
* apresentar os principais resultados em um dashboard.

## Tecnologias utilizadas

* Python
* Google Colab
* Pandas
* Scikit-learn
* Power BI
* GitHub

## Etapas desenvolvidas

O projeto foi dividido nas seguintes etapas:

1. Carregamento e compreensão da base de dados.
2. Avaliação da qualidade e limpeza dos dados.
3. Transformação e preparação das variáveis.
4. Construção dos principais KPIs.
5. Análises descritivas e diagnósticas.
6. Avaliação das hipóteses do projeto.
7. Desenvolvimento de um modelo preditivo com Regressão Logística.
8. Avaliação do modelo utilizando métricas de classificação.
9. Construção de dashboard no Power BI.

## Principais KPIs

* Total de reservas
* Reservas canceladas
* Reservas não canceladas
* Taxa de cancelamento

## Principais resultados

### Antecedência da reserva

Foi observado aumento da taxa de cancelamento conforme a antecedência da reserva:

* 0 a 30 dias: **18,58%**
* 31 a 90 dias: **37,73%**
* 91 a 180 dias: **44,74%**
* Mais de 180 dias: **57,01%**

### Recorrência do hóspede

Hóspedes recorrentes apresentaram menor taxa de cancelamento:

* Não recorrentes: **37,81%**
* Recorrentes: **14,65%**

### Modelo preditivo

Foi utilizado um modelo de **Regressão Logística** para prever o cancelamento das reservas.

Resultados obtidos:

* Acurácia: **79,62%**
* Precisão: **84,98%**
* Recall: **54,71%**
* F1-score: **66,56%**

## Dashboard

O dashboard foi desenvolvido no **Power BI Desktop** e apresenta os principais indicadores e análises do projeto, incluindo:

* KPIs gerais;
* taxa de cancelamento por antecedência;
* comparação entre hóspedes recorrentes e não recorrentes;
* distribuição das reservas por status e tipo de hotel;
* filtros por hotel e ano.

O arquivo do dashboard está disponível no repositório em:

`power_BI.pbix`

## Arquivos do repositório

* `Fase2_BI_Hotel_Bookings.ipynb` — preparação dos dados, análises e modelo preditivo.
* `hotel_bookings.csv` — conjunto de dados utilizado no projeto.
* `power_BI.pbix` — dashboard desenvolvido no Power BI.
* `README.md` — documentação resumida do projeto.
