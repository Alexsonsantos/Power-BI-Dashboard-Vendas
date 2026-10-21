📊 Financial Data Analysis & Power BI Dashboard

📌 Sobre o Projeto

Este projeto consiste numa solução completa de Business Intelligence desenvolvida no Power BI, focada na análise do desempenho financeiro de uma empresa multinacional. O dashboard permite acompanhar indicadores estratégicos de faturamento, vendas brutas, lucratividade, margem de lucro e impacto de concessão de descontos por segmento, produto e país.

📈 Indicadores Chave (KPIs)

Vendas Brutas: $127,93 Mi
Faturamento Total: $118,73 Mi
Lucro Total: $16,89 Mi
Margem de Lucro Média: 14,23%
Total de Descontos Concedidos: $9,21 Mi
Total de Unidades Vendidas: 1,13 Mi
Ticket Médio por Transação: $169,61 Mil
Volume de Transações: 700 vendas

🏗️ Arquitetura de Dados & Modelagem

1. ETL & Power Query

Limpeza e padronização de dados financeiros.
Modificação e estruturação do tipo de dados (moeda, percentagem, datas e inteiros).
Normalização das tabelas e criação de chaves relacionais via Merge/Append Queries.

2. Modelagem de Dados (Star Schema)

O modelo foi construído seguindo a arquitetura Esquema Estrela (Star Schema), separando a tabela de fatos das suas respetivas dimensões com relacionamentos 1:N:
Fact_Sales: Tabela fato com os registos transacionais das vendas.
Dim_Country: Informações geográficas.
Dim_Product: Detalhes dos produtos (Paseo, VTT, Velo, Amarilla, Montana, Carretera).
Dim_Segment: Segmentos de mercado (Channel Partners, Enterprise, Government, Midmarket, Small Business).
Dim_Discount_Band: Escalões de desconto (High, Medium, Low, None).

3. Cálculos & Medidas em DAX

Criadas medidas explícitas para cálculo de receita acumulada, margem operacional %, ticket médio e distribuição percentual de descontos.
Análise temporal da evolução do faturamento (2013-2014).

🖥️ Estrutura das Telas do Relatório

Desempenho Financeiro:
Visão executiva com cartões de KPIs principais.
Gráfico de evolução temporal de Faturamento vs. Vendas Brutas vs. Custos.
Análise de Quadrante: Rentabilidade (%) vs. Faturamento Total por Produto.
Tabela de desempenho por Segmento de mercado.
Análise por Produto e Geografia:
Distribuição das Vendas Brutas por País (EUA, Canadá, França, Alemanha, México).
Total de Desconto por Produto e por Faixa de Desconto (Discount Band).
Ranking de Unidades Vendidas por Produto.

Tabela de Auditoria:

Detalhamento granular de todas as transações para validação de dados e exportação.

👨‍💻 Desenvolvedor

Nome: Alexson Santos
WhatsApp: 11 96253-9565
LinkedIn: linkedin.com/in/alexson11

Projeto desenvolvido para portfólio de Engenharia e Análise de Dados.
