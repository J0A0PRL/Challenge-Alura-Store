Análise de Desempenho das Lojas

Este projeto tem como objetivo analisar o desempenho de quatro lojas fictícias a partir de dados de vendas, avaliando métricas como faturamento, categorias e produtos mais vendidos, satisfação dos clientes e custo médio de frete.
Ao final, a análise gera visualizações e um relatório com a recomendação de qual loja deve ser vendida pelo Sr. João.

📁 Estrutura dos Dados

Cada loja possui um arquivo .csv com as seguintes colunas:

Produto – Nome do produto vendido.

Categoria do Produto – Categoria à qual o produto pertence.

Preço – Valor da venda.

Frete – Custo do frete para o pedido.

Data da Compra – Data em que o pedido foi realizado.

Vendedor – Nome do vendedor responsável.

Local da compra – Estado de origem do cliente.

Avaliação da compra – Nota de 1 a 5 dada pelo cliente.

Tipo de pagamento – Método de pagamento utilizado.

Quantidade de parcelas – Parcelamento escolhido.

📌 Etapas da Análise

Cálculo do faturamento total de cada loja.

Contagem de produtos vendidos por categoria para identificar as mais populares.

Média das avaliações de clientes para medir satisfação.

Identificação de produtos mais e menos vendidos.

Cálculo do custo médio de frete por loja.

Geração de visualizações:

Gráfico de barras: faturamento por loja.

Gráfico de pizza: distribuição de categorias (Loja 1).

Gráfico de linha: custo médio de frete por loja.

Relatório final com recomendação sobre qual loja vender.

📊 Tecnologias Utilizadas

Python 3

Pandas – Tratamento e análise dos dados.

Matplotlib – Criação das visualizações.

📂 Saídas do Projeto

relatorio_final.md – Relatório consolidado com introdução, análises, gráficos e recomendação.

Gráficos salvos em formato .png:

faturamento_por_loja.png

categorias_loja1.png

frete_medio_por_loja.png

🏆 Principais Insights

Loja 1 apresenta maior faturamento.

Loja 4 tem menor faturamento, avaliação média mediana e mix de produtos semelhante aos concorrentes.

Loja 3 e Loja 2 se destacam pela boa avaliação de clientes.

📌 Recomendação

Com base na análise, recomenda-se a venda da Loja 4, pois apresenta o menor desempenho geral em faturamento e não se diferencia positivamente nos demais indicadores, apesar do frete médio mais baixo.
