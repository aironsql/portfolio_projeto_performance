# 📊 Dashboard de Performance Operacional - Nexora Solutions

## 📖 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de simular um ambiente corporativo real utilizando Power BI, modelagem dimensional e análise de dados.

A empresa fictícia **Nexora Solutions** foi criada para representar uma organização que monitora a execução de processos operacionais e financeiros realizados por seus colaboradores.

O dashboard permite acompanhar indicadores de produtividade, volume de processos, esforço operacional (FTE), distribuição por áreas e desempenho individual.

---

## 🎯 Objetivo

Transformar dados operacionais em informações estratégicas, permitindo responder perguntas de negócio como:

- Qual colaborador executou mais atividades?
- Quais processos possuem maior volume?
- Qual área concentra mais demandas?
- Como o volume de processos evolui ao longo do tempo?
- Quanto esforço operacional foi consumido no período?
- Existem padrões de sazonalidade nas operações?

---

## 🏢 Contexto de Negócio

A Nexora Solutions atua em áreas operacionais e financeiras, realizando diversos processos internos diariamente.

Para apoiar a gestão, foi criado um dashboard que consolida informações de:

- Colaboradores
- Processos
- Áreas de atuação
- Calendário
- Tempos de execução

O objetivo é fornecer visibilidade sobre produtividade e eficiência operacional.

---

## 🛠️ Tecnologias Utilizadas

- Power BI
- DAX
- Power Query
- Excel
- GitHub

---

## 📂 Estrutura dos Dados

### 📌 Tabela Fato

#### `fato_processos_realizados`

Tabela responsável por armazenar os eventos operacionais.

**Principais campos:**

- Data
- Colaborador
- Processo
- Área
- Tempo médio de execução
- Quantidade de processos

### 📌 Tabelas Dimensão

#### `dim_colaboradores`

Informações dos colaboradores.

- ID
- Nome
- Cargo
- Área de atuação

#### `dim_atividades`

Catálogo de processos executados.

- ID Atividade
- Nome da Atividade
- Tipo de Atividade
- Tempo Médio

#### `dim_calendario`

Tabela calendário utilizada para análises temporais.

- Ano
- Mês
- Trimestre
- Dia da Semana
- Semana do Ano

---

## 📈 Indicadores Desenvolvidos

### KPIs

- Total de Processos
- Média de Processos por Dia
- FTE Total
- Tempo Médio de Execução
- Quantidade de Colaboradores

### Análises

- Processos mais executados
- Processos por área
- Evolução mensal
- Evolução diária
- Ranking de colaboradores
- Distribuição de FTE

---

## 🧠 Storytelling

O dashboard foi desenvolvido seguindo princípios de **Storytelling com Dados**.

A navegação foi organizada para responder uma sequência lógica de perguntas:

1. Qual o volume total da operação?
2. Quais áreas concentram mais atividades?
3. Quais processos possuem maior relevância?
4. Quem são os principais responsáveis pela execução?
5. Como a operação evolui ao longo do tempo?

Dessa forma, o usuário consegue transformar dados em informações acionáveis.

---

## 📷 Dashboard

### Visão Geral

<img width="1495" height="800" alt="image" src="https://github.com/user-attachments/assets/f3244b0a-39b4-4f99-a789-e8caaf218b0f" />


---

## 🚀 Competências Demonstradas

- Modelagem Dimensional
- Construção de Dashboards
- DAX
- Storytelling com Dados
- Indicadores Operacionais
- Visualização de Dados
- Análise Exploratória
- Boas Práticas de BI

---

## 📌 Autor

**Airon Leonardo**

🔗 LinkedIn:  
[https://www.linkedin.com/in/airon-leonardo-rufino](https://www.linkedin.com/in/aironleonardo/)

🔗 GitHub:  
https://github.com/aironsql
