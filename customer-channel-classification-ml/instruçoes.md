Carregue a base que está neste [link](https://raw.githubusercontent.com/cassiusf/datasets/main/customers_data.csv): Faça a importação diretamente do Github e armazene os dados em um dataframe único. Se desejar, utilize a biblioteca Pandas.

Após carregar a base, execute as seguintes operações:

- Avalie a existência de dados ausentes e elimine estas observações.
- Recodifique a variável alvo, utilizando (1) para Horeca (Hotel/Restaurant/Café) e (0) para Retail channel.
- Separe o dataframe resultante em Treino-Teste, utilizando a proporção 75-25%.

A partir do dataframe totalmente ajustado, aplique um modelo Random Forest, utilizando as opções padrão do classificador.

1. Apresente as métricas acurácia, precision, recall e F1-score deste modelo. Apresente também a matriz de confusão resultante do processo de treinamento.
2. Execute o algoritmo XGBoost na mesma base (após os ajustes pedidos), utilizando apenas as configurações padrão do modelo. Apresente as mesmas métricas da questão acima.
3. Qual modelo você utilizaria, a partir dos resultados da execução dos dois modelos? Justifique sua resposta.
