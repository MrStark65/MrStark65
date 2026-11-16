<div align="center">

<img src="assets/header.gif" width="760" alt="Lakshay Singh — animated introduction" />

# Lakshay Singh

### Backend Development · Systems Integration · Applied AI

**Developer Apprentice at NEC India** · Building dependable software, APIs, and automation.

[![GitHub](https://img.shields.io/badge/GitHub-MrStark65-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MrStark65)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshay-singh-2a7755276/)
[![Open Source](https://img.shields.io/badge/Open_Source-Public_PRs-3B82F6?style=for-the-badge&logo=git&logoColor=white)](https://github.com/pulls?q=is%3Apr+author%3AMrStark65)

</div>

---

## About me

I work on **backend systems, enterprise integrations, infrastructure automation, and AI-enabled applications**. My engineering interests are **reliable services, clear APIs, fault recovery, operational monitoring, and practical machine learning**.

- **Currently:** Developer Apprentice at **NEC India**, working on the Delhi Safe City Project
- **Core strengths:** Python, FastAPI, SQL, C#/.NET, integrations, automation
- **Exploring:** LLM applications, retrieval-augmented generation, open-source backend engineering
- **Next milestone:** Meaningful open-source contributions and **GSoC 2027** preparation

## Engineering experience

**NEC India | Developer Apprentice | Delhi Safe City Project**

<table>
<tr>
<td valign="top" width="50%">

**Integration platform & backend services**

- Designed and developed a separate **ERSS integration platform**
- Created an **IIS operations dashboard** and **Windows worker service**
- Worked on **durable incident queuing, retries, idempotency, health checks, and diagnostics**
- Implemented worker leadership and designed active/standby failover

</td>
<td valign="top" width="50%">

**Enterprise integrations**

- Worked with **Genetec Mission Control, WebSDK, CAD**, and related integration workflows
- Built and tested connectivity and service-integration paths
- Focused on monitoring, error handling, and operational visibility

</td>
</tr>
<tr>
<td valign="top">

**Face Attendance System**

- Designed and developed a **production-deployed** application
- Face-based check-in/out and liveness verification
- Employee administration, shift/leave workflows, offline synchronization, and reporting

</td>
<td valign="top">

**Infrastructure & camera automation**

- Python-based **network/switch audits**, configuration checks, and structured Excel reporting
- Device connectivity troubleshooting and validation
- Browser-driven camera configuration automation using **Playwright**

</td>
</tr>
</table>

> **Project maturity:** The ERSS development dashboard, worker service, health endpoints and worker leadership are operational. Live incident processing and end-to-end failover validation remain pending; this is **not** described as a completed production rollout.

<details>
<summary><b>Visual: how I think about reliable integrations</b></summary>

```mermaid
flowchart LR
    A["Incoming event"] --> B["Validate & normalize"]
    B --> C["Durable processing"]
    C --> D{"Outcome"}
    D -->|Success| E["Record result"]
    D -->|Transient error| F["Retry policy"]
    F --> C
    D -->|Terminal error| G["Diagnostics & alert"]
    E --> H["Monitoring"]
    G --> H
```

*Conceptual engineering pattern — not an internal system diagram.*

</details>

## Technical toolkit

<div align="center">

**Languages & backend**

<img src="https://skillicons.dev/icons?i=python,cs,dotnet,fastapi&theme=dark" alt="Python, C sharp, .NET, FastAPI" />

`REST APIs` · `Pydantic` · `Uvicorn` · `Windows Services` · `SignalR`

**Databases & data**

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" height="45" alt="PostgreSQL" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" height="45" alt="Microsoft SQL Server" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" height="45" alt="pandas" />&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" height="45" alt="NumPy" />

**Machine learning & LLM development**

<img src="https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark" alt="PyTorch and scikit-learn" />

`Hugging Face Transformers` · `OpenAI API` · `LangChain` · `LangGraph` · `LlamaIndex` · `Sentence Transformers`

**Development & automation tools**

<img src="https://skillicons.dev/icons?i=git,github,linux,powershell,vscode&theme=dark" alt="Git, GitHub, Linux, PowerShell, VS Code" />

`Playwright` · `PowerShell` · `Excel Reporting` · `Integration Testing`

</div>

## Selected public repositories

<table>
<tr>
<td width="50%" valign="top">

### [AI-Powered Invoice Extractor](https://github.com/MrStark65/AI-Powered-Invoice-Extractor)
Document extraction and structured-data workflows.

`Python` `AI` `Document Processing`

</td>
<td width="50%" valign="top">

### [AI Minesweeper](https://github.com/MrStark65/ai-minesweeper)
Reasoning, constraint-solving and game logic.

`Algorithms` `Problem Solving`

</td>
</tr>
<tr>
<td valign="top">

### [Face Emotion Detection](https://github.com/MrStark65/Face-Emotion-Detection)
Computer vision and facial-expression recognition experiments.

`Computer Vision` `ML`

</td>
<td valign="top">

### [Movie Recommendation System](https://github.com/MrStark65/movie_recommended_system)
Recommendations and data-driven prediction experiments.

`Python` `Machine Learning`

</td>
</tr>
</table>

### Other engineering work

`ERSS Operations Dashboard` · `Face Attendance System` · `Network VLAN Auditing` · `SNMP Configuration Automation` · `ANPR Camera Configuration Automation`

*These include workplace projects; source code is not represented as publicly available.*

## Open source · GSoC 2027

Exploring the backend ecosystems of **[PyAirbyte](https://github.com/airbytehq/PyAirbyte)** and **[Meshery](https://github.com/meshery/meshery)** with an emphasis on reproducing bugs, understanding existing architecture, writing focused tests, and contributing maintainable fixes.

[**See my public pull requests →**](https://github.com/pulls?q=is%3Apr+author%3AMrStark65)

<sub>Exploration or issue investigation does not imply accepted or merged contributions.</sub>

## GitHub activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MrStark65&theme=github-compact&hide_border=true&area=true" width="95%" alt="GitHub contribution activity graph generated from public activity" />

</div>

<details>
<summary><b>Engineering principles</b></summary>

- **Reliability first:** define failure modes, retries, and recovery paths.
- **Make systems observable:** logs, health checks, meaningful error reporting.
- **Automate repeatable work:** reduce manual changes and produce auditable results.
- **Keep learning:** read source, reproduce bugs, test changes, welcome review.

</details>

---

<div align="center">

**Build carefully. Test edge cases. Keep improving.**

<sub>Confidential endpoints, internal network details, credentials, employee data, and proprietary source code are intentionally omitted.</sub>

</div>
