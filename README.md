# Projeto: Análise e Predição de Influência no Instagram com k-Nearest Neighbors (kNN)

Este projeto implementa o algoritmo **k-Nearest Neighbors (kNN)** para prever a pontuação de influência (**Influence Score**) de influenciadores no Instagram. Usando um conjunto de dados real extraído do Kaggle, exploramos, preprocessamos e modelamos os dados para avaliar o desempenho do algoritmo e otimizamos seus hiperparâmetros para melhorar a precisão das previsões.

---

## 📋 Descrição do Projeto

1. **Definição e Preparação do Problema:**
   - Carregamento do conjunto de dados `top_insta_influencers_data.csv`.
   - Conversão da coluna `country` em faixas numéricas baseadas em continentes.

2. **Análise Exploratória:**
   - Investigação da relação entre variáveis como `followers` e `avg_likes`.
   - Análise do impacto de `60_day_eng_rate` na pontuação de influência.

3. **Implementação do Algoritmo kNN:**
   - Divisão dos dados em conjuntos de treinamento e teste.
   - Criação e treinamento do modelo kNN com validação cruzada para otimizar o valor de k.

4. **Avaliação do Modelo:**
   - Cálculo de métricas como MAE, MSE e RMSE.
   - Validação cruzada para garantir generalização do modelo.

5. **Visualização dos Resultados:**
   - Geração de gráficos para análise de correlações e desempenho.

---

## 📂 Conjunto de Dados

O conjunto de dados utilizado é o `top_insta_influencers_data.csv`, que contém informações sobre os principais influenciadores do Instagram, incluindo:

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

---

## ⚙️ Instalação

1. Certifique-se de que as bibliotecas necessárias estejam instaladas.
2. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/instagram-knn.git
   cd instagram-knn
3. Execute o notebook `knn_instagram.ipynb`.
   
### Pré-requisitos

- **Python 3.8+**
- Bibliotecas necessárias: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.


## Resultados

📊 Resultados Obtidos
- Melhor valor de k (encontrado por GridSearchCV): 18
### **Métricas finais:**
- MAE (Erro Absoluto Médio): 4.64
- MSE (Erro Quadrático Médio): 29.91
- RMSE (Raiz do Erro Quadrático Médio): 5.47
- Além disso, gráficos de correlação, análise de engajamento e validação cruzada estão disponíveis no notebook.

## 👥 Autores e Contribuidores
- Iaquine Santos da Silva: Desenvolvimento do modelo, análise de dados e visualizações.
- Renato Gomez de Sousa: Desenvolvimento do modelo, análise de dados e visualizações.
