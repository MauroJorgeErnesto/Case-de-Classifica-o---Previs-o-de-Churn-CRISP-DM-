Este repositório contém um projeto de classificação de Churn utilizando Regressão Logística, com um pipeline completo de análise de dados, pré-processamento e avaliação de modelo. O projeto segue a metodologia CRISP-DM, abordando desde a exploração inicial dos dados até a modelagem preditiva.

🔍 Etapas do projeto:
Carga e exploração dos dados
Leitura do dataset churn_data.xlsx
Análise exploratória com estatísticas descritivas
Visualização da distribuição do Churn
Análise de correlação entre variáveis numéricas

Pré-processamento dos dados:
Remoção da coluna customerID (irrelevante para a análise)
Identificação de colunas categóricas
Codificação One-Hot Encoding para variáveis categóricas
Combinação de variáveis numéricas e categóricas transformadas

Divisão dos dados:
Separação em variáveis independentes (X) e variável alvo (y)
Divisão do conjunto de dados em treino (80%) e teste (20%)

Treinamento do modelo:
Utilização da Regressão Logística para previsão de Churn

Avaliação do modelo:
Matriz de Confusão para visualizar erros de classificação

Cálculo de métricas de desempenho:
Acurácia
Acurácia balanceada
Precisão (Precision)
Revocação (Recall)
F1-Score
Área sob a curva ROC (ROC AUC)

📌 Tecnologias utilizadas
Linguagem: Python

Bibliotecas: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Este projeto pode ser expandido com outros modelos de machine learning, técnicas de feature engineering e ajustes de hiperparâmetros para otimizar a performance. 
