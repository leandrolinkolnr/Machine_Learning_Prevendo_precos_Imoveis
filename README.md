# HousePrices
Repositório para a **[competição do Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) sobre a previsão de preço das casas** na cidade de Ames, Iowa (Estados Unidos)

<img src='https://github.com/lucaslealx/HousePrices/blob/main/img/img1.png' />

O histórico dos resultados é mostrado abaixo:
<img src='https://raw.githubusercontent.com/lucaslealx/HousePrices/9301f4bc8360541493d28d524ec00a1d5b37f537/img/img2.png' />


## [Versão 1: Primeiro modelo](https://github.com/leandrolinkolnr/Projeto-completo---Machine-Learning/blob/main/Versao%201.ipynb)
- Nesta primeira etapa, realizei apenas o tratamento minimo para os valores nulos para verificar qual seria o resultado sem fazer nenhum tratamento nem engenharia dos dados, ter uma baseline.
- Para simplificar, **substitui todos os valores vazios por -1** e **trabalhei somente com valores numericos**
- Criei o modelo utilizando **3 algoritmos**: **Regressão Linear**, **Árvore de Regressão** e **KNeighborsRegressor** e **avaliamos os resultados** utilizando o **Erro médio absoluto** e o **Erro quadrático médio**.
- Obtive o **score público retornado pelo Kaggle de 0,25476**


## [Versão 2: Analise e tratamento dos dados](https://github.com/leandrolinkolnr/Projeto-completo---Machine-Learning/blob/main/Versão%202.ipynb)
- Iniciei esta versão realizando uma analise dos dados, buscando identificar a importancia de algumas variaveis para o modelo e, após isso, realizei **limpeza e tratamento dos dados**, analisando **valores vazios e informações faltantes** para escolher a melhor estratégia de tratamento:
- Os valores vazios foram tratados de forma diferenciada: quando indicavam a ausência de atributos na casa, como a falta de piscina, foram substituídos por -1, considerando o vazio como informação; em casos de verdadeira ausência de informação, foram substituídos pela média da coluna, moda ou outras abordagens apropriadas.
- Além disso, utilizei o OneHotEncoder para tratar algumas colunas textuais que eram muito importantes para o modelo e não podiam ser desconsideradas.
- Então, utilizei os mesmos modelos da etapa 1 e obtive o **score público retornado pelo Kaggle de 0.21104**


