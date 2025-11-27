# Valuation da Totvs (TOTS3) — Bases de Dados

Este repositório reúne exclusivamente os arquivos de dados utilizados no valuation da Totvs S.A. (TOTS3), desenvolvido como monografia do curso de Ciências Econômicas (UFRJ). O código completo foi implementado em Python (Google Colab) e consome diretamente os arquivos CSV disponibilizados aqui.

## 📊 Objetivo
Fornecer as séries históricas necessárias para estimar o WACC por diferentes metodologias (semanal fixa, semanal rolante, mensal fixa e mensal rolante) e aplicar o modelo de Fluxo de Caixa Descontado (DCF) construído no Colab.

## 🗂️ Arquivos do Repositório
- **base-historica-totvs.csv** — dados históricos da Totvs (preço, liquidez e métricas de mercado).  
- **cds-brasil-5y-bps.csv** — série do CDS Brasil 5 anos (bps).  
- **projecoes-macro-boletim-focus-2020-2024.csv** — projeções macroeconômicas (Focus/BCB).  
- **series-mensais-2015-2024-totvs-ibov-selic.csv** — séries mensais (Totvs, IBOV, SELIC).  
- **series-semanais-2015-2024-totvs-ibov-selic.csv** — séries semanais (Totvs, IBOV, SELIC).  
- **totvs-debentures.csv** — base de debêntures corporativas da Totvs.

## 🧠 Metodologia do Valuation (executada no Colab)
O valuation utiliza um único FCFF projetado. A sensibilidade do valuation deriva **exclusivamente das diferentes formas de calcular o WACC**, variando:

- granularidade da série (semanal vs. mensal);  
- janelas fixas vs. rolantes;  

Cada metodologia gera um WACC distinto, e o DCF resultante é comparado ao preço de mercado na data “as-of”.

## 📎 Observações
- Todos os dados são públicos.  
- O repositório contém somente os **inputs** utilizados pelo notebook.  
- O código em Python está hospedado no Google Colab.

## 🔗 Contato
Para dúvidas ou sugestões: **alinea.souza@outlook.com.br**
