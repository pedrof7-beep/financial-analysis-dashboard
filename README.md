# Financial Performance Analysis Dashboard 2009–2023

## Resumo Executivo

Análise financeira comparativa de 12 empresas líderes em tecnologia, banca, finanças, logística, manufatura e consumo, cobrindo um período de 15 anos (2009–2023). Este projeto demonstra capacidade profissional em análise de dados, business intelligence e transformação de informação em decisões estratégicas.

Ferramentas utilizadas: Excel, Power BI, análise financeira e storytelling de negócio.

---

## Contexto e Objetivo

### Por que este projeto?
Empresas precisam entender o seu posicionamento financeiro em relação aos concorrentes e ao mercado. Este projeto analisa:
- Rentabilidade e eficiência operacional (ROE, ROA, ROI, margins)
- Saúde financeira e solvência (Debt/Equity, Current Ratio, fluxos de caixa)
- Crescimento sustentável (Revenue, Net Income, EBITDA)
- Geração de valor para acionistas (Market Cap, Free Cash Flow)

### Objetivo
Criar um dashboard executivo que permita comparar performance financeira, identificar padrões de crescimento e risco, e apoiar decisões de investimento e análise competitiva.

---

## Dataset

### Empresas Analisadas
- AAPL
- MSFT
- GOOG
- NVDA
- INTC
- PYPL
- AIG
- BCS
- AMZN
- PCG
- MCD
- SHLDQ

### Período Analisado
2009–2023

### Métricas Incluídas
- Revenue
- Gross Profit
- Net Income
- EBITDA
- ROE
- ROA
- ROI
- Net Profit Margin
- Debt/Equity Ratio
- Current Ratio
- Cash Flow from Operating
- Free Cash Flow per Share
- Market Cap
- Earnings Per Share
- Shareholder Equity
- Number of Employees
- Inflation Rate (US)

---

## Principais Insights e Descobertas

### 1. Tech domina o crescimento e a criação de valor
- NVIDIA, Microsoft, Apple e Amazon cresceram bastante em Revenue e Market Cap.
- A tecnologia mostra capacidade superior de escala e rentabilidade.

### 2. Rentabilidade não depende apenas do tamanho
- Empresas pequenas ou médias podem ter ROE muito fortes quando têm boa eficiência operacional.
- O modelo de negócios influencia mais do que o volume de vendas.

### 3. Fluxo de caixa é mais importante do que o lucro isolado
- O cash flow operacional e o free cash flow ajudam a medir consistência e sustentabilidade financeira.
- Empresas com forte crescimento nem sempre têm o melhor fluxo de caixa.

### 4. Endividamento afeta risco e estabilidade
- Debt/Equity elevado aumenta risco, principalmente em contextos de inflação e crise econômica.
- Solvência e liquidez são fundamentais para comparar empresas de sectores diferentes.

### 5. A inflação altera comparação histórica
- Comparar anos diferentes sem contexto macroeconómico pode distorcer a leitura.
- A inflação impacta custos, margens e desempenho financeiro real ao longo do tempo.

---

## Dashboard Power BI — Estrutura Recomendada

### Página 1: Executive Overview
- KPI cards principais
- Market Cap por empresa
- Revenue vs Net Income
- ROE médio

### Página 2: Company Comparison
- Gráficos comparativos por empresa
- ROE, ROA, ROI
- EBITDA e Net Margin
- Solvency e Current Ratio

### Página 3: Trend Analysis
- Evolução da receita por ano
- Lucro líquido ao longo do tempo
- Cash Flow Operating
- Impacto da inflação

### Página 4: Sector Benchmarking
- Comparação de setor por setor
- Rentabilidade média por categoria
- Market Cap e crescimento

### Página 5: Risk & Liquidity
- Debt/Equity by company
- Current Ratio by company
- Risk profile e solvência

---

## Dashboard Principal

Esta é a visualização central do projeto e representa a estrutura principal do dashboard financeiro comparativo desenvolvido em Power BI.

![Dashboard principal](dashboard/screenshots/01-comparacao-financeira.png)

