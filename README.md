# Análise Exploratória de Vendas de Video Games Globais

![Python Version](https://img.shields.io/badge/Python-3.11%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.x-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)

Este repositório contém uma análise exploratória de dados (EDA) sobre o dataset "Video Game Sales", originalmente obtido do [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales?resource=download). O objetivo é investigar tendências de vendas, popularidade de gêneros, plataformas e publicadoras ao longo dos anos.

## Visão Geral

A análise é conduzida utilizando Python e as bibliotecas Pandas para manipulação de dados, e Matplotlib/Seaborn para visualização. Todo o processo, desde o carregamento e limpeza dos dados até a geração de insights e conclusões, está documentado em um Jupyter Notebook (`analise_vendas_games.ipynb`).

## Objetivos da Análise

* Identificar os gêneros, plataformas e publicadoras de maior destaque no mercado de video games.
* Analisar a evolução das vendas e dos lançamentos de jogos ao longo do tempo.
* Compreender as dinâmicas e preferências de vendas nas principais regiões (América do Norte, Europa, Japão e Outras Regiões).
* Explorar correlações e padrões entre diferentes aspectos do dataset.

## Principais Etapas da Análise

1.  **Carregamento e Inspeção Inicial:** Familiarização com a estrutura, tipos de dados e estatísticas descritivas.
2.  **Limpeza e Pré-processamento:** Tratamento de valores ausentes, correção de tipos de dados, renomeação de colunas para padronização.
3.  **Análise Univariada:** Exploração individual de variáveis chave como vendas globais, ano de lançamento, gênero, plataforma e publisher.
4.  **Análise Bivariada e Multivariada:** Investigação de relações entre variáveis, como vendas por gênero em diferentes regiões, evolução de plataformas ao longo do tempo e correlações de vendas.
5.  **Interpretação de Resultados e Conclusões:** Discussão dos insights obtidos e das limitações do dataset.

## Como Visualizar a Análise

A análise completa, com todo o código, visualizações e interpretações, está disponível no Jupyter Notebook:
* [`analise_vendas_games.ipynb`](./analise_vendas_games.ipynb) (Clique para visualizar diretamente no GitHub)

## Tecnologias Utilizadas

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / JupyterLab

## Principais Insights

* A América do Norte historicamente dominou o mercado global de vendas de video games, embora a Europa também represente uma parcela significativa e estável.
* Gêneros como "Action" e "Sports" são os mais prolíficos em número de títulos, enquanto "Platform" e "Shooter" frequentemente apresentam altas médias de vendas por jogo.
* O mercado japonês exibe preferências distintas, com uma forte inclinação para o gênero "Role-Playing".
* Observou-se um pico de lançamentos de jogos no final dos anos 2000, com uma queda no volume de títulos registrados no dataset para anos posteriores a 2016, indicando uma possível incompletude do dataset para o período mais recente.
* O pico de vendas de jogos foi atigindo por entre os anos 2008 e 2009.

## Autor

* **Pedro Henrique Vital Guimarães**
* GitHub: [@PHVital](https://github.com/PHVital)
* LinkedIn: [Pedro Henrique Vital Guimarães](https://www.linkedin.com/in/pedro-henrique-vital-guimar%C3%A3es/)