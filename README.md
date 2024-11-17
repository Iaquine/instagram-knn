# Projeto kNN para Dados do Instagram

## Descrição

Este projeto implementa o algoritmo k-Nearest Neighbors (kNN) para prever a pontuação de influência de influenciadores do Instagram. O projeto inclui as seguintes etapas:

1. **Definição e Preparação do Problema:**
    - Carregamento do conjunto de dados 'top_insta_influencers_data.csv'.
    - Conversão da coluna 'country' em faixas numéricas baseadas em continentes.
2. **Análise Exploratória:**
    - Investigação da relação entre 'followers' e 'avg_likes'.
    - Análise do impacto de '60_day_eng_rate' na pontuação de influência.
3. **Implementação do Algoritmo kNN:**
    - Divisão dos dados em conjuntos de treinamento e teste.
    - Criação e treinamento do modelo kNN com k=5.
4. **Avaliação do Modelo:**
    - Cálculo da acurácia do modelo.
    - Geração do relatório de classificação.
5. **Visualização dos Resultados:**
    - Criação de gráficos para visualizar o desempenho do modelo.

## Conjunto de Dados

O conjunto de dados usado neste projeto é 'top_insta_influencers_data.csv', que contém informações sobre os principais influenciadores do Instagram, incluindo:

- `rank`: Classificação do influenciador.
- `channel_info`: Nome do canal/influenciador.
- `influence_score`: Pontuação de influência.
- `posts`: Número de posts.
- `followers`: Número de seguidores.
- `avg_likes`: Média de curtidas por post.
- `60_day_eng_rate`: Taxa de engajamento em 60 dias.
- `new_post_avg_like`: Média de curtidas em novos posts.
- `total_likes`: Total de curtidas.
- `country`: País do influenciador.

## Dependências

- pandas
- scikit-learn
- matplotlib

## Como Executar

1. Certifique-se de que as bibliotecas necessárias estejam instaladas.
2. Execute o notebook `knn_instagram.ipynb`.

## Resultados

Os resultados da execução do código, incluindo a acurácia do modelo e o relatório de classificação, serão exibidos no notebook.
