# Análise Exploratória de Dados - Catálogo da Netflix

Este repositório contém o projeto final (MVP) da disciplina de Análise Exploratória e Pré-processamento de Dados da pós em Ciência de Dados. A ideia foi usar dados reais do catálogo da Netflix para entender melhor o conteúdo disponível na plataforma.

## Objetivo do Projeto

O foco foi explorar o dataset, identificar padrões, limpar inconsistências e gerar insights úteis para a área de negócio. Um exemplo: será que a Netflix está investindo mais em filmes ou séries? Existe algum gênero subaproveitado que poderia ser explorado? Quais públicos estão sendo priorizados?

## O que foi feito

- Carga e limpeza dos dados
- Tratamento de valores ausentes
- Conversão de tipos (datas, números etc.)
- Criação de colunas auxiliares (ex: mês/ano de adição)
- Análises descritivas com gráficos
- Pré-processamento (normalização, OneHotEncoding)
- Visualizações para destacar padrões
- Conclusões com base nos dados, voltadas para uma decisão de negócio

## Dataset utilizado

Os dados vieram de um dataset público disponível no Kaggle:

Netflix Movies and TV Shows: https://www.kaggle.com/datasets/shivamb/netflix-shows

## Estrutura do projeto

mvp-netflix/
├── mvp_netflix_aepd_final.ipynb     # Versão final com análises e conclusão
├── README.md                        # Este arquivo

## Principais insights encontrados

- A maior parte do catálogo é composta por filmes, mas as séries vêm crescendo nos últimos anos.
- Os gêneros mais frequentes são Drama, Comédia e Documentários. Outros segmentos, como conteúdo infantil, ainda têm espaço para crescer.
- A classificação indicativa tende ao público geral (TV-MA, PG-13), com menos foco em conteúdos para crianças.
- Existe uma oportunidade clara de diversificação, tanto em tipo quanto em público-alvo.

## Tecnologias usadas

- Python (Pandas, Matplotlib, Seaborn, Sklearn)
- Google Colab
- Dataset do Kaggle

