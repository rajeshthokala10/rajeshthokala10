<h1 align="center">Hi, I'm Rajesh Thokala 👋</h1>
<h3 align="center">AI Full Stack Engineer · 13+ years · Bangalore</h3>

<p align="center">
13+ years of building backend systems, from <b>Java, Spring Boot and microservices</b> to today's production-grade <b>RAG systems</b>, <b>agentic AI</b> and <b>LLM pipelines</b>, covering the model and data, the API, the UI and the cloud deployment.
</p>

<p align="center">
  <a href="https://storyley.ai"><img src="https://img.shields.io/badge/Live-storyley.ai-7c3aed?style=for-the-badge" alt="storyley.ai"/></a>
  <a href="https://x.com/IamRajesh"><img src="https://img.shields.io/badge/X-@IamRajesh-000000?style=for-the-badge&logo=x" alt="X"/></a>
  <img src="https://komarev.com/ghpvc/?username=rajeshthokala10&style=for-the-badge&color=0e75b6&label=Profile+views" alt="profile views"/>
</p>

---

## 🚀 What I'm building now

### 📖 [Storyley.AI](https://storyley.ai): personalised children's stories, live in production
A parent or teacher picks a child, a theme and a voice. The platform writes a safe, age-appropriate story, illustrates it and narrates it, optionally in a family member's cloned voice.
- **Microservices:** FastAPI services for users, stories, voices, pictures and safety, plus a Next.js web app and an Expo mobile app
- **AI:** LLM story generation, a fail-closed child-safety gate on every field, an evaluation harness, TTS and voice cloning on GPU (RunPod)
- **Data and ops:** Postgres with versioned Alembic migrations, MongoDB and Redis; CI/CD to Railway, health checks, structured logs with personal data redacted, Prometheus/OTel signals
- **Next:** a native **Telugu children's-story model** (Gemma 3, QLoRA) trained on Ramayana, Mahabharata, Panchatantra and Tenali Ramakrishna tales

### 🏛️ [Assembly_KB](https://github.com/rajeshthokala10/Assembly_KB): multilingual legislative RAG ingestion
OCR for Telugu, Hindi and English (including legacy-font Indic text), hierarchical parent/child chunking, hybrid **BGE-M3 dense + BM25 sparse** embeddings and a Qdrant schema. It runs as a separate service from the query API.

### 🗞️ [ai-editor](https://github.com/rajeshthokala10/ai-editor): an autonomous AI newspaper
Claude with live web research writes a ten-page PDF newspaper and a ten-slide PPTX briefing each day. Every edition passes a schema check and automated QA before it is emailed.

### 🏙️ [investor-publish](https://github.com/rajeshthokala10/investor-publish): Bengaluru real-estate intelligence
A scheduled research batch produces a daily-edition PDF, a monthly magazine, metrics and a FastAPI website with news filtered by zone, growth charts and price levels.

### 🪙 [Gold_Tracker](https://github.com/rajeshthokala10/Gold_Tracker): 22K gold and Gold BeES weekly patterns
A phone-first static site with a standard-library Python data collector that cross-checks its sources. It shows seasonal and weekly patterns, with Python and Node tests.

### 🧠 [AIML](https://github.com/rajeshthokala10/AIML): Text-to-SQL with LoRA
T5 Text-to-SQL with LoRA/QLoRA fine-tuning, RAG few-shot examples at inference, human-feedback retraining and exact/execution-match benchmarks.

---

## ☕ Java, Spring Boot and microservices: where it started

Before AI, I spent years building **enterprise backends in Java and Spring Boot**, and that experience shapes how I build AI systems today: clean service boundaries, configuration, resilience and testing.

| Area | What I built | Repos |
|---|---|---|
| 🧩 **Spring Cloud microservices** | Netflix OSS stack: Eureka service registry, Spring Cloud Config server, Zuul API gateway, Hystrix circuit breaker and dashboard, Docker Compose, plus a traffic generator to exercise it | [springcloud-netflix-oss-poc](https://github.com/rajeshthokala10/springcloud-netflix-oss-poc) · [webservice-registry](https://github.com/rajeshthokala10/webservice-registry) · [config-server](https://github.com/rajeshthokala10/config-server) · [SpringCloudZuul](https://github.com/rajeshthokala10/SpringCloudZuul) |
| 🛒 **Domain microservices** | An e-commerce system split into Product, Pricing and Discount services | [EcommerceMicroservice](https://github.com/rajeshthokala10/EcommerceMicroservice) · [studnet-api](https://github.com/rajeshthokala10/studnet-api) |
| 🌱 **Spring Boot REST and data** | CRUD REST APIs with JPA/Hibernate on MySQL and Oracle, and a full-stack Spring Boot + React app | [SpringBootRestCrudApplication](https://github.com/rajeshthokala10/SpringBootRestCrudApplication) · [SpringBoot-Jpa_Oracle](https://github.com/rajeshthokala10/SpringBoot-Jpa_Oracle) · [springboot-oracledb](https://github.com/rajeshthokala10/springboot-oracledb) · [SpringBoot-ReactApp](https://github.com/rajeshthokala10/SpringBoot-ReactApp) |
| 🦠 **COVID-19 tracker (2020)** | A Spring Boot app that tracked India's COVID-19 numbers | [COVID19-R-TRACKER](https://github.com/rajeshthokala10/COVID19-R-TRACKER) |

### 🧮 Problem solving and modern Java
Data structures, algorithms and interview-style problems in Java (HackerRank and FAANG-style questions), plus hands-on practice with **Java 8+**: lambdas, streams, functional interfaces, Optional and the newer language features.

[ProblemSolving-Latest](https://github.com/rajeshthokala10/ProblemSolving-Latest) · [java8Practice](https://github.com/rajeshthokala10/java8Practice) · [java8](https://github.com/rajeshthokala10/java8) · [PracticeCode](https://github.com/rajeshthokala10/PracticeCode) · [DataStructures-Part02](https://github.com/rajeshthokala10/DataStructures-Part02)

---

## 🛠️ Tech stack

**AI / LLM:** &nbsp;
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?logo=qdrant&logoColor=white)

**Backend:** &nbsp;
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-6DB33F?logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)

**Frontend:** &nbsp;
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white)

**Data and cloud:** &nbsp;
![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rajeshthokala10&show_icons=true&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rajeshthokala10&layout=compact&langs_count=2&hide=html,css,javascript,typescript,jupyter%20notebook,ruby,tsql,shell,rich%20text%20format,scss,dockerfile,makefile,procfile,batchfile,c%2B%2B,c%23,c,go&custom_title=Languages&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=rajeshthokala10&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>
<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=rajeshthokala10&theme=tokyo-night&hide_border=true&area=true" alt="Contribution graph"/>
</p>

> Much of my current work, including Storyley.AI, is in private repositories, so these public numbers show only part of it.

---

---

<p align="center"><i>Open to conversations about AI products, RAG and agentic systems. Reach out on <a href="https://x.com/IamRajesh">X</a>.</i></p>
