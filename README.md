![Pedro Henrique — Engenharia de Dados. Python, SQL e PostgreSQL. Fluxo de ingestão, transformação e carga.](./assets/perfil.png)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro%20Henrique-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-h-a27a9a275)
![DataCamp](https://img.shields.io/badge/DataCamp-Certifica%C3%A7%C3%A3o%20em%20Engenharia%20de%20Dados-135B46?style=flat-square&logo=datacamp&logoColor=white)

### Sobre mim

Estudo Engenharia de Software na **UniEVANGÉLICA**, em Anápolis (GO), e busco estágio em **Engenharia de Dados**. Nos meus projetos, uso Python e SQL para estruturar dados semiestruturados, aplicar regras de qualidade e carregar os resultados em bancos relacionais. Minha certificação em **Engenharia de Dados pela DataCamp** complementa essa prática.

## Projeto principal

### [Pipeline ETL de contatos](https://github.com/pedrohenriqueinv/etl-contacts-pipeline)

Transforma listas de contatos em TXT em registros estruturados para consulta no PostgreSQL.

| Etapa | Implementação |
| --- | --- |
| **Ingestão** | Leitura de arquivos TXT em UTF-8, com caminho configurável. |
| **Transformação** | Parser em Python, normalização de campos, tipagem e deduplicação com Pandas. |
| **Carga** | Transação via SQLAlchemy e upsert no PostgreSQL com `ON CONFLICT (email) DO UPDATE`. |
| **Automação** | Workflow agendado no GitHub Actions, suíte pytest e logs por etapa. |

[Implementação do ETL](https://github.com/pedrohenriqueinv/etl-contacts-pipeline/blob/HEAD/pipeline/etl.py) · [Testes](https://github.com/pedrohenriqueinv/etl-contacts-pipeline/blob/HEAD/tests/test_etl.py) · [Workflow](https://github.com/pedrohenriqueinv/etl-contacts-pipeline/blob/HEAD/.github/workflows/pipeline_schedule.yml)

## Mais projetos e estudos

**[LOGOS](https://github.com/pedrohenriqueinv/LOGOS)** — plataforma de estudo com exercícios executáveis de Python/Pandas e SQL. O código roda no navegador via WebAssembly, com Pyodide para Python e PGlite para PostgreSQL.

**[Estudos de Engenharia de Dados](https://github.com/pedrohenriqueinv/data-science-studies/tree/HEAD/data-engineering)** — anotações e exercícios de ingestão, limpeza de dados, ETL/ELT, testes de integração e orquestração com Apache Airflow.

## Tecnologias

| Área | Ferramentas e práticas |
| --- | --- |
| **Linguagens e bancos** | Python · SQL · PostgreSQL · SQLite |
| **Processamento de dados** | Pandas · SQLAlchemy · normalização · deduplicação · upsert |
| **Testes e automação** | pytest · Git · GitHub Actions |
| **Em estudo** | Apache Airflow · Parquet · fundamentos de cloud |
