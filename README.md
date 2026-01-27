# Projetos de Machine Learning

Repositório com **projetos de Machine Learning** com foco em **classificação, regressão, avaliação de modelos e comparação de algoritmos**.  
Os projetos foram desenvolvidos em Python, utilizando datasets clássicos e problemas próximos de cenários reais, com objetivo **educacional e prático**.

## Projetos Disponíveis

### 🐧 Classificação de Pinguins

Projeto introdutório de Machine Learning utilizando o dataset **Palmer Penguins**, com foco na compreensão progressiva dos conceitos fundamentais da área.

**Principais tópicos abordados:**

- Conceitos básicos de Machine Learning
- Tipos de aprendizado
- Preparação e análise de dados
- Construção e avaliação de modelos com Scikit-learn
- Classificação binária:
  - Adelie vs. outras espécies
  - Gentoo vs. outras espécies
- Reflexão crítica sobre desafios em projetos de ML

---

### 🚢 Titanic Machine Learning

Estudo de **Machine Learning supervisionado** utilizando o dataset do Titanic, com foco na **comparação de modelos de classificação** e análise de métricas.

**Etapas principais:**

- Limpeza e tratamento de dados
- Codificação de variáveis categóricas
- Separação em conjuntos de treino e teste

**Modelos explorados:**

- Árvore de Decisão
  - Análise de diferentes profundidades
  - Visualização das árvores
- Support Vector Machine (SVM)
  - Kernels: Linear, RBF e Sigmoid
  - Normalização dos dados
  - Ajuste de hiperparâmetros com GridSearchCV

**Métricas utilizadas:**

- Acurácia
- Precision
- Recall
- F1-score

---

### 🛒 Classificação de Clientes por Canal de Compra

Projeto de classificação de clientes de uma distribuidora de alimentos, com o objetivo de prever o **canal de compra**:

- Horeca (Hotel / Restaurante / Café)
- Retail (Varejo)

**Dataset:**

- Gastos anuais dos clientes em diferentes categorias de produtos
- Variáveis: Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicatessen
- Variáveis adicionais: Channel (alvo) e Region

**Pré-processamento:**

- Tratamento de dados ausentes
- Recodificação da variável alvo
- Codificação de variáveis categóricas
- Divisão treino/teste
- Escalonamento das variáveis numéricas

**Modelos utilizados:**

- Random Forest
- XGBoost

**Avaliação:**

- Acurácia
- Precision
- Recall
- F1-score
- Matriz de confusão

---

### 🧬 Breast Cancer Wisconsin

Projeto baseado no dataset **Breast Cancer Wisconsin**, voltado para problemas de **classificação e regressão** na área da saúde.

#### Notebook 1 – KNN, Classificação e Regressão Linear

- Classificação de tumores: Benigno vs. Maligno
- Regressão para estimar a área média do tumor
- Uso de KNN para classificação
- Análise do impacto do parâmetro K
- Geração de dados sintéticos com ruído
- Construção e avaliação de modelo de Regressão Linear
- Análise de resíduos e métricas estatísticas

#### Notebook 2 – Comparação de Modelos de Classificação

- KNN como modelo baseline
- Implementação de Regressão Logística
- Estratégia de holdout + validação cruzada
- Comparação detalhada entre modelos

**Métricas avaliadas:**

- Acurácia
- Precisão
- Recall
- F1-score

---

## Tecnologias Utilizadas:

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Objetivo do Repositório

Consolidar o aprendizado prático em **Machine Learning**, explorando desde conceitos introdutórios até técnicas mais avançadas de avaliação, comparação de modelos e seleção de features, servindo como material de estudo.

_Todos os projetos possuem **fins educacionais**._
