Previsão de Preços de Casas: Análise e Modelagem de Regressão
Este projeto é uma análise completa de um conjunto de dados de imóveis, com o objetivo de construir um modelo de Machine Learning capaz de prever os preços de casas com base em suas características. O projeto foi desenvolvido com base na competição House Prices do Kaggle e aborda um problema de regressão.

Ferramentas e Bibliotecas Utilizadas
Linguagem de Programação: Python

Análise de Dados: Pandas, NumPy

Visualização: Matplotlib, Seaborn

Modelagem de Machine Learning: Scikit-learn, XGBoost

Metodologia e Técnicas Aplicadas
Análise e Pré-processamento de Dados:

Identificação e tratamento de valores ausentes de forma estratégica.

Conversão de variáveis categóricas em numéricas (One-Hot Encoding).

Aplicação de transformação logarítmica (np.log1p) na variável-alvo (SalePrice) para normalizar sua distribuição e otimizar o desempenho do modelo.

Engenharia de Features:

Criação de novas variáveis, como a área total (TotalSF), combinando features existentes para capturar informações mais relevantes para o modelo.

Modelagem e Comparação de Modelos:

Regressão Linear: Utilização de um modelo de regressão linear como baseline.

XGBoost: Treinamento de um modelo XGBoost, conhecido por sua alta performance em dados tabulares.

Otimização de Hiperparâmetros:

Emprego da técnica Grid Search para testar diferentes combinações de hiperparâmetros no modelo XGBoost, visando encontrar a configuração ideal para o problema.

Resultados e Conclusão
O modelo de Regressão Linear, após a aplicação da transformação logarítmica, demonstrou ser o mais eficaz para este conjunto de dados, alcançando o melhor resultado com um RMSE de $22.948. Este projeto reforça a importância das etapas de pré-processamento e análise exploratória de dados, que muitas vezes têm um impacto maior no desempenho do modelo do que a complexidade do algoritmo em si.
