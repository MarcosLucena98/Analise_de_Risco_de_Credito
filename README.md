# 📊 **Credit Risk Analysis — Data-Driven Credit Decision**
## 📌 **Visão Geral**

Este projeto simula um cenário real de concessão de crédito em um banco, utilizando dados históricos de clientes para avaliar risco de inadimplência e apoiar decisões gerenciais de política de crédito.
O foco não é apenas construir um modelo preditivo, mas transformar dados em insights acionáveis, equilibrando risco x rentabilidade, como ocorre no dia a dia de instituições financeiras.

## 🎯 **Objetivo de Negócio**

Responder à seguinte pergunta:
Como identificar clientes com maior risco de inadimplência e ajustar políticas de crédito para reduzir perdas sem comprometer significativamente a receita?

## ❓ **Perguntas que o projeto responde**
* Qual é a taxa de inadimplência da carteira?
* Quais perfis de clientes apresentam maior risco de default?
* Quais variáveis mais influenciam a inadimplência?
* Como mudanças na política de crédito impactam:
* taxa de inadimplência?
* número de clientes aprovados?
* receita esperada?

## 🗂️ **Fonte dos Dados**
**Dataset público:** [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
**Disponível em:** [Kaggle](https://www.kaggle.com/)
Contém informações demográficas, financeiras e históricas de crédito de solicitantes de empréstimo.

⚠️ Os dados são utilizados apenas para fins educacionais e de portfólio.


## 🧠 **Abordagem Analítica**
O projeto segue um pipeline completo de dados, semelhante ao ambiente corporativo:
* Entendimento do problema de negócio
* Exploração inicial com SQL
* Análise exploratória de dados (EDA) em Python
* Pré-processamento e feature engineering
* Modelagem preditiva (classificação)
* Avaliação de métricas focadas em risco
* Dashboard executivo em Power BI
* Geração de insights para tomada de decisão

## 🛠️ **Tecnologias Utilizadas**
* **Python** — tratamento de dados, EDA e modelagem
    * Pandas, NumPy, Scikit-learn
* **Power BI** — visualização e dashboard gerencial
* **Git/GitHub** — versionamento e documentação

## 📈 **Modelagem Preditiva**
* **Problema:** Classificação binária (inadimplente vs. não inadimplente)
* **Variável alvo:** loan_status
* **Modelo principal:** Regressão Logística (modelo explicável)
* **Métricas avaliadas:**
    * ROC-AUC
    * Recall da classe inadimplente
    * Matriz de confusão

O foco é maximizar a identificação de clientes de alto risco, mesmo que isso gere alguns falsos positivos, refletindo um cenário conservador de crédito.

## 📊 **Dashboard (Power BI)**
O dashboard foi desenvolvido com foco em usuários gerenciais e inclui:
* Visão geral da carteira de crédito
* Perfil de risco por segmento de cliente
* Taxa de inadimplência por tipo de empréstimo
* Simulação de políticas de crédito
* Principais fatores de risco

## 💡 **Principais Insights (exemplos)**
Clientes com histórico anterior de inadimplência apresentam risco significativamente maior.
Determinados tipos de empréstimo concentram taxas de default mais elevadas.
Ajustes no score mínimo reduzem inadimplência, porém impactam a aprovação e a receita.

## 📁 **Estrutura do Repositório**
credit_risk_project/
│
├── data/
│   └── credit_risk_dataset.csv
│
├── sql/
│   └── exploratory_analysis.sql
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_modeling.ipynb
│
├── powerbi/
│   └── credit_risk_dashboard.pbix
│
└── README.md

# 👤 **Autor**
**Marcos Lucena**
Analista de Dados | BI | Modelos Preditivos
Pós-graduação em Ciência de Dados — USP/ESALQ