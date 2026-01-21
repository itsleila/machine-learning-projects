# Breast Cancer Wisconsin – Modelos de Machine Learning

Este repositório contém atividades práticas de **Machine Learning** desenvolvidas a partir do dataset **Breast Cancer Wisconsin**, amplamente utilizado para estudos de classificação e análise de dados na área da saúde.  
O objetivo principal é aplicar conceitos fundamentais e avançados do ciclo de vida de modelos de ML, comparando diferentes abordagens de classificação e regressão.

## 📊 Dataset

O dataset **Breast Cancer Wisconsin** contém atributos numéricos extraídos de exames clínicos de tumores mamários, com o objetivo de classificar tumores como:

- **Benigno**
- **Maligno**

Além disso, alguns atributos permitem tarefas de **regressão**, como a estimativa da área média do tumor.

---

## 🧪 Notebook 1 – KNN, Classificação e Regressão Linear

`knn_linearRegression_models.ipynb`

Neste notebook, são aplicados conceitos fundamentais do ciclo de vida de um modelo de Machine Learning, contemplando tanto **classificação** quanto **regressão**.

### Objetivos

- Construir um **modelo de classificação** para prever se um tumor é benigno ou maligno;
- Construir um **modelo de regressão** para estimar a área média de um tumor.

### Etapas Desenvolvidas

- Carregamento e pré-processamento dos dados;
- Treinamento e avaliação de modelos de classificação utilizando **K-Nearest Neighbors (KNN)**;
- Geração e uso de **dados sintéticos com ruído** para simular aumento da base de dados;
- Análise da performance do modelo variando o parâmetro **K**;
- Comparação da acurácia obtida com a de outros participantes;
- Discussão teórica sobre as diferenças entre **classificação** e **regressão**;
- Construção e avaliação de um modelo de **Regressão Linear**;
- Análise dos **resíduos** e das métricas estatísticas associadas ao modelo de regressão.

---

## 🔍 Notebook 2 – Comparação de Modelos de Classificação

`classification_ models_ comparison`

Neste notebook, o foco é a **avaliação avançada de desempenho** e a **comparação entre modelos de classificação**, utilizando o KNN como modelo baseline.

### Objetivos

- Implementar um novo modelo de classificação (ex.: Regressão Logística, Árvore de Decisão, Random Forest, SVM, etc.);
- Comparar o desempenho do novo modelo com o **baseline KNN**.

### Metodologia

- Estratégia de **holdout + validação cruzada**;
- Avaliação dos modelos:
  - Dentro dos folds da validação cruzada;
  - Após o **re-treinamento final** com os melhores hiperparâmetros (quando aplicável).

### Métricas Avaliadas

- Acurácia
- Precisão
- Recall
- F1-score

### Análises Realizadas

- Comparação detalhada das métricas entre os modelos;
- Discussão dos resultados obtidos nos folds e no modelo final;
- Justificativa do **modelo vencedor**, considerando:
  - Métricas mais relevantes para o problema;
  - Vantagens e limitações dos algoritmos escolhidos.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Bibliotecas:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib / Seaborn

---

## 📌 Observações

Este repositório tem fins **educacionais**, com foco na compreensão prática e teórica de modelos de Machine Learning aplicados a problemas reais de classificação e regressão.
