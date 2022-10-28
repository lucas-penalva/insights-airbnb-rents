# Aluguel de Imóveis
  
![nyc](real-state.jpg)

# Problema de Negócio:


## I. Atributos

<table style="width:100%">
<tr><th>Atributos</th><th>Descrição</th></tr>
<tr><td>Store</td><td>ID exclusivo para cada loja</td></tr>
<tr><td>Sales</td><td>quantidade de vendas por dia</td></tr>
<tr><td>Customers</td><td>número de clientes no dia</td></tr>
<tr><td>Open</td><td>indica se a loja está aberta ou fechada, 0 = closed, 1 = open</td></tr>
<tr><td>StateHoliday</td><td>indica feriado estadual. Normalmente todas as lojas, com poucas exceções, estão fechadas nos feriados estaduais. Observe que todas as escolas estão fechadas nos feriados e fins de semana. a = feriado, b = feriado da páscoa, c = natal, 0 = nenhum</td></tr>
<tr><td>SchoolHoliday</td><td>indica feriado escolar</td></tr>
<tr><td>StoreType</td><td>diferencia entre 4 modelos de loja diferentes: a, b, c, d</td></tr>
<tr><td>Assortment</td><td>descreve um nível de sortimento: a = básico, b = extra, c = estendido</td></tr>
<tr><td>CompetitionDistance</td><td>indica a distância em metros do concorrente mais próximo</td></tr>
<tr><td>CompetitionOpenSince[Month/Year]</td><td>mês e ano em que abriu o concorrente mais próximo</td></tr>
<tr><td>Promo</td><td>indica se está ocorrendo alguma promoção na loja</td></tr>
<tr><td>Promo2</td><td>é uma promoção contínua e consecutiva para algumas lojas: 0 = a loja não está participando, 1 = a loja está participando</td></tr>
<tr><td>Promo2Since[Year/Week]</td><td>indica mês e ano que a loja iniciou a Promo2</td></tr>
<tr><td>PromoInterval</td><td>indica os intervalos consecutivos em que a Promo2 é iniciada</td></tr>
</table>

# Premissas de Negócio:

* 
* 

# Estratégia de Negócio:

Etapa 01 - Entedimento do problema de négocio.

Etapa 02 - Download do dataset diretamente do <a href="https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data" target="_blank">Kaggle</a>.

Etapa 03 - Limpeza do conjunto de dados removendo valores discrepantes, valores NA e recursos desnecessários.

Etapa 04 - Exploração os dados (EDA) para criar hipóteses, gerar insights e validá-los.

# Insights:


# Resultados:



# Conclusões:








