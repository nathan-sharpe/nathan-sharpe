# Nathan Sharpe

AI Solutions Developer based in Cincinnati. I build production AI systems: RAG platforms, agentic workflows, and business automations.

## What I've built

**Commodoor** - a production RAG platform for a construction industry client, built on a two-person team where I served as technical lead. n8n orchestration, LangChain-powered Supabase vector database (35,000+ document chunks), Gemini 2.5 Pro with OpenAI embeddings, deployed on DigitalOcean and Google Cloud for 300 concurrent users. Live today: [commodoorai.com](https://www.commodoorai.com/)

**Client automation systems** - AI-powered content creation, customer support routing, and newsletter/blog generation pipelines for corporate clients including EXAIR, delivered through K&J Web Designs.

**Local AI infrastructure** - fully self-hosted stacks with Docker, n8n, and Ollama for privacy-preserving agent development.

## Currently

Just shipped [Total Transparency RAG](https://github.com/nathan-sharpe/Total-Transparency-RAG) - the open-source, code-only companion to the client work above. A RAG system over the SciFact corpus with a rigorous two-layer evaluation harness (retrieval metrics + LLM-as-judge), built as the deliberate inverse of the n8n/LangChain stack: chunking, retrieval scoring, and recall@k/MRR metrics all hand-built, Postgres/pgvector and local Ollama models behind a FastAPI layer, with input/output guardrails and CI throughout.

## Stack

n8n | LangChain | Supabase (pgvector) | Python | SQL | JavaScript/React | Docker | Ollama | DigitalOcean | Google Cloud | Gemini & OpenAI APIs

## Get in touch

[LinkedIn](https://www.linkedin.com/in/nathan-j-sharpe/) - open to roles in AI solutions development, implementation, and workflow automation.
