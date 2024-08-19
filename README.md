# Projeto de Engenharia de Dados

## Descrição do Projeto
Este projeto foi desenvolvido durante o Bootcamp de Engenharia de Dados, orientado pelo tutor Fernando Amaral. O objetivo foi criar um pipeline completo de dados, desde a extração e carga dos dados até a transformação e análise, utilizando ferramentas modernas de engenharia de dados.

## Objetivo
Explorar dados da empresa NovaDrive Motors e montar uma arquitetura de engenharia de dados para prover informações para a área de vendas. O projeto visa responder perguntas de negócio relacionadas a:
- Vendas por concessionárias
- Vendas por veículo
- Vendas por vendedor
- Análise de vendas ao longo do tempo

## Tecnologias Utilizadas

<p align="center">
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" alt="Python" width="100">
  <img src="https://github.com/devicons/devicon/blob/master/icons/apacheairflow/apacheairflow-original.svg" alt="Airflow" width="100">
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="100">
  <img src="https://github.com/MvJr98/images/blob/main/Snowflake.png" alt="Snowflake" width="100">
  <img src="https://github.com/MvJr98/images/blob/main/dbt.png" alt="dbt" width="100">
  <img src="https://github.com/MvJr98/images/blob/main/looker.png" alt="Dashboarding" width="100">
</p>

- **Python**: Utilizado para a ingestão dentro da DAG do Airflow.
- **Airflow**: Orquestração de workflows.
- **AWS (EC2 e Ubuntu)**: Infraestrutura na nuvem.
- **Snowflake**: Modern DataWarehouse para armazenamento e processamento de dados.
- **dbt (Data Build Tool)**: Ferramenta de transformação de dados.
- **Dashboarding**: Ferramentas de visualização de dados.

## Estrutura do Projeto
1. **Introdução**
2. **Exploração de Dados da NovaDrive Motors**
3. **Configuração do Airflow na AWS com EC2 e Ubuntu**
4. **Criação de conta e estrutura no Snowflake**
5. **Criação de DAG no Airflow e carga de dados para a área de Stage**
6. **Transformação dos dados com dbt e construção da camada analítica**
   - **Estrutura do Projeto dbt**:
     ```plaintext
     novadrive/
     ├── analysis/
     ├── dimensions/
     ├── facts/
     └── stage/
     ```
7. **Criação de Dashboards e avaliação de alternativas ao projeto**

## Resultados
- Automatização do processo de ingestão de dados para a área de Stage.
- Construção de uma camada analítica utilizando dbt.
- Geração de dashboards que proporcionam insights sobre vendas por concessionárias, veículos, vendedores e análise de vendas ao longo do tempo.
