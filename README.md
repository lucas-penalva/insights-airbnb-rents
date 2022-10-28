# Aluguel de Imóveis
  
![nyc](real-state.jpg)

# Problema de Negócio:

O investidor James Bauer, gostaria de diversificar seus negócios e começar a investir em imóveis. Ele definiu que compraria imóveis na cidade de Nova York, nos Estados Unidos. Por ser um dos lugares mais caros para se morar no país, ele acredita que obterá um retorno satisfatório de seus investimentos se alugar imóveis na cidade. Como todas as suas decisões são baseadas em dados, ele quer que alguém o ajude nessa empreitada.

Ele inicialmente planeja arrendar os imóveis adquiridos e por isso definiu que usará a plataforma Airbnb para esse fim. Ele encontrou um conjunto de dados na internet contendo dados sobre o comportamento dos anfitriões e suas propriedades na cidade de Nova York.

Ele quer ajuda para descobrir as regiões com os aluguéis mais altos e os preços mais altos e quais apartamentos ou casas estão em regiões favoráveis da cidade de Nova York. Ele acredita que essas características o ajudarão a recuperar mais rapidamente o dinheiro investido na aquisição de alguns imóveis. O desafio é fazer uma análise exploratória e responder as perguntas do CEO.


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








