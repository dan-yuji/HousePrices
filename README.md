# HousePrices
Esse repositório foi feito para explicar o projeto do Kaggle:

## [Etapa 1: Primeiro modelo](https://github.com/dan-yuji/HousePrices/blob/main/Etapa1.ipynb)
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
- O arquivo utilizado está disponível nesse mesmo repositório através do link:
  https://github.com/dan-yuji/HousePrices/blob/main/Projeto_real_para_portifolio.ipynb

## [Etapa 2 : Tratamento de valores vazios](https://github.com/dan-yuji/HousePrices/blob/main/Etapa2.ipynb)
- Nesta etapa iniciamos o um processo de limpeza dos dados
- Analisamos valores vazios e ausênsia de informações
- Em algumas colunas, valores vazios representavam ausência dos atributos na casa, nesse caso o vazio era uma informação e não poderiamos simplesmente eliminar essas colunas
- Em outros casos onde a informação estava realmente faltando utilizamos tratamento como substituição pela média da coluna, ou pela moda
- Foi utilizado os mesmos modelos da etapa 1: [Etapa2Modelos](https://github.com/dan-yuji/HousePrices/blob/main/Etapa2Modelos.ipynb) 
- O score retornado pelo Kaggle foi: 0,1812
