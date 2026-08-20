# Olá, eu sou o Leonardo Santos Medeiros

**Desenvolvedor Backend e IA Aplicada | Líder Técnico**

> Construo produtos que colocam LLM em produção de verdade, com atenção a integração, custo de
> inferência e ao que a operação consegue sustentar.

## Sobre mim

Comecei em dados (SQL, ETL e BI) e migrei para desenvolvimento backend e IA aplicada. Hoje
trabalho na entrega de produtos de IA em ambiente governamental, incluindo um servidor de LLM
on-premise em produção para análise de documentos confidenciais. Lidero tecnicamente uma equipe
de 4 a 5 pessoas, com revisão de código, desdobramento técnico e mentoria de júniores e
estagiários.

Venho da licenciatura em matemática e da sala de aula, o que explica a parte do trabalho que mais
gosto: destravar gente.

**No que trabalho:** backend em Python, integração com APIs de LLM, automação de processos,
pipelines de dados e a parte chata e necessária de colocar tudo isso no ar.

**No que estou me aprofundando:** avaliação de qualidade de saída de LLM, observabilidade de
aplicação e Go.

## Experiência

| Período | Cargo | Empresa |
|---|---|---|
| 07/2025 a atual | Líder Técnico e Desenvolvedor Backend/IA | Logiks, cliente Ministério dos Transportes |
| 09/2024 a 06/2025 | Analista de Dados | FPA, Frente Parlamentar da Agropecuária |
| 08/2021 a 03/2024 | Analista de Dados Júnior | Vert Integradora de TI |
| 01/2014 a 03/2021 | Professor de Matemática | Centro Educacional Maria Rosa Molas |

## Stack

**Domínio:** Python, SQL, FastAPI, PostgreSQL, Docker e Docker Compose, ETL, BigQuery, Looker
Studio, SAS (Enterprise Guide e Visual Analytics), n8n, Git

**Experiência em projeto:** Go, Kafka, React, Cloudflare, CI/CD, Prometheus e Grafana, APIs de LLM
(Gemini e Ollama), MCP, API do SharePoint

## Projetos

### [Avaliador de Currículos](https://www.avaliadorcurriculos.com.br)
Produto próprio em produção, em beta com acesso controlado.

Triagem de currículos assistida por IA. O recrutador cadastra a vaga com seus requisitos, envia
currículos em lote e recebe resumo estruturado e nota comparativa gerada por LLM. Por decisão de
produto o sistema não elimina candidatos: a decisão final é sempre do recrutador
(human-in-the-loop).

* **Arquitetura:** FastAPI, React e PostgreSQL, com fila Kafka para processamento assíncrono em
  lote, orquestrados em Docker Compose.
* **Camada de IA:** prompt autoral para a comparação entre vaga e currículo, com contrato de
  entrada e saída em JSON estruturado.
* **Custo de inferência como requisito:** migração de inferência local (Ollama) para API
  gerenciada (Gemini), contabilização de consumo de tokens na plataforma e quota por plano.
* **Infraestrutura:** self-hosted em VM Linux, exposta via Cloudflare com HTTPS, CI/CD para build
  e deploy e monitoramento de containers com Prometheus e Grafana.

### Outros projetos

| Projeto | Descrição | Stack |
|---|---|---|
| **Contabilidade Inteligente** | Chatbot que responde perguntas em linguagem natural sobre uma base contábil conectada. | Python, SQLite, LLM |
| **ControleGastosApp** | Aplicativo de controle de gastos pessoais. | C#, .NET MAUI, XAML |
| **Dashboard Petshop** | Análise de negócio do setor pet com dados de 2018 a 2020. | Power BI, DAX |

### Projetos de estudo

Repositórios mantidos como registro de aprendizado durante a pós-graduação, não como trabalho de
produção: `machine-learning-project`, `Projeto_fraude` e `Calculadora 3.0`.

## Formação

| Curso | Instituição | Ano |
|---|---|---|
| Pós-graduação em Ciência de Dados e Analytics Avançado | Anhanguera | 2026 |
| Pós-graduação em Inteligência Artificial e Machine Learning | Anhanguera | 2025 |
| Graduação em Gestão da Tecnologia da Informação | UNIP | 2024 |
| Pós-graduação em Docência do Ensino Superior | Unyleya | 2018 |
| Licenciatura em Matemática | Faculdade Projeção | 2014 |

## Certificações

**SAS**
* Programming 1: Essentials
* Enterprise Guide 1: Querying and Reporting
* Visual Analytics 1 for SAS Viya: Basics
* Visual Analytics 2 for SAS Viya: Advanced
* Data Literacy Essentials

**AWS Educate**
* Machine Learning Foundations
* Introduction to Generative AI

**EF SET**
* English Certificate, nível B2

## Idiomas

Português, nativo. Inglês, nível B2 certificado pelo EF SET.

## Contato

leonardo.medeiros7293@outlook.com | [LinkedIn](https://linkedin.com/in/leonardo-santos-medeiros)
