# 🏗️ Arquitetura Medalha de Dados - E-commerce Databricks

Implementação completa de um Data Lakehouse no Databricks seguindo a arquitetura Medalha (Bronze → Silver → Gold) para processamento ETL de dados de e-commerce. Atividade desenvolvida durante participação no Rocket Lab REC 26.1 da visagio.  

---

## 📋 Descrição do Projeto

Este projeto estrutura os dados de um grande e-commerce através de um pipeline ETL robusto na plataforma Databricks. Os dados brutos são extraídos de múltiplas fontes, transformados em camadas de dados progressivamente refinadas e, finalmente, disponibilizados para análise e geração de KPIs de negócio.

### 🎯 Objetivo

- Extrair dados de múltiplas fontes
- Implementar processo ETL completo
- Estruturar dados em camadas (Bronze → Silver → Gold)
- Gerar Data Marts analíticos
- Extrair e disponibilizar KPIs de negócio

---

## 📁 Estrutura do Projeto

```
.
├── Atividade_land_to_bronze.ipynb      # Carregamento (Landing → Bronze)
├── Atividade_bronze_to_silver.ipynb    # Transformação (Bronze → Silver)
├── Atividade_silver_to_gold.ipynb      # Agregação (Silver → Gold)
├── Job_arq_medalhao.yaml               # Configuração do Job Databricks
└── Execucao_sucesso_job.jpeg           # Print da Execução do Job
```
