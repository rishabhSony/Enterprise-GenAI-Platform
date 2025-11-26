# Enterprise GenAI Platform 🏢

**Secure, Scalable Conversational AI Infrastructure**

A production-grade platform designed to deploy Large Language Models (LLMs) within enterprise environments. It addresses critical business requirements including data security, role-based access control (RBAC), and auditability, while delivering a seamless chat experience.

## 🛡️ Enterprise-Grade Security

-   **RBAC & SSO**: Integrated with Keycloak/Auth0 for granular permission management and Single Sign-On.
-   **PII Redaction**: Middleware layer automatically detects and masks Personally Identifiable Information before it reaches the LLM.
-   **Audit Trails**: Comprehensive logging of all prompts and completions for compliance (GDPR/SOC2).

## 🏗️ System Architecture

-   **API Gateway**: Kong / NGINX for rate limiting and traffic management.
-   **Orchestration**: Kubernetes (EKS/GKE) for auto-scaling inference services.
-   **Vector Search**: Qdrant cluster for high-availability semantic search.
-   **Database**: PostgreSQL with row-level security.

## 🚀 Key Features

-   **Model Agnostic**: Hot-swappable support for OpenAI, Azure OpenAI, Anthropic, and self-hosted Llama 3.
-   **Advanced RAG**: Hybrid search (Dense + Sparse) with reranking for superior context retrieval.
-   **Admin Console**: React-based dashboard for managing knowledge bases, API keys, and usage quotas.

## 🛠️ Tech Stack

-   **Backend**: Python, FastAPI, LangChain
-   **Frontend**: React, TypeScript, TailwindCSS
-   **Infrastructure**: Docker, Kubernetes, Terraform

## 📄 License
MIT License
