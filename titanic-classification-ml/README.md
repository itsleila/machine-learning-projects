# 🚢 Titanic Machine Learning

Este repositório contém um estudo de **Machine Learning supervisionado** utilizando o dataset clássico do **Titanic,** com o objetivo de comparar diferentes modelos de classificação e avaliar seus desempenhos por meio de métricas estatísticas.

## 📊 Dataset

O conjunto de dados utilizado é o _Titanic Dataset_, contendo informações sobre passageiros e o rótulo de sobrevivência.
Antes da modelagem, os dados passam por etapas de:

- limpeza e remoção de valores ausentes
- codificação de variáveis categóricas
- separação em conjuntos de treino e teste

## 📘 Notebooks

### 1. Árvore de Decisão

`titanic_decision_tree_models.ipynb`

- Aplicação de um modelo de Árvore de Decisão
- Avaliação com diferentes profundidades
- Visualização das árvores geradas
- Métricas: acurácia, precision, recall e F1-score
- Análise do impacto da profundidade no desempenho do modelo

### 2. Support Vector Machine (SVM)

`titanic_svm_models.ipynb`

- Aplicação de SVM com diferentes kernels:
  - Linear
  - RBF
  - Sigmoid
- Uso de normalização dos dados
- Ajuste de hiperparâmetros com GridSearchCV
- Comparação de desempenho entre os kernels
- Métricas: acurácia, precision, recall e F1-score

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🎯 Objetivo

O objetivo deste projeto é aplicar e comparar técnicas clássicas de Machine Learning, reforçando conceitos como:

- pré-processamento de dados
- escolha de modelos
- ajuste de hiperparâmetros
- interpretação de métricas de avaliação
