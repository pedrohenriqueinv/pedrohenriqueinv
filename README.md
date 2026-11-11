![Pedro Henrique · Engenharia de Dados. Python, SQL e PostgreSQL. Fluxo de ingestão, transformação e carga.](./assets/perfil.png)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro%20Henrique-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-h-a27a9a275)
![DataCamp](https://img.shields.io/badge/DataCamp-Data%20Engineer-135B46?style=flat-square&logo=datacamp&logoColor=white)
![Microsoft](https://img.shields.io/badge/Microsoft-Career%20Essentials%20in%20Generative%20AI-175A9E?style=flat-square&logo=microsoft&logoColor=white)
[![GitHub](https://img.shields.io/badge/GitHub-pedrohenriqueinv-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pedrohenriqueinv)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2CA5E0?style=flat-square&logo=python&logoColor=white)

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### Sobre mim

Curso **Engenharia de Software em Goiás** e busco estágio em **Engenharia de Dados**. Desenvolvo pipelines em Python e SQL, da ingestão de dados semiestruturados à validação e carga em bancos relacionais. Possuo a credencial **Data Engineer** da DataCamp e formação em IA generativa pela Microsoft e LinkedIn.

## Certificações

- **Data Engineer** · DataCamp · outubro de 2026 · ID da credencial: `ee27d588aceb7f9289663c7bb2d5e45944ba0698`
- **Career Essentials in Generative AI by Microsoft and LinkedIn** · Microsoft · julho de 2026

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

**[LOGOS](https://github.com/pedrohenriqueinv/LOGOS)** · plataforma de estudo com exercícios executáveis de Python/Pandas e SQL. O código roda no navegador via WebAssembly, com Pyodide para Python e PGlite para PostgreSQL.

**[Estudos de Engenharia de Dados](https://github.com/pedrohenriqueinv/data-science-studies/tree/HEAD/data-engineering)** · anotações e exercícios de ingestão, limpeza de dados, ETL/ELT, testes de integração e orquestração com Apache Airflow.

## AI Builder · Aplicações e orquestração de agentes

- **[LOGOS](https://github.com/pedrohenriqueinv/LOGOS)** · progressão opcional de dificuldade nos cartões de revisão com Gemini, integrada ao agendamento FSRS e aos exercícios executáveis de Python e SQL.
- **[GEMUL Professor](https://github.com/pedrohenriqueinv/acq-edu)** · integração com a API Gemini para gerar planejamentos estruturados, com revisão e edição pelo usuário antes da exportação.
- **Orquestração de agentes** · desenho fluxos com planejamento, implementação, revisão e validação. Uso roteamento por complexidade para escolher modelos e critérios de aceite para decidir quando encerrar ou repetir uma rodada.

## Stack técnica

| Área | Tecnologias e práticas |
| --- | --- |
| **Engenharia de dados** | Python · SQL · Pandas · ETL · parsing de texto · tipagem, normalização e deduplicação |
| **Bancos e acesso a dados** | PostgreSQL · SQLite · Supabase · SQLAlchemy · psycopg2 · transações e upsert |
| **Apps e frameworks** | Flask · Streamlit · TypeScript · React · Next.js · Tailwind CSS |
| **Processamento e visualização** | OpenPyXL · Recharts · Pyodide · PGlite · WebAssembly |
| **IA aplicada** | Gemini API · geração estruturada · revisão humana · orquestração de agentes · roteamento de modelos |
| **Testes e automação** | pytest · Git · GitHub Actions · workflows agendados |
| **Em estudo** | Apache Airflow · NumPy · Parquet · fundamentos de cloud |
