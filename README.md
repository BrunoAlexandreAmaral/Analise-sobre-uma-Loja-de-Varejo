# Analise-sobre-uma-Loja-de-Varejo

# Analise-sobre-uma-Loja-de-Varejo
O Dataset de varejo que temos em maõs é composto por infomrações de vendas de uma loja virtual,que atua em todo territorio nacional,vendendo produtos diferentes departaemntos.alem disso, a loja atua em diferentes canais de vendas, como marketplace,loja propia, entre outros.

A base de vendas contém informações sobre cada venda realizada pela loja, possivelmente com dados como:
  ID da venda
  Data e hora da venda
  Valor total da venda
  Valor do frete
  ID do cliente
  ID do vendedor
  ID do produto
  Quantidade vendida
  Preço unitário
  Descontos
  Impostos

Premissas de negocio:
Ao analisar os dados, é importante ter em mente que existem, algumas premissas de negocio que devem ser consideradas.A primeira delas é, devido a um erro no sistema, algumas compras nao possuem informações de UF. Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul(MS).A segunda premissa é que o preço final de um produto nao pode ser maior que o preço com frete.

Metricas:
Com base nesse contexto e nas premissas de negocio podemos avaliar as seguintes metricas:

1.Departamentos mais vendidos:Analisando os dados de Vendas, podemos identificar quais sao os departamentos mais populares entre os clientes.Essa informação pode ser util para entender quais são os produtos mais procurados pelo cliente e ajustar a estrategia de venda da loja em conformidade.

2.Media de preço com frete por nome de Departamento: Para entender o Comportamento de preço por departamento, podemos calcular a media de preço com frete por nome de departamento.Essa metrica pode ajudar a Identificar quais são os departamentos mais rentaveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.

3.Quantidade de vendas por Mes: Analisando a qauntidade de vendas relaizada em cada mês,podemos identificar sazonalidade no comportamento de compras dos clientes e planejar campanhas de marketing especificas para cada periodo

4.Media de renda para cada tipo de canal de venda: Identificar a media de renda dos clientes em diferentes canais de venda pode ajudar a loja a adaptar a estrategia de marketing e vedas para cada publico -alvo.

5.Media de idade de Clientes por bandeira:Saber a faixa etaria dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar a estrategia de vendas para atender melhor cada publico

Variaveis importantes:
Depart_ven = depatamento com maior vendas
media_preco_DP= media de preço por departamento
Quand_mes = mes com mais quantidade de vendas
media_renda = media de renda para cada tipo de canal de compra
media_idade_bandeira = media de idade por bandeira
