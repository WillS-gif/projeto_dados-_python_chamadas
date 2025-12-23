# 📊 ETL de Chamadas de Atendimento com Python

## 📌 Visão Geral
Este projeto demonstra a construção de um **pipeline ETL simples e funcional**, utilizando **Python** para gerar, transformar e analisar dados simulados de um **call center de atendimento ao cliente**.

O objetivo é simular um cenário real de dados corporativos, aplicando boas práticas de organização, tratamento de dados e geração de insights para apoio à tomada de decisão.

---

## 🎯 Objetivos do Projeto
- Simular um **dataset realista** de chamadas de atendimento  
- Aplicar o processo **ETL (Extract, Transform, Load)** com Python  
- Criar métricas e colunas derivadas relevantes para o negócio  
- Realizar análises exploratórias e visualizações  
- Demonstrar domínio de **Python para análise de dados** em nível júnior  

---

## 🗂️ Fonte dos Dados
Os dados utilizados neste projeto são **simulados**, gerados via script em Python, representando chamadas de atendimento realizadas nos **últimos 6 meses**.

Cada registro representa **uma interação de atendimento**.

---

## 🧱 Estrutura do Dataset

| Coluna | Descrição |
|------|---------|
| interaction_id | Identificador único da chamada |
| data_chamada | Data e hora da chamada |
| cliente_id | Identificador do cliente |
| canal | Canal de atendimento (Voz, Chat, WhatsApp) |
| motivo | Motivo principal do contato |
| submotivo | Detalhamento do motivo |
| duracao_segundos | Duração da chamada |
| duracao_minutos | Duração convertida em minutos |
| satisfacao | Nota de satisfação (1 a 5) |
| agente | Agente responsável |
| ano_mes | Ano e mês da chamada |
| chamada_longa | Indicador de chamadas acima de 10 minutos |

---

## 🔄 Processo ETL

### 🔹 Extract
- Geração de dados simulados com regras de negócio
- Criação de volumes realistas de chamadas
- Distribuição coerente entre motivo e submotivo

### 🔹 Transform
- Padronização de textos
- Tratamento de valores nulos
- Conversão de tipos de dados
- Criação de colunas derivadas para análise
- Simulação de problemas comuns de qualidade de dados

### 🔹 Load
- Exportação do dataset tratado em formato `.csv`
- Dados prontos para consumo analítico ou ferramentas de BI

---

## 📈 Análises Realizadas
- Volume de chamadas por motivo
- Evolução mensal de chamadas
- Satisfação média por canal de atendimento
- Identificação de chamadas longas
- Base preparada para criação de KPIs operacionais

---

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab**
- **GitHub**

---

## 🚀 Como Executar o Projeto
1. Abra o notebook no **Google Colab**
2. Execute as células na ordem
3. O dataset será gerado, tratado e analisado automaticamente
4. Os gráficos serão exibidos ao final do notebook
