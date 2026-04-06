<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=30&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=600&height=45&lines=pratik-raut+%24+deploying+agents+%E2%80%A6" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pratik-raut-9b678416b/)
[![Email](https://img.shields.io/badge/pratik.narendra.raut@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:pratik.narendra.raut@gmail.com)
[![Website](https://img.shields.io/badge/useful--agents.com-%234285F4.svg?style=flat&logo=google-chrome&logoColor=white)](https://useful-agents.com)
[![Paper](https://img.shields.io/badge/Publication-ScienceDirect-orange?style=flat&logo=elsevier&logoColor=white)](https://www.sciencedirect.com/science/article/pii/S0306457325001438)

</div>

```yaml
# pratik-raut.agent.yaml

apiVersion: engineer/v1
kind: Agent
metadata:
  name: pratik-raut
  location: Erlangen, Germany
  labels:
    role: ai-solutions-engineer
    org: siemens
    research: faps-fau-erlangen
    education: msc-electromobility-ai-data-analytics
    status: shipping

spec:
  description: >
    I build multi-agent systems, production ML pipelines, and cloud-native
    infrastructure. Published researcher in agentic causal discovery.
    I care about systems that ship and stay up — not just notebooks.

  experience:
    - role: AI Solutions Engineer
      org: Siemens
      highlight: "Multi-agent RCA system — 50% MTTR reduction, 60+ hrs/month saved"

    - role: AI Research Engineer
      org: FAPS, FAU Erlangen-Nuremberg
      highlight: "Agentic causal discovery on NVIDIA OpenClaw — ~20% agent perf gain, published"

    - role: AI Engineer
      org: Bosch
      highlight: "Patent copilot — 80 hrs/week saved, 40% faster IP analysis, 35% fewer hallucinations"

    - role: Data Scientist
      org: Nirvana
      highlight: "7 ML systems E2E — fraud, CLV, search ranking, recommendations, sentiment"

  activeDeployments:
    - name: StratosGuard
      url: github.com/Pat027/StratosGuard
      desc: "AI governance — EU AI Act, ISO 42001, NIST RMF, SOC 2"

    - name: useful-agents.com
      url: useful-agents.com
      desc: "17-agent AI platform on GCP, 100+ users, $0 infra cost"

  publication:
    title: "Structured knowledge-based causal discovery: Agentic streams of thought"
    venue: ScienceDirect
```

---

## Shipped

<table>
<tr>
<td width="50%">

**[StratosGuard](https://github.com/Pat027/StratosGuard)** \
AI governance across 7 compliance frameworks. Automated remediation with sandboxed Terraform/Python fixes. Supply chain attack detection across 50+ AWS services. \
`LangGraph` `FastAPI` `React` `PostgreSQL` `Celery` `Redis`

</td>
<td width="50%">

**[useful-agents.com](https://useful-agents.com)** \
17-agent platform. No-code agent builder with A2A protocol. GKE Autopilot with spot nodes (~75% savings), scale-to-zero workers. 2,500 lines of Terraform. \
`Google ADK` `A2A` `MCP` `GKE` `pgvector` `LiteLLM`

</td>
</tr>
<tr>
<td width="50%">

**Multi-Agent RCA System** — *Siemens* \
Automated root cause analysis with human-in-the-loop. 8+ MCP tool servers with dual-layer auth. Multi-tier caching — 40% token reduction. \
`MCP` `LangGraph` `RAG` `Langfuse`

</td>
<td width="50%">

**Patent Intelligence Copilot** — *Bosch* \
Enterprise RAG with grounded citations. Knowledge graph for patent networks — 40% faster IP analysis. Hallucination rates down 35%. 80 hrs/week saved. \
`Azure OpenAI` `LangChain` `Neo4j` `Airflow` `RAGAS`

</td>
</tr>
<tr>
<td width="50%">

**Agentic Causal Discovery** — *FAPS* &nbsp; [![Paper](https://img.shields.io/badge/paper-ScienceDirect-orange?style=flat-square&logo=elsevier)](https://www.sciencedirect.com/science/article/pii/S0306457325001438) \
LLMs aligned via RLHF/GRPO — ~20% agent performance gain. Sandboxed platform on NVIDIA OpenClaw. ~30% refutation accuracy gain. \
`PyTorch` `RLHF` `GRPO` `MCP` `Docker`

</td>
<td width="50%">

**Fraud, CLV & Churn Pipelines** — *Nirvana* \
CatBoost fraud + chargeback detection (96%/89% recall, 34% fewer false negatives). LightGBM CLV (8% MAPE) + churn (0.93 AUC, 14% churn reduction). \
`CatBoost` `LightGBM` `Optuna`

</td>
</tr>
<tr>
<td width="50%">

**Search Ranking System** — *Nirvana* \
Multi-stage ranking: BM25, bi-encoders, cross-encoder, LightGBM L2R. 61% relevance improvement (MRR@10: 0.84) across 100K passages. \
`LightGBM` `Transformers` `BM25`

</td>
<td width="50%">

**Recommendations & Intelligence** — *Nirvana* \
LightGCN + SimpleX recommendation system — 5x NDCG lift, 49% catalog coverage across 2.7M events. BERT-based competitor sentiment across 150K+ reviews. \
`LightGCN` `BERT` `NLP`

</td>
</tr>
</table>

---

## Toolbox

**Agents & LLMs** &nbsp;
![LangChain](https://img.shields.io/badge/LangChain-%231C3C3C.svg?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-%231C3C3C.svg?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-%236B3FA0.svg?style=flat-square)
![Google ADK](https://img.shields.io/badge/Google%20ADK-%234285F4.svg?style=flat-square&logo=google&logoColor=white)
![Strands SDK](https://img.shields.io/badge/Strands%20SDK-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-%23191919.svg?style=flat-square)
![A2A](https://img.shields.io/badge/A2A-%234285F4.svg?style=flat-square&logo=google&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-%231D4ED8.svg?style=flat-square)
![LiteLLM](https://img.shields.io/badge/LiteLLM-%231D4ED8.svg?style=flat-square)
![Ray](https://img.shields.io/badge/Ray-%23028CF0.svg?style=flat-square&logo=ray&logoColor=white)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-%230078D4.svg?style=flat-square&logo=microsoft&logoColor=white)
![FSDP](https://img.shields.io/badge/FSDP-%23EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white)

**RAG & Eval** &nbsp;
![RAGAS](https://img.shields.io/badge/RAGAS-%230F766E.svg?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-%230F766E.svg?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-%231C3C3C.svg?style=flat-square&logo=langchain&logoColor=white)
![Docling](https://img.shields.io/badge/Docling-%230F766E.svg?style=flat-square)
![Crawl4AI](https://img.shields.io/badge/Crawl4AI-%230F766E.svg?style=flat-square)

**ML & DL** &nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-%23FFD21E.svg?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%23337AB7.svg?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-%23339900.svg?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-%23FFCC00.svg?style=flat-square&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-%231E88E5.svg?style=flat-square)
![PySpark](https://img.shields.io/badge/PySpark-%23E25A1C.svg?style=flat-square&logo=apachespark&logoColor=white)

**RL** &nbsp;
![RLHF](https://img.shields.io/badge/RLHF-%236D28D9.svg?style=flat-square)
![GRPO](https://img.shields.io/badge/GRPO-%236D28D9.svg?style=flat-square)
![Gymnasium](https://img.shields.io/badge/Gymnasium-%230081A5.svg?style=flat-square)

**Cloud** &nbsp;
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![AgentCore](https://img.shields.io/badge/AgentCore-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-%23FF9900.svg?style=flat-square&logo=awslambda&logoColor=white)
![AI Foundry](https://img.shields.io/badge/AI%20Foundry-%230072C6.svg?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure ML](https://img.shields.io/badge/Azure%20ML-%230072C6.svg?style=flat-square&logo=microsoftazure&logoColor=white)
![GKE](https://img.shields.io/badge/GKE-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-%23FF3621.svg?style=flat-square&logo=databricks&logoColor=white)

**Infra** &nbsp;
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
![KEDA](https://img.shields.io/badge/KEDA-%23326CE5.svg?style=flat-square&logo=keda&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-%230194E2.svg?style=flat-square&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B-%23FFBE00.svg?style=flat-square&logo=weightsandbiases&logoColor=black)
![DVC](https://img.shields.io/badge/DVC-%23945DD6.svg?style=flat-square&logo=dvc&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-%23E6522C.svg?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-%23F46800.svg?style=flat-square&logo=grafana&logoColor=white)

**Backend** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-%23009688.svg?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-%23D71F00.svg?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST%20APIs-%2315803D.svg?style=flat-square)
&nbsp; **Frontend** &nbsp;
![React](https://img.shields.io/badge/React-%2320232A.svg?style=flat-square&logo=react&logoColor=61DAFB)

**Data** &nbsp;
![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-%2300A98F.svg?style=flat-square&logo=weaviate&logoColor=white)
![Faiss](https://img.shields.io/badge/Faiss-%230467DF.svg?style=flat-square&logo=meta&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-%234053D6.svg?style=flat-square&logo=amazondynamodb&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-%23005EB8.svg?style=flat-square&logo=opensearch&logoColor=white)

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Pat027&show_icons=true&theme=github_dark&hide_border=true&hide_title=true&hide_rank=true&include_all_commits=true" height="150" />

</div>
