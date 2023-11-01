# Detecção de Fraudes em Cartões de Crédito usando PCA e K-Means

Este projeto teve como objetivo a detecção de fraudes em um dataset de transações de cartões de crédito utilizando PCA e K-Means. O dataset utilizado foi obtido a partir do [link do Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata).

## Passos do Projeto

1. **Análise Exploratória de Dados (EDA):**
   - Foram realizadas análises estatísticas e gráficas para compreender a distribuição das transações e padrões nos dados.
     
2. **Aplicação do PCA:**
   - A técnica de PCA foi aplicada para reduzir a dimensionalidade do conjunto de características.
   - Isso permitiu capturar a variância dos dados em um espaço de menor dimensão, enquanto ainda mantinha informações significativas.

3. **Treinamento do Modelo K-Means:**
   - Utilizando o conjunto de características resultante do PCA, o algoritmo K-Means foi aplicado para agrupar as transações em clusters.
   - O número de clusters foi definido de acordo com critérios como a análise do "Knee Point" e do diagrama representando a árvore de clusters.
