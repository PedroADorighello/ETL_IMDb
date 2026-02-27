# Projeto de Data Warehouse: Análise de Filmes com Baixa Avaliação (IMDb)

Pipeline de ETL completo construído no **Databricks** utilizando **PySpark** e **Delta Lake**, desenvolvido como projeto prático para a disciplina de Novas Tecnologias de Bancos de Dados da Universidade Federal de São Carlos (UFSCar - Sorocaba).

## 📋 Resumo
Este projeto implementa a arquitetura Medalhão (Bronze, Silver, Gold) para processar e analisar dados de filmes do IMDb. O fluxo abrange a ingestão de dados brutos, o enriquecimento via requisições à API OMDb, limpeza, transformação e a modelagem dimensional final em um Data Warehouse (Star Schema).

## 🛠️ Tecnologias Utilizadas
* **Plataforma:** Databricks
* **Linguagens:** Python (PySpark), SQL
* **Armazenamento:** Delta Lake
* **APIs:** OMDb API

## 🚀 Como Executar no Databricks
1. Importe o notebook `ETL_imdb.ipynb` para o seu workspace do Databricks.
2. Configure um Secret Scope chamado `chaves_api` e adicione suas chaves da OMDb.
3. Anexe o notebook a um cluster rodando Databricks Runtime com suporte a Spark 3.x.

## Diagrama do Modelo Dimensional
![Diagrama do DW](https://i.imgur.com/QYYW3Fr.png)

## Diagrama de Fluxo do Pipeline ETL
![Pipeline ETL](https://i.imgur.com/9rGWguF.png")

## 👥 Aturores
* Pedro Andrade Dorighello
* Jean Lucas Rocha dos Santos
