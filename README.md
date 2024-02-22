# California Housing 
Neste projeto serão realizados processos de Regressão Linear, a partir do dataset California Housing Prices que pode ser encontrado no Kaggle e disponibilizado por Cam Nugent em 2018.

# 1. Contexto
Os dados referem-se às casas encontradas em um determinado distrito da Califórnia e a algumas estatísticas resumidas sobre elas com base nos dados do censo de 1990.
## 1.1. Objetivo

A partir dos dados meu objetivo é entender a relação entre as outras variáveis e o preço mediano dos imóveis, e fazer previsões de preço a partir desses parâmetros. 
## 1.2. Variáveis

`longitude`: Uma medida do oeste de uma casa. Um valor mais negativo está mais a oeste.

`latitude`: Uma medida do norte mais alto de uma casa; um valor maior é mais ao norte.

`housing_median_age`: Idade mediana de uma casa em um bloco. Um número menor é um edifício mais recente.

`total_rooms`: Número total de salas em um bloco.

`total_bedrooms`: Número total de quartos em um bloco.

`population`: Número total de pessoas que residem em um bloco.

`households`: Número total de residências, um grupo de pessoas que moram em uma unidade residencial, para um bloco.

`median_income`: Renda mediana para famílias em um bloco de casas (medida em dezenas de milhares de dólares americanos).

`median_house_value`: Valor mediano da casa para casas em um bloco (medido em dólares americanos)

`ocean_proximity`: Próximidade do oceano.
# 2. Preparação do ambiente
## 2.1. Carregamento das bibliotecas
Carregamento das bibliotecas utilizadas inicialmente no projeto
## 2.2. Fazendo uma verificação da estrutura dos dados
Utilizando os métodos shape, head(), tail() e info() para entender os dados. 
# 3. Limpeza e manipulação dos dados
## 3.1. Tratamento de nulos e duplicados
Remoção de nulos e duplicatas no dataframe.
## 3.2. Manipulação das colunas
Transformação da coluna ocean_proximity através do método get_dummies().
# 4. Análises preliminares
## 4.1. Estatistícas descritivas
Uso do método describe()
## 4.2. Matriz de correlação
Uso do método corr() e sua visualização utilizando o seaborn
## 4.3. Comportamento da variável dependente (y)
Visualizações de boxplot, histograma e pairplot utilizando o seaborn
# 5. Modelos de Regressão Linear
## 5.1. Pré processamento
Criação dos datasets de treino e test através do train_test_split do sklearn
## 5.2. Statsmodels
Entendendo as relações entre variáveis através do Statsmodels
## 5.3. LinearRegression
Modelo de Machine Learning para previsão dos valores de median_house_values
## 5.4. Análises gráficas
Gráficos de dispersão e histograma para avaliar o modelo
