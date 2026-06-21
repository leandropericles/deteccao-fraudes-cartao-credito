# Detecção de Fraudes em Transações Financeiras

Projeto de Machine Learning para identificação de fraudes em transações com cartão de crédito utilizando técnicas de classificação em bases altamente desbalanceadas.
```
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11oEYZfEFeHL6kpOROoW-2lQ4sr4eRPJB?usp=sharing)
```


## Objetivo

Desenvolver um modelo capaz de identificar transações fraudulentas minimizando falsos negativos, priorizando a métrica Recall para a classe fraude.

## Dataset

- Credit Card Fraud Detection
- 284.807 transações
- Features anonimizadas via PCA (V1–V28)
- Classe altamente desbalanceada (~0,17% de fraudes)

## Etapas do Projeto

### 1. Análise Exploratória

- Distribuição das classes
- Correlação das variáveis
- Análise temporal
- Distribuição dos valores das transações

### 2. Engenharia de Atributos

- hour_sin
- hour_cos
- is_night
- log_amount

### 3. Balanceamento

- Baseline
- RandomUnderSampler
- SMOTE

### 4. Modelagem

- Random Forest
- Class Weight Balanced

### 5. Explicabilidade

- SHAP Summary Plot
- SHAP Beeswarm
- SHAP Force Plot

## Métricas Avaliadas

- Recall
- Precision
- F1-Score
- ROC-AUC

## Tecnologias

- Python
- Pandas
- NumPy
- Scikit-Learn
- Imbalanced-Learn
- SHAP
- Matplotlib
- Seaborn
- Google Colab
