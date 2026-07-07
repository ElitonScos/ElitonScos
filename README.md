<div align="center">

# Eliton Scos

**AI Automation & Backend Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eliton-silva-982463187/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ElitonScos)

</div>

---

Engenheiro de backend e automação com foco em **IA aplicada e arquitetura de soluções**. Projeto arquiteturas de IA (agentes com function/tool calling e RAG), integro LLMs em sistemas de produção e cuido de infraestrutura orientada a dados: containers, orquestração, CI/CD e observabilidade. Trabalho com múltiplas linguagens (Go, Python, Rust, TypeScript, PHP, Ruby) escolhendo a ferramenta certa para cada problema.

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
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

**AI / ML**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![RAG](https://img.shields.io/badge/RAG-6E56CF?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers.js-F5A623?style=flat)

---

## Projetos

### [erpmind](https://github.com/ElitonScos/erpmind)
**ERP com IA nativa: agente com function calling + RAG**

API FastAPI de ERP (pedidos, estoque, financeiro) com Clean Architecture, mais um agente de IA (LangGraph) que chama os módulos como ferramentas (function calling) e responde perguntas fundamentadas em RAG sobre pgvector. Roda com LLM ou 100% offline. Observabilidade com Langfuse, avaliação de RAG, Docker, CI, diagramas C4 e ADRs.

`Python` `FastAPI` `LangGraph` `RAG` `pgvector` `Docker`

---

### [agentflow](https://github.com/ElitonScos/agentflow)
**Automação inteligente de processos com motor de workflow**

Classifica solicitações de negócio com LLM (structured output) e decide a ação — encaminhar, escalar, auto-resolver ou revisão humana — sobre um motor de workflow (DAG) próprio com retry, detecção de ciclos e human-in-the-loop por limiar de confiança. Roda com LLM ou offline.

`Python` `FastAPI` `LangChain` `Workflow Engine` `Docker`

---

### [k8s-observability-platform](https://github.com/ElitonScos/k8s-observability-platform)
**Plataforma Kubernetes local com observabilidade completa**

Cluster Kubernetes em kind (3 nós) orquestrando dois serviços com PostgreSQL e RabbitMQ, expostos via NGINX Ingress e empacotados num Helm chart próprio. Observabilidade com Prometheus e Grafana (dashboard provisionado como código), autoscaling com HPA e metrics-server.

`Kubernetes` `Helm` `Prometheus` `Grafana` `kind` `NGINX Ingress`

---

### [iac-cloud-pipeline](https://github.com/ElitonScos/iac-cloud-pipeline)
**Infraestrutura como Código com Terraform e CI/CD completo**

Terraform provisionando recursos AWS (S3, DynamoDB, SQS com DLQ, IAM, VPC) via LocalStack, sem conta na nuvem. Pipeline GitHub Actions com lint, testes, build da imagem, scan de segurança com Trivy, push para o GHCR e terraform plan/apply.

`Terraform` `AWS` `LocalStack` `GitHub Actions` `Trivy` `Docker`

---

### [infrastack](https://github.com/ElitonScos/infrastack)
**Stack de infraestrutura com Nginx, Go e CI/CD automatizado**

Reverse proxy Nginx com upstream least_conn e health endpoint, API Go multi-stage, scripts Bash validados com ShellCheck (deploy, rollback, healthcheck) e pipeline GitHub Actions completo.

`Go` `Nginx` `Bash` `Docker` `GitHub Actions`

---

### [hookbridge](https://github.com/ElitonScos/hookbridge)
**Plataforma multi-linguagem de recebimento e classificação de webhooks**

Receiver em PHP (Slim 4) com validação HMAC-SHA256, processor em Go que consome o banco e despacha eventos, classificador em Ruby (regras léxicas) exposto via HTTP. Tudo orquestrado com Docker Compose e PostgreSQL.

`PHP` `Go` `Ruby` `PostgreSQL` `Docker`

---

### [vaultapi](https://github.com/ElitonScos/vaultapi)
**API REST de gerenciamento de credenciais com autenticação JWT**

FastAPI com SQLAlchemy e Alembic, autenticação JWT (RS256), criptografia AES-256 para secrets em repouso, cobertura de testes com pytest e pipeline CI no GitHub Actions.

`Python` `FastAPI` `PostgreSQL` `JWT` `Docker`

---

### [mailflow](https://github.com/ElitonScos/mailflow)
**Automação de pedidos via e-mail com extração por LLM**

Daemon Go que monitora IMAP, extrai dados estruturados de e-mails de pedido via GPT-4o e persiste os registros no PostgreSQL com status de processamento. Inclui dashboard HTTP para acompanhamento.

`Go` `OpenAI` `PostgreSQL` `IMAP` `Docker`

---

### [eventrelay](https://github.com/ElitonScos/eventrelay)
**Broker de eventos assíncronos com RabbitMQ**

Sistema produtor/consumidor com topic exchange, dead-letter queue, retry com backoff exponencial e persistência no PostgreSQL. Publisher e consumer em Python com aio-pika (async).

`Python` `RabbitMQ` `PostgreSQL` `Docker`

---

### [semanticvault](https://github.com/ElitonScos/semanticvault)
**Busca semântica por similaridade vetorial**

API TypeScript/Node com pgvector (PostgreSQL), geração de embeddings local via @xenova/transformers (sem API key), índice IVFFlat e busca por cosine similarity. Totalmente offline.

`TypeScript` `Node.js` `pgvector` `PostgreSQL` `Docker`

---

### [dataharvest](https://github.com/ElitonScos/dataharvest)
**Web scraper concorrente escrito em Rust**

Worker pool em Rust com Tokio, scraping via reqwest e scraper, fila de jobs no PostgreSQL com sqlx, retry automático e API HTTP (Axum) para submissão e consulta de resultados.

`Rust` `Axum` `Tokio` `PostgreSQL` `Docker`
