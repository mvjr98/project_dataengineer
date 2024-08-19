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

<table align="center">
  <th></th>
  <tr>
    <td align="center">
      <img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg"/>  
      <img align="left" alt="Airflow" width="30px" style="padding-right:10px;" src="https://github.com/devicons/devicon/blob/master/icons/apacheairflow/apacheairflow-original.svg"/>
      <img align="left" alt="AWS" width="30px" style="padding-right:10px;" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg"/>
      <img align="left" alt="Snowflake" width="50px" style="padding-right:10px;" src="https://github.com/MvJr98/images/blob/main/snowflake.avif"/>
      <img align="left" alt="DBT" width="30px" style="padding-right:10px;" src="https://github.com/MvJr98/images/blob/main/dbt.png"/>
      <img align="left" alt="Looker" width="30px" style="padding-right:10px;" src="https://github.com/MvJr98/images/blob/main/looker-icon.svg"/>
    </td>
  </tr>
</table>

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
