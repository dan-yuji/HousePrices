# HousePrices
Esse repositório foi feito para explicar o projeto do Kaggle:

## Etapa 1: Primeiro modelo
- Nesse modelo fizemos:
- Importamos o dataset de treino e verificamos as informações
- Verificamos a quantidade de valores vazios e os substituimos por -1
- Selecionamos apenas as colunas numéricas e criamos uma nova base com esses valores
- Separamos em treino e teste
- Selecionamos os algoritmos: Regressão linear, Árvore de descisão e KNeighborsRegressor
- Importamos os algoritmos e fizemos o fit com os dados de treino e a previsão para cada um dos algoritmos
- Avaliamos esses dados utilizando o erro absoluto e o quadrático
- Selecionamos a Regressão linear por te sido o algoritmo com menor erro quadrático médio
- Importamos o dataset de teste e fizemos os mesmos tratamentos anteriores
- O resultado obtido foi:
<img src="https://github.com/dan-yuji/HousePrices/blob/main/imagens/Captura%20de%20tela%202025-01-14%20011537.png" />
