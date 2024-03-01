# HousePrices
Repositório para a **[competição do Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) sobre a previsão de preço das casas** na cidade de Ames, Iowa (Estados Unidos)

<img src='https://github.com/lucaslealx/HousePrices/blob/main/img/img1.png' />

O histórico dos resultados é mostrado abaixo:
<img src='https://raw.githubusercontent.com/lucaslealx/HousePrices/9301f4bc8360541493d28d524ec00a1d5b37f537/img/img2.png' />


## [Etapa 1: Primeiro modelo]([https://github.com/lucaslealx/HousePrices/blob/main/Etapa1.ipynb](https://github.com/leandrolinkolnr/Projeto-completo---Machine-Learning/blob/main/Versao%201.ipynb))
- Nesse etapa, realizei apenas o tratamento minimo para os valores nulos para verificar qual seria o resultado sem fazer nenhum tratamento nem engenharia dos dados, ter uma baseline.
- Para simplificar, **substitui todos os valores vazios por -1** e **trabalhei somente com valores numericos**
- Criei o modelo utilizando **3 algoritmos**: **Regressão Linear**, **Árvore de Regressão** e **KNeighborsRegressor** e **avaliamos os resultados** utilizando o **Erro médio absoluto** e o **Erro quadrático médio**, dando preferência ao segundo pois era o critério usando na competição
- Obtive a **pontuação retornado pelo Kaggle de 0,25476**
