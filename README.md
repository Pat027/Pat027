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
  location: Nuremberg, Germany
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
      highlight: "Agentic causal discovery on NVIDIA OpenClaw — published in ScienceDirect"

    - role: AI Engineer
      org: Bosch
      highlight: "Patent intelligence copilot — 80 hrs/week saved"

    - role: Data Scientist
      org: Nirvana
      highlight: "Fraud, CLV, churn, dormancy systems — 96% recall, 0.93 AUC"

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
Enterprise RAG with grounded citations and hallucination detection. Knowledge graph for patent citation networks. 80 hrs/week saved. \
`Azure OpenAI` `LangChain` `Neo4j` `Airflow` `RAGAS`

</td>
</tr>
<tr>
<td width="50%">

**Agentic Causal Discovery** — *FAPS* &nbsp; [![Paper](https://img.shields.io/badge/paper-ScienceDirect-orange?style=flat-square&logo=elsevier)](https://www.sciencedirect.com/science/article/pii/S0306457325001438) \
LLMs aligned via RLHF/GRPO for autonomous causal discovery. Sandboxed agentic platform on NVIDIA OpenClaw. ~30% refutation accuracy gain. \
`PyTorch` `RLHF` `GRPO` `MCP` `Docker`

</td>
<td width="50%">

**Risk & Fraud Systems** — *Nirvana* \
Dual-model fraud + chargeback detection (96% recall). CLV prediction (8% MAPE). Dormancy reactivation across 500K+ users — 4.2x campaign ROI. \
`CatBoost` `LightGBM` `Optuna` `SageMaker`

</td>
</tr>
</table>

---

## Toolbox

**Agents & LLMs** &nbsp; `LangChain` `LangGraph` `LlamaIndex` `Google ADK` `Strands SDK` `MCP` `A2A` `vLLM` `LiteLLM` `Ray` `DeepSpeed`

**RAG & Eval** &nbsp; `RAGAS` `Langfuse` `LangSmith` `Docling` `Crawl4AI`

**ML & DL** &nbsp; `PyTorch` `TensorFlow` `HuggingFace` `scikit-learn` `XGBoost` `LightGBM` `CatBoost` `Optuna` `PySpark`

**RL** &nbsp; `RLHF` `GRPO` `Gymnasium`

**Cloud** &nbsp;
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=flat-square&logo=google-cloud&logoColor=white)
&nbsp; `Bedrock` `AgentCore` `SageMaker` `Lambda` `AI Foundry` `GKE`

**Infra** &nbsp;
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white)
&nbsp; `KEDA` `MLflow` `W&B` `DVC` `Prometheus` `Grafana`

**Data** &nbsp;
![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat-square&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
&nbsp; `pgvector` `Weaviate` `Faiss` `DynamoDB` `OpenSearch`

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Pat027&show_icons=true&theme=github_dark&hide_border=true&hide_title=true&hide_rank=true&include_all_commits=true" height="150" />
<img src="https://github-readme-streak-stats.herokuapp.com?user=Pat027&theme=github-dark-blue&hide_border=true" height="150" />

</div>
