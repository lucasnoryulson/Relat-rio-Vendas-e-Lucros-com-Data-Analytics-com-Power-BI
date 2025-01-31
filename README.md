📊 Projeto de Data Analytics com Power BI

📌 Descrição do Projeto

Este projeto tem como objetivo analisar e visualizar dados de vendas e unidades vendidas utilizando o Power BI. O relatório foi estruturado para apresentar insights relevantes para a tomada de decisões estratégicas.

🎯 Objetivos

Criar páginas de detalhes conforme especificado no desafio.

Organizar os visuais de maneira clara e intuitiva.

Implementar medidas DAX necessárias para os cálculos.

Criar dashboards interativos para fácil consumo de informações.

📂 Estrutura do Relatório

O relatório é composto por múltiplas páginas que apresentam diferentes análises sobre as vendas, produtos e segmentos.

🔹 1. Página Inicial - Report Financeiro

📌 Introdução ao dashboard, destacando:

Indicadores-chave: Total de Vendas, Unidades Vendidas, Lucro, Descontos.

Filtro de Data para seleção de período.

Resumo das vendas por período.

Análise de Vendas por Segmento e Produto.

🔹 2. Análise de Categorias e Clusters

📌 Visão sobre a segmentação das vendas, incluindo:

Gráfico Sankey: Distribuição das vendas por continente e ano.

Gráfico de dispersão: Relação entre unidades vendidas, vendas e lucro por clusters.

Análise de vendas por segmento e mês.

🔹 3. Análise de Vendas e Unidades Vendidas

📌 Análise detalhada do desempenho das vendas:

Top 3 países com mais unidades vendidas.

Evolução das vendas e unidades vendidas por mês.

Gráficos de barras e histogramas para detalhamento das unidades vendidas.

🔹 4. Análise dos Top 3 Produtos

📌 Identificação dos produtos mais vendidos:

Gráfico de dispersão: Evolução das vendas por produto e mês.

Top 3 produtos mais vendidos e soma das vendas por país.

Comparação de receitas entre os produtos mais populares.

🔹 5. Detalhes de Vendas

📌 Comparação entre diferentes períodos e métricas:

Análise por semestre e trimestre.

Histograma de unidades vendidas.

Unidades vendidas por produto.

🛠️ Medidas DAX Criadas

Cálculo de Total Sales (SUM(financials[Sales]))

Cálculo de Unidades Vendidas (SUM(financials[Units Sold]))

Cálculo de Top 3 Produtos (TOPN(3, ALL(financials[Product]), [Total Sales]))

Cálculo de Lucro por Cluster (CALCULATE([Total Profit], financials[Cluster] = "ClusterX"))

📌 Principais Insights

✅ Os produtos do segmento Government lideram as vendas.
✅ Os meses de outubro, novembro e dezembro apresentam picos de vendas.
✅ Os clusters mostram padrões distintos de unidades vendidas e lucro.
✅ Os países com maior volume de vendas são EUA, Canadá e França.

📊 Tecnologias Utilizadas

Power BI

DAX (Data Analysis Expressions)

Modelagem de Dados

🚀 Como Usar o Relatório

Abra o arquivo .pbix no Power BI Desktop.

Utilize os segmentadores de dados para explorar os filtros interativos.

Navegue entre as páginas para visualizar as diferentes análises.

