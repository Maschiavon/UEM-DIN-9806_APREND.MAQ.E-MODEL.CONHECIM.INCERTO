# UEM-DIN-9806_APREND.MAQ.E-MODEL.CONHECIM.INCERTO
Um repositório para os trabalhos e exercicios realizados para a conclusão da disciplina aprendizado de maquina e modelagem de conhecimento incerto da Universidade estadual de Maringá (UEM)

## Trabalho 1
O trabalho consiste na modelagem de um problema com cerca de 3 a 5 variáveis,
considerando de 3 a 5 decisões diferentes, considerando os conceitos apreendidos da teoria de
decisões simples e de redes bayesianas.
Os bancos incorrem em prejuízos quando os clientes não pagam seus empréstimos em
dia. Por causa disso, todos os anos, os bancos têm prejuízos de milhões, e isso também afeta
em grande medida o crescimento econômico do país. Foi escolhida uma base de dados de
previsão de empréstimo que contém 67 mil registros fictícios, esses registros são os dados
dos supostos clientes que pediram empréstimo. O objetivo do trabalho é determinar se o
banco deverá conceder empréstimo de acordo com os dados do cliente. A base de dados
utilizada neste trabalho pode ser obtida em:

https://www.kaggle.com/datasets/hemanthsai7/loandefault

## Trabalho 2
O modelo do dataset escolhido foi o conjunto de dados de vendas da Adidas,
uma coleção de dados que inclui informações sobre as vendas de produtos da
Adidas. Esse tipo de conjunto de dados incluir detalhes como número de
unidades vendidas, receita total de vendas, local das vendas, tipo de produto
vendido, entre outras informações relevantes.

Link: https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset?
select=Adidas+US+Sales+Datasets.xlsx

Tratamento de dados base

Foi realizado um tratamento de dados no dataset da adidas para corrigir alguns
erros e para adequa-lo a um dataframe:

1 - Ler as informações do dataset, mas apenas as colunas de B até N do excel.

2 - Utilizar os valores da quarta linha para nomear as colunas.

3 - Apagar as 4 primeiras linhas.

4 - Dividir o valor da venda e o lucro por 10 pois as contas do dataset original
estão erradas.
