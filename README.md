<div align="center">

# Hi there, I'm Sayeed Anawar 👋

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6C63FF&center=true&vCenter=true&width=620&lines=Senior+GenAI+%2F+Agentic+AI+%26+Backend+Engineer;LangGraph+%26+Model+Context+Protocol+(MCP)+Architect;Zero-Copy+OLAP+(DuckDB+%2B+S3+Parquet)+Pipelines;Enterprise+Java+%26+Spring+Boot+Microservices" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://www.linkedin.com/in/sayeedanawar"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sayeedanawarr@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/sayeedanawar"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Location-Kolkata%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location"/>
  <img src="https://komarev.com/ghpvc/?username=sayeedanawar&color=6C63FF&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views"/>
</p>

---

</div>

## 📌 Executive Summary

**Senior GenAI / Agentic AI & Backend Engineer** with 5 years of enterprise experience building resilient distributed backends and production-grade agentic AI systems. 

- 💼 **Current Role:** Senior AI & Backend Engineer at **Tata Consultancy Services (TCS)** *(ex-**Accenture**)*
- 🤖 **Agentic AI & Orchestration:** Production multi-tool agent engines via **LangGraph**, **Model Context Protocol (MCP)**, AWS Bedrock, deterministic Pydantic v2 schemas, and self-healing execution loops.
- ⚡ **Zero-Copy OLAP & Data Lakehouse:** Embedded analytics with **DuckDB (`httpfs`)** querying partitioned S3 Parquet snapshots with predicate pushdowns, AST-level SQL safety guardrails, and sub-100ms latencies.
- 🚀 **Enterprise Microservices:** High-throughput **Java (8/11/17)** and **Spring Boot** microservices, distributed resilience patterns (Resilience4j), and high-volume batch processing.
- 🎓 **Education & Certifications:** B.Tech in CSE (Aliah University) • AWS Certified Developer – Associate • AWS Certified Generative AI Developer – Professional (In Progress)

---

## 🛠️ Technical Competencies

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,java,spring,postgres,aws,docker,git,maven,idea,postman,linux" alt="Tech Stack Icons" />
</div>

<br/>

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Agentic AI & LLM Systems** | `LangGraph` `LangChain (create_agent)` `Model Context Protocol (MCP)` `AWS Bedrock (Converse API)` `RAG` `Pydantic v2` |
| **Lakehouse, OLAP & Vectors** | `DuckDB (httpfs)` `Apache Parquet (ZSTD)` `Amazon S3 Data Lake` `PostgreSQL (RDS Proxy)` `FAISS` `TF-IDF` |
| **AI Safety & Cost Optimization** | `SQL AST Parsing (extract_statements)` `Artifact Whitelisting` `Bedrock Prompt Caching (cachePoint - 90% cost drop)` |
| **Enterprise Backend** | `Java (8/11/17)` `Python` `Spring Boot` `Spring Cloud` `Spring Data JPA` `Spring Batch` `Resilience4j` `HikariCP` |
| **Cloud & DevOps** | `AWS Lambda` `Amazon S3` `SQS / SNS` `Amazon CloudWatch` `Docker` `CI/CD Pipelines` `Git` |

---

## ⚙️ Engineering Highlights & Core Architecture

<div align="center">

| 🤖 Deterministic Agentic AI | ⚡ Zero-Copy Lakehouse Analytics | 🛡️ AST Guardrails & Optimization | 🏛️ Resilient Microservices |
| :--- | :--- | :--- | :--- |
| LangGraph workflows with recursion limits, self-healing nudge prompts, and MultiServerMCPClient routing. | DuckDB over daily-partitioned S3 Parquet snapshots via predicate pushdowns and ETag cache invalidation. | Enforcing non-SELECT / multi-statement payload blocking via DuckDB AST parser; Bedrock prompt caching. | Low-latency Spring Boot APIs protected by Resilience4j circuit breakers, rate-limiting, and RDS Proxy. |

</div>

---

## 💼 Professional Experience & Production Impact

### 🏢 **Tata Consultancy Services (TCS)** — *Senior AI & Backend Engineer*
*May 2025 – Present | Kolkata, India*
- **Enterprise Agent Engine:** Architected an enterprise agentic query engine using **LangGraph**, enforcing a deterministic Final Answer Pydantic schema and a 15-step recursion cap to eliminate runaway execution loops in production.
- **Dynamic Multi-Tool Execution (MCP):** Built natural-language routing using `MultiServerMCPClient` to orchestrate tool calls across PostgreSQL, enterprise knowledge bases, and cloud storage.
- **Self-Healing AI Execution:** Implemented nudge prompts for missing structured outputs, fallback text extraction, and exponential backoff (3 attempts) for Bedrock transport failures, dropping unhandled failures to near-zero.
- **Zero-Copy OLAP Architecture:** Developed an embedded OLAP pipeline with **DuckDB (`httpfs`)** querying daily-partitioned Amazon S3 Parquet snapshots using predicate pushdowns and ETag cache invalidation, resolving OOM issues and achieving sub-100ms latencies.
- **AST-Level SQL Safety & Token Optimization:** Engineered SQL security guardrails using DuckDB's AST parser (`extract_statements`) to intercept unauthorized and multi-statement queries before execution; configured AWS Bedrock `cachePoint` boundaries to reduce prompt token costs by 90%.

---

### 🏢 **Accenture** — *Backend Engineer*
*October 2021 – May 2025 | Kolkata, India*
- **High-Throughput Microservices:** Designed and maintained mission-critical Java 11 / Spring Boot microservices across banking, healthcare, and energy domains, boosting API response times by up to 90%.
- **Resilience & Fault Tolerance:** Applied distributed resilience patterns with **Resilience4j** (circuit breakers, retries, rate limiters) to guarantee system reliability under heavy enterprise traffic loads.
- **Relational Tuning & Schema Design:** Analyzed query execution plans and tuned indexes for PostgreSQL and SQL Server layers.
- **Batch Processing & Containerization:** Developed scheduled data processing pipelines and automated notification workflows with **Spring Batch**; containerized services using **Docker** within automated CI/CD pipelines.

---

## 🚀 Featured Architecture & Systems

### ⚡ **Enterprise Agentic Lakehouse & Query Engine**
*Production Multi-Tool AI Agent & Zero-Copy Analytics Pipeline*
- **Tech Stack:** `Python` • `LangGraph` • `Model Context Protocol (MCP)` • `AWS Bedrock` • `DuckDB` • `Parquet` • `S3` • `PostgreSQL`
- **Key Deliverables:**
  - Dynamic tool routing across heterogeneous storage layers using MCP client architecture.
  - Sub-100ms analytical query response directly over S3 data lakes without cluster overhead.
  - Zero-exception self-healing loops and strict AST payload validation for secure, deterministic execution.

---

## 📬 Let's Connect & Collaborate

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sayeed%20Anawar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayeedanawar)
[![Email](https://img.shields.io/badge/Email-sayeedanawarr%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sayeedanawarr@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sayeedanawar-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sayeedanawar)

<br/>

*Open to discussions on Production Agentic AI, MCP Architecture, Zero-Copy OLAP, and Enterprise Distributed Systems.*

</div>
