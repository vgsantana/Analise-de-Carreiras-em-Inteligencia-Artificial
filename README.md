# 📊 Análise de Carreiras em Inteligência Artificial

Este projeto analisa o mercado global de carreiras relacionadas à Inteligência Artificial, com foco em entender os fatores que influenciam salários, oportunidades, crescimento profissional e satisfação dos profissionais.

A análise foi construída a partir de um dataset global, explorando variáveis como país, experiência, indústria, adoção de IA e indicadores de mercado.

# 🎯 Objetivo

# Responder às principais perguntas:

A adoção de IA influencia os salários?

Onde estão as melhores oportunidades?

Como ocorre o crescimento de carreira?

Quais segmentos são mais promissores?

O que impacta a satisfação dos profissionais?

# 🛠️ Tecnologias Utilizadas

Python (PySpark)

Spark SQL

Pandas

Looker Studio

# 🔄 Metodologia do Projeto

O desenvolvimento do projeto seguiu um fluxo estruturado de análise de dados:

Ingestão de dados
Importação do dataset em ambiente distribuído utilizando PySpark

Filtragem e seleção
Escolha das variáveis mais relevantes para análise, com foco em carreiras relacionadas à IA

Exploração de dados (EDA)
Análise exploratória para identificação de padrões, tendências e relações entre variáveis

Visualização exploratória
Criação de gráficos utilizando Matplotlib e Seaborn para validação de hipóteses iniciais

Pipeline de dados
Estruturação e preparação dos dados para consumo analítico utilizando Google BigQuery

Dashboard final
Construção do dashboard interativo no Looker Studio, organizado em múltiplas páginas analíticas



# 📊 Estrutura do Dashboard

# 🟡 1. Visão Geral

Salário médio anual

Satisfação média

Adoção média de IA

Risco de automação

Densidade de profissionais por país

👉 Objetivo: apresentar uma visão macro do cenário global

# 🟠 2. Onde Estão as Melhores Oportunidades

Salário vs adoção de IA por país

Custo de vida por país

Salário real vs dificuldade de contratação

👉 Objetivo: identificar os países mais atrativos considerando múltiplos fatores

# 🔵 3. Crescimento de Carreira

Salário por tempo de experiência

Evolução salarial ao longo dos anos

Crescimento de carreira vs velocidade de promoção

👉 Objetivo: entender progressão profissional e evolução salarial

# 🟣 4. Segmentos

Salário + bônus por indústria

Dificuldade de contratacão por indústria

Demanda de habilidade x salário por indústria

Demanda de habilidade por tamanho da empresa

👉 Objetivo: analisar diferenças entre indústrias e estruturas organizacionais

# 🟢 5. Influência na Satisfação dos Profissionais

Satisfação por país

Relação entre salário, work-life balance e satisfação

Satisfação vs risco de layoff e tamanho da empresa

👉 Objetivo: identificar os fatores que impactam a percepção dos profissionais

# ⚫ 6. Conclusões

Síntese dos principais achados do projeto

👉 Objetivo: transformar dados em decisões e aprendizados

🔍 Principais Insights
💰 Salários

A adoção de IA não apresentou impacto direto consistente nos salários

Experiência, localização e indústria são os principais fatores

🌎 Oportunidades

Países com mercados mais estruturados concentram melhores salários

O salário real (ajustado ao custo de vida) altera significativamente o ranking de oportunidades

📈 Crescimento

Forte relação entre experiência e aumento salarial

Indícios de desaceleração salarial recente

🏭 Segmentos

Indústrias específicas apresentam maior compensação e demanda

Diferenças relevantes entre setores e tamanhos de empresa

😊 Satisfação

Fortemente ligada a salário e localização

Baixa influência direta do modelo de trabalho

🚀 Conclusão

A análise mostra que o mercado de carreiras em IA é influenciado por fatores estruturais mais amplos do que apenas a adoção de tecnologia. Experiência, localização e dinâmica de mercado continuam sendo os principais determinantes.

O projeto reforça a importância de uma análise contextualizada, capaz de transformar dados em insights relevantes para tomada de decisão.
