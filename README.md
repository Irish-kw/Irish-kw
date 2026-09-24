<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:0969DA,100:8250DF&height=230&section=header&text=Guo-Wei%20Wong&fontSize=52&fontColor=F0F6FC&animation=fadeIn&fontAlignY=36&desc=AI%20Security%20%E2%80%A2%20Graph%20Learning%20%E2%80%A2%20Agent%20Observability&descAlignY=56&descSize=19" alt="Guo-Wei Wong" />

<a href="https://github.com/Irish-kw">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=920&lines=AI+Security+Researcher;Graph+Reasoning+under+Incomplete+Observations;Observable+Agentic+Software;APT+Campaign+Analysis+and+Streaming+Security+Memory" alt="Research interests" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Irish-kw&style=for-the-badge&color=0969da&label=PROFILE+VIEWS" alt="Profile views" />
<img src="https://img.shields.io/badge/AI%20Security-Research-8250DF?style=for-the-badge" alt="AI Security" />
<img src="https://img.shields.io/badge/Graph%20Learning-Research-0969DA?style=for-the-badge" alt="Graph Learning" />
<img src="https://img.shields.io/badge/Agent%20Observability-Systems-1F6FEB?style=for-the-badge" alt="Agent Observability" />

</div>

## About

I work on **AI systems for security**, **graph reasoning**, and **observable agentic software**.  
My recent research focuses on recovering structure from noisy or incomplete evidence, understanding long-running APT campaigns, and building systems that make AI-agent execution behavior inspectable.

---

## Focus On

- **CURVE** — graph-theoretic reasoning under incomplete observations, with a focus on support, exhaustiveness, and occurrence relations.
- **ExecWeave** — cross-layer execution provenance for observable agentic software, connecting agent semantics with processes, files, and network evidence.
- **SLM Streaming Security Memory** — compact persistent memory for long-running security reasoning without replaying arbitrary discarded history.
- **GraphGeneration** — conditional attack-campaign graph generation from security evidence and structured technique/campaign representations.

---

## Featured Project — ExecWeave

<div align="center">

<a href="https://github.com/Irish-kw/ExecWeave">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Irish-kw&repo=ExecWeave&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=8250DF&text_color=C9D1D9" alt="ExecWeave repository card" />
</a>

<br/><br/>

<a href="https://github.com/Irish-kw/ExecWeave">
  <img src="https://raw.githubusercontent.com/Irish-kw/ExecWeave/main/docs/assets/codex.gif" width="92%" alt="ExecWeave live execution graph" />
</a>

</div>

**ExecWeave — Cross-Layer Execution Provenance for Observable Agentic Software**

A local-first observability system that combines provider-level agent semantics with operating-system runtime evidence and renders the result as an interactive execution graph.

[**Repository**](https://github.com/Irish-kw/ExecWeave) · [**PyPI**](https://pypi.org/project/execweave/)

---

## Publications

### First-author
- **Learnable Staircase Activations for Ordinal Outputs under Mutual Information Regularization**, *In Peer-Review*, 2026.
- **TGCM: Topic-Guided Generative Disentanglement of Interleaved APT Technique Sequences**. *arXiv preprint arXiv:2606.18651*, 2026. [arXiv](https://arxiv.org/abs/2606.18651)
- **Poster: When Logs Misbehave: Retrieving Known APTs from Noisy Graphs**. *ACM Conference on Computer and Communications Security (CCS Poster)*, 2025.
- **Attention-based API locating for malware techniques**. *IEEE Transactions on Information Forensics and Security*, 19:1199–1212, 2023.

### Selected co-authored works

- **A cascade approach for APT campaign attribution in system event logs: Technique hunting and subgraph matching**. *ICC 2025-IEEE International Conference on Communications*, 1073–1078, 2025.
- **Poster: LogCraft: Crafting CVE-Aware Synthetic Worlds (Logs)**. *ACM Conference on Computer and Communications Security (CCS Poster)*, 2025.
- **Saga: Synthetic audit log generation for APT campaigns**. *IEEE Transactions on Dependable and Secure Computing*, 2025.
- **Sparse grid imputation using unpaired imprecise auxiliary data: Theory and application to PM2.5 estimation**. *ACM Transactions on Knowledge Discovery from Data*, 18(3):1–26, 2024.
- **Extreme event discovery with self-attention for PM2.5 anomaly prediction**. *IEEE Intelligent Systems*, 38(2):36–45, 2023.
- **Building cybersecurity ontology for understanding and reasoning adversary tactics and techniques**. *2022 IEEE International Conference on Big Data (Big Data)*, 4266–4274, 2022.
- **Numerical simulation for flow of rolling piston type of rotary compressor**. *Energies*, 13(10):2526, 2020.
- **The influence factors on heat transfer performance of loop thermosyphon system**. *Transactions of the Canadian Society for Mechanical Engineering*, 40(5):947–958, 2016.

---

## Research Map

```text
Agent / system telemetry
        |
        +--> execution provenance -----------------> ExecWeave
        |
        +--> compact persistent reasoning state ---> SLM security memory
        |
        +--> ATT&CK techniques / campaign evidence
                    |
                    +--> sequence disentanglement ---> TGCM
                    +--> graph retrieval -----------> CONVERT
                    +--> incomplete-graph theory ---> CURVE
                    +--> graph generation ----------> GraphGeneration
