# 🛒 Classificação de Clientes por Canal de Compra

Este projeto tem como objetivo aplicar modelos de **Machine Learning** para classificar clientes de uma distribuidora de produtos alimentícios de acordo com o **canal de compra**:

- **Horeca** (Hotel / Restaurante / Café)
- **Retail** (Varejo)

## 📊 Dataset

A base utilizada contém informações de gastos anuais dos clientes em diferentes categorias de produtos, como:

- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicatessen  
  Além das variáveis **Channel** (variável alvo) e **Region**.

## 🧹 Pré-processamento

As seguintes etapas foram realizadas:

- Remoção de observações com dados ausentes
- Recodificação da variável alvo (`Channel`):
  - 1 → Horeca
  - 0 → Retail
- Codificação da variável categórica `Region`
- Separação dos dados em treino (75%) e teste (25%)
- Escalonamento das variáveis numéricas

## 🤖 Modelos Utilizados

Foram treinados e avaliados dois modelos de classificação, utilizando configurações padrão:

- **Random Forest**
- **XGBoost**

## 📈 Avaliação

Os modelos foram avaliados com as seguintes métricas:

- Acurácia
- Precision
- Recall
- F1-score
- Matriz de confusão
