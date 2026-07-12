# Nathan Sharpe

AI Solutions Developer. I build production AI systems: RAG platforms, agentic workflows, and automation pipelines.

## What I've built

**Commodoor** ([commodoorai.com](https://www.commodoorai.com/)) is a production RAG platform I built as technical lead on a two-person team for a corporate client in the construction industry. It answers questions over 35,000+ document chunks and is live today with a public demo page.

The parts I'm most proud of:

- **Retrieval architecture**: n8n orchestration over a LangChain-powered Supabase vector database, with Gemini 2.5 Pro answering over OpenAI embeddings
- **Metadata enrichment**: a pipeline that uses a small LLM (GPT-4o mini) to extract structured attributes from every document chunk, which substantially improved retrieval accuracy
- **Automated ingestion**: a Firecrawl + n8n web scraping pipeline that pulls, vectorizes, and ingests OSHA regulations
- **Production infrastructure**: DigitalOcean backend provisioned for 300 concurrent users, Google Cloud front end
- **Feedback instrumentation**: per-answer ratings with categorized failure reasons, logged to Supabase to drive iteration across 200+ test queries

Before that, I built AI-powered automation systems for corporate clients at K&J Web Designs, including content creation, customer support routing, and newsletter and blog generation, and led front-end development for PrepShift, a restaurant scheduling app.

## Currently

Building an open-source RAG system in Python to share the patterns I use in client work: ingestion, retrieval, evaluation, and deployment. Watch this space.

## Stack

n8n, LangChain, Supabase (pgvector), Python, SQL, LLM APIs (Gemini, OpenAI), Firecrawl, DigitalOcean, Google Cloud, Docker, Ollama, self-hosted local AI

## Contact Information

- LinkedIn: [in/nathan-j-sharpe](https://www.linkedin.com/in/nathan-j-sharpe/)
- Email: nathan.sharpe.dev@gmail.com