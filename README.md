<div align="center">

# Eliton Scos

**AI Automation & Backend Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/elitonscos)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ElitonScos)

</div>

---

Engenheiro de automação e backend com foco em pipelines de processamento inteligente, integração de LLMs em sistemas de produção e infraestrutura orientada a dados. Trabalho com múltiplas linguagens e tecnologias — Go, Python, Rust, TypeScript, PHP, Ruby — escolhendo a ferramenta certa para cada problema.

---

## Stack

**Linguagens**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)

**Infra & Dados**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**AI / ML**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers.js-F5A623?style=flat)

---

## Projetos

### 🔗 [hookbridge-platform](https://github.com/ElitonScos/hookbridge-platform)
**Plataforma multi-linguagem de recebimento e classificação de webhooks**

Receiver em PHP (Slim 4) com validação HMAC-SHA256, processor em Go que consome o banco e despacha eventos, classificador em Ruby (regras léxicas) exposto via HTTP. Tudo orquestrado com Docker Compose e PostgreSQL.

`PHP` `Go` `Ruby` `PostgreSQL` `Docker`

---

### 🔐 [vault-api](https://github.com/ElitonScos/vault-api)
**API REST de gerenciamento de credenciais com autenticação JWT**

FastAPI com SQLAlchemy + Alembic, autenticação JWT (RS256), criptografia AES-256 para secrets em repouso, cobertura de testes com pytest e pipeline CI no GitHub Actions.

`Python` `FastAPI` `PostgreSQL` `JWT` `Docker`

---

### 📧 [mailflow-processor](https://github.com/ElitonScos/mailflow-processor)
**Automação de pedidos via e-mail com extração por LLM**

Daemon Go que monitora IMAP, extrai dados estruturados de e-mails de pedido via GPT-4o e persiste os registros no PostgreSQL com status de processamento. Inclui dashboard HTTP para acompanhamento.

`Go` `OpenAI` `PostgreSQL` `IMAP` `Docker`

---

### 📨 [eventrelay-broker](https://github.com/ElitonScos/eventrelay-broker)
**Broker de eventos assíncronos com RabbitMQ**

Sistema produtor/consumidor com topic exchange, dead-letter queue, retry com backoff exponencial e persistência no PostgreSQL. Publisher e consumer em Python com aio-pika (async).

`Python` `RabbitMQ` `PostgreSQL` `Docker`

---

### 🔍 [semanticvault](https://github.com/ElitonScos/semanticvault)
**Busca semântica por similaridade vetorial**

API TypeScript/Node com pgvector (PostgreSQL), geração de embeddings local via @xenova/transformers (sem API key), índice IVFFlat e busca por cosine similarity. Totalmente offline.

`TypeScript` `Node.js` `pgvector` `PostgreSQL` `Docker`

---

### 🕷️ [dataharvest-scraper](https://github.com/ElitonScos/dataharvest-scraper)
**Web scraper concorrente escrito em Rust**

Worker pool em Rust com Tokio, scraping via reqwest + scraper, fila de jobs no PostgreSQL com sqlx, retry automático e API HTTP (Axum) para submissão e consulta de resultados.

`Rust` `Axum` `Tokio` `PostgreSQL` `Docker`

---

### ⚙️ [devops-infrastack](https://github.com/ElitonScos/devops-infrastack)
**Stack de infraestrutura com Nginx, Go e CI/CD automatizado**

Reverse proxy Nginx com upstream least_conn e health endpoint, API Go multi-stage, scripts Bash validados com ShellCheck (deploy, rollback, healthcheck), pipeline GitHub Actions completo.

`Go` `Nginx` `Bash` `Docker` `GitHub Actions`

---

<div align="center">

*"Automação é sobre remover fricção — não sobre substituir julgamento."*

</div>