### Principais conclusões do dashboard
- Microsoft apresenta o maior crescimento em receitas ao longo do período analisado.
- Apple mantém uma forte margem líquida e elevada capacidade de geração de valor.
- Google revela uma posição financeira muito sólida em termos de liquidez.
- O nível de dívida e a estrutura de capital continuam a ser indicadores fundamentais para avaliação de risco.

---

## Dashboard Screenshots

### 1. Comparação financeira
Este gráfico compara receitas e margem líquida entre Apple, Google e Microsoft ao longo dos anos, permitindo identificar padrões de crescimento e eficiência operacional.

![Comparação financeira](dashboard/screenshots/01-comparacao-financeira.png)

### 2. Evolução das receitas
A análise da receita mostra o crescimento de Apple, Google e Microsoft no período 2009–2022, destacando a diferenciação entre empresas com crescimento linear e com escalas mais agressivas.

![Evolução das receitas](dashboard/screenshots/02-evolucao-receitas.png)

### 3. Evolução da margem líquida
A margem líquida evidencia a capacidade das empresas em transformar receita em lucro, refletindo eficiência operacional, gestão de custos e competitividade no mercado.

![Evolução da margem líquida](dashboard/screenshots/03-evolucao-margem-liquida.png)

### 4. Dívida sobre capital próprio
Este indicador mede o nível de endividamento em relação ao capital próprio, sendo essencial para analisar risco financeiro e solvência das empresas.

![Dívida sobre capital próprio](dashboard/screenshots/04-divida-capital-proprio.png)

---

## Metodologia de Análise

### Etapa 1: Preparação de Dados
- Limpeza e validação dos dados
- Ajuste de valores nulos e inconsistentes
- Organização por empresa, ano e setor

### Etapa 2: Tratamento em Excel
- Pivot tables para agregação
- Cálculo de KPIs próprios
- Criação de comparações temporais e setoriais

### Etapa 3: Visualização em Power BI
- Importação dos dados tratados
- Criação de medidas DAX para KPIs
- Filtros interativos por empresa, ano e setor

### Etapa 4: Storytelling e comunicação
- Transformar números em insights claros
- Evidenciar tendências de negócio e risco
- Produzir uma narrativa profissional para RH e stakeholders

---

## Estrutura do Repositório

```text
financial-analysis-dashboard/
├── README.md
├── data/
│   └── Financial Statements.csv
├── docs/
│   ├── portfolio-presentation.md
│   └── technical-notes.md
├── dashboard/
│   ├── README.md
│   └── screenshots/
│       ├── 01-comparacao-financeira.png
│       ├── 02-evolucao-receitas.png
│       ├── 03-evolucao-margem-liquida.png
│       └── 04-divida-capital-proprio.png
└── .gitignore
```

---

## Competências Demonstradas

Este projeto permite mostrar que o candidato sabe:
- limpar e preparar dados reais;
- analisar indicadores financeiros;
- interpretar KPIs e métricas de desempenho;
- criar dashboards executivos em Power BI;
- comunicar insights de negócio com clareza;
- demonstrar raciocínio analítico e capacidade de apresentação profissional.

---

## Texto Profissional para CV / LinkedIn

Desenvolvi um dashboard financeiro comparativo de 12 empresas líderes em tecnologia, banca, finanças e consumo, cobrindo o período de 2009 a 2023. Utilizei Excel para preparar e validar os dados e Power BI para construir um dashboard executivo com indicadores financeiros-chave como revenue, EBITDA, ROE, ROA, ROI, Net Profit Margin, Debt/Equity e Free Cash Flow. O projeto demonstrou a minha capacidade de transformar dados financeiros em insights de negócio, analisar tendências temporais e comunicar resultados com clareza para stakeholders.

---

## Recomendações para apresentar o projeto

Para dar um melhor impacto no portfolio, recomenda-se:
- incluir screenshots do dashboard;
- destacar 3 a 5 principais descobertas;
- explicar quais métricas usaste e porquê;
- mostrar que o projeto foi pensado como análise executiva profissional, não apenas gráfico bonito.

---

## Autor

Pedro Fernandes  
Recém-licenciado  
Portfolio: https://github.com/pedrof7-beep

---

Este projeto foi desenvolvido como portfolio profissional em análise financeira e business intelligence.
