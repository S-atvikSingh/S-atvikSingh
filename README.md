<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1a2e&height=100&section=header" width="100%"/>

# Satvik Singh

**AI/ML Engineer · Backend Systems · Sunnyvale, CA**

*I build AI systems that work in production — not just in demos.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/s-atviksingh)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jaisatvik@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Guardian_·_Top_0.75%25-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/jaisatvik)

</div>

---

## About

AWS Certified ML Engineer with 4+ years of experience across
production AI pipelines, distributed backend systems, and
high-throughput data infrastructure. I focus on the part of
AI engineering most people skip: **measurable quality**. Reliable
retrieval, observable pipelines, and systems you can actually
debug at 2am.

```python
profile = {
    "currently_building" : "WhyFail", "DesignCritic", "DocWatch",
    "sharpening"         : "LangGraph multi-agent systems", "QLoRA fine-tuning",
    "competing"          : "Leetcode Guardian · Top 0.75% of 863,486 participants",
    "open_to"            : "Backend · AI/ML Engineering roles · Sunnyvale, CA"
}
```

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Dyna-Cache](https://github.com/S-atvikSingh/dyna-cache)
**Semantic caching middleware for LLM applications**

Traditional caches require exact string matches. Dyna-Cache
uses vector similarity search to serve cached responses for
semantically equivalent queries — intercepting requests before
they ever reach the LLM.

**Benchmarked results:**
- **70x+ effective speedup** vs remote LLM roundtrip
- ~14ms cache HIT vs 1,000–5,000ms LLM call
- 98% latency reduction per cached request
- Production telemetry: hit rates, latency saved, cost delta

**Key decision:** L2 distance threshold of 0.35 on FAISS index
tuned to balance precision vs recall — too low returns wrong
answers, too high never hits the cache.

`Python` `FastAPI` `FAISS` `Sentence-Transformers` `Redis` `Docker`

</td>
<td width="50%" valign="top">

### [Knowledge Assistant](https://github.com/S-atvikSingh/knowledge-assistant)
**RAG-powered document Q&A system**

Upload any document, ask questions in natural language, get
answers grounded strictly in your content. Source-attribution
logic prevents the model from answering outside retrieved
context — the core failure mode of most RAG systems.

**Results:**
- **95% answer faithfulness** (RAGAS eval, 200-question set)
- Strict prompt constraints enforce source citation on every answer
- Full-stack: async FastAPI backend + React frontend

**Key decision:** Semantic chunking over fixed-size chunking
improved faithfulness from 71% → 95% — the retrieval strategy
mattered more than the model.

`Python` `FastAPI` `OpenAI` `Pinecone` `LangChain` `React` `Docker`

</td>
</tr>
</table>

---

## What I'm Building Next

> Each project solves a problem I personally run into —
> which means I'm user #1 and the feedback loop is immediate.

| Project | The Problem | Why It's Hard | Stack |
|---|---|---|---|
| **WhyFail** | Leetcode tells you *that* your solution failed — not *why* your logic breaks on that specific input or what class of problem you're actually stuck on | Socratic guidance without revealing the answer is a constrained generation problem general LLMs are inconsistent at | LangGraph · pgvector · LangSmith · FastAPI |
| **DesignCritic** | No way to stress-test system designs before an interview. Generic AI feedback doesn't probe failure modes the way a real staff engineer would | Requires a real knowledge base of how actual companies (Netflix, Discord, Uber) solved the same problems — retrieval must be semantic, not keyword | LangGraph · Multi-Agent · pgvector · LangSmith |
| **DocWatch** | Documentation goes stale silently when code changes. A function renamed `verify()` → `validate()` can invalidate docs that never mention either word | True staleness detection requires semantic diff, not string matching — this is a retrieval problem disguised as a docs problem | LangGraph · pgvector · GitHub App · Celery |

---

## Competitive Programming

<div align="center">

<img width="1470" height="776" alt="LeetCodeSnap042026" src="https://github.com/user-attachments/assets/55e35786-dcf0-4301-b024-ebe75db61879" />


</div>

Got serious in **June 2025**. Nine months to Guardian — top 0.75%
globally. Contest format (90 min · 4 problems · no hints) taught
me more about my own reasoning under pressure than years of
solo practice. The gap between what you *know* and what you can
*execute under time pressure* is where the real work is.

---

## Experience

**Machine Learning Engineer** · Community Dreams Foundation
*(Sep 2025 – Present · Sunnyvale, CA)*

Built real-time RAG pipeline (Whisper ASR + LangChain) serving
200+ concurrent users. Cut P95 latency from 1.4s → 480ms via
MLflow-traced bottleneck analysis. Reduced inference cost 30%
(~$800/mo) through context pruning while maintaining 95% answer
faithfulness. Maintained 99.9% uptime across 4 services on AWS
ECS over 6 months, monitored via CloudWatch.

**Software Engineer** · MothersonSumi Infotech & Design (MIND)
*(Aug 2020 – Dec 2023 · Noida, India)*

Automated 500K+ daily OEM→Salesforce transactions, eliminating
95% of manual data entry across 3 enterprise clients. Architected
Java/Python ETL pipelines at <5 min data freshness over 3+ years
of production operation. Reduced client support tickets 45%
(~80/mo → ~44/mo) by fixing survey logic failures and expanding
test coverage from 60% → 92%.

---

## Certifications

![AWS ML](https://img.shields.io/badge/AWS_Certified-ML_Engineer_Associate-FF9900?style=flat&logo=amazonaws&logoColor=white)
![AWS CCP](https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=flat&logo=amazonaws&logoColor=white)

---

## Skills

**AI / LLM Engineering**
`LangGraph` `LangChain` `LlamaIndex` `RAG Pipelines` `Whisper ASR`
`Semantic Caching` `FAISS` `Prompt Engineering` `MLflow`

**Backend & Systems**
`Python` `Java` `FastAPI` `RESTful APIs` `WebSockets` `Microservices` `Redis`

**Databases**
`PostgreSQL` `pgvector` `MySQL` `DynamoDB` `Pinecone` `ChromaDB`

**DevOps & Cloud**
`Docker` `Kubernetes` `CI/CD` `AWS (EKS · EC2 · SageMaker · Bedrock · CloudWatch)`

---

<div align="center">

*Open to backend and AI engineering roles · Will consider relocation/remote as appropriate*
<br/>
**[linkedin.com/in/s-atviksingh](https://linkedin.com/in/s-atviksingh) · jaisatvik@gmail.com**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0d1117&height=80&section=footer" width="100%"/>

</div>
