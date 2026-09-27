<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0221,25:A61E4D,50:B5541B,75:146356,100:0D0221&height=300&section=header" />

<br>

# RIYASHIKA NEDUNCHEZHIAN

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1400&color=B5541B&center=true&vCenter=true&width=800&lines=Founding+Engineer+%E2%80%94+OBLIQ.in;AI%2FLLM+Systems+Engineer;Agentic+Workflows+%C2%B7+RAG+%C2%B7+Evaluation" alt="Typing SVG" />

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D0221?style=for-the-badge&logo=linkedin&logoColor=B5541B&labelColor=0D0221)](https://linkedin.com/in/riyashika-nedunchezhian-a17227390)
&nbsp;
[![Email](https://img.shields.io/badge/Email-0D0221?style=for-the-badge&logo=gmail&logoColor=A61E4D&labelColor=0D0221)](mailto:riyashikanedunchezhian@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-0D0221?style=for-the-badge&logo=github&logoColor=146356&labelColor=0D0221)](https://github.com/riyashikanedunchezhian-lgtm)

<br>

![views](https://komarev.com/ghpvc/?username=riyashikanedunchezhian-lgtm&style=flat-square&color=B5541B&label=PROFILE+VIEWS)

</div>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:A61E4D,50:B5541B,100:146356&height=2" />

<br>

<div align="center">
<h3>I. OVERVIEW</h3>
</div>

<br>

<table align="center" width="92%">
<tr><td>

<div align="center">

*"Exploring open-source, systems & Bitcoin —*
*conquering myself to become a new person, one commit at a time."*

</div>

</td></tr>
</table>

<br>

Founding Engineer at **OBLIQ.in** and a computer science undergraduate (**B.E. CSE, CGPA 9.17/10**) working at the intersection of applied AI and production systems. My work sits across three layers: **agentic reasoning** — multi-node LangGraph systems that route, retrieve, and act; **evaluation infrastructure** — LLM-as-a-Judge harnesses that measure whether those systems can be trusted; and **backend engineering** — the audit trails, access controls, and idempotent pipelines that make AI-adjacent products safe to ship.

<br>

<div align="center">

| | | |
|:---:|:---:|:---:|
| **9.17 / 10** | **20+** | **6** |
| CGPA | Repositories | Developer Programs |

</div>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:146356,50:B5541B,100:A61E4D&height=2" />

<br>

<div align="center">
<h3>II. HOW I WORK</h3>
</div>

<br>

<table align="center" width="92%">
<tr>
<td width="33%" valign="top" align="center">

**Reason, then act**

Agentic systems should route to the cheapest sufficient model, log every reasoning step, and degrade gracefully when a tool fails — never fail silently.

</td>
<td width="33%" valign="top" align="center">

**Measure the measurer**

An LLM output is only as trustworthy as its evaluation. I build jury-based, bias-checked harnesses rather than trusting a single judge call.

</td>
<td width="33%" valign="top" align="center">

**Make it auditable**

Every system I ship — from webhook pipelines to forecasting dashboards — carries traceability: hashed inputs, append-only logs, deterministic replays.

</td>
</tr>
</table>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:A61E4D,50:B5541B,100:146356&height=2" />

<br>

<div align="center">
<h3>III. EXPERIENCE</h3>
</div>

<br>

<table align="center" width="92%">
<tr>
<td width="20%" valign="top">

<sub>SEPT 2026 —<br>PRESENT</sub>

</td>
<td width="80%">

**Founding Engineer, OBLIQ.in**

One of the earliest engineers on the founding team, building an audit-workflow platform for CA (accounting) firms with full-stack ownership across backend, data design, and security. Selected after independently designing and shipping a working prototype featuring multi-tenant data isolation, an append-only audit trail, and role-based access control.

`FastAPI` `SQLite` `Multi-Tenant Architecture` `RBAC` `Audit Trails`

</td>
</tr>
</table>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:146356,50:B5541B,100:A61E4D&height=2" />

<br>

<div align="center">
<h3>IV. SELECTED WORK</h3>
<sub>Agentic systems, evaluation infrastructure, and production-grade backends</sub>
</div>

<br>

<table align="center" width="92%">
<tr><td>

**01 — Multi-Agent Research Assistant**

A multi-node LangGraph agent — router, retrieval, tool-calling, synthesis — combining RAG over a ChromaDB vector store with agentic tool use across a calculator, web search, and code execution.

*Per-node token/cost tracking with cost-aware routing → cheap model for routing, stronger model for synthesis. Full reasoning-trace observability. Graceful degradation on tool failure.*

`Python` `LangGraph` `RAG` `ChromaDB` `FastAPI` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/multi-agent-research-assistant)

</td></tr>
<tr><td>

**02 — LLM Evaluation Harness**

An LLM-as-a-Judge system scoring outputs across five rubric dimensions using three-judge jury aggregation to reduce single-judge variance and detect position bias.

*3x latency reduction via parallelized judging. Quality, latency, and per-call cost tracked across Claude and GPT variants on 25 test prompts. Live Streamlit dashboard visualizing tradeoffs.*

`Python` `LLM-as-a-Judge` `Claude & GPT APIs` `Streamlit` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/llm-evaluation-harness)

</td></tr>
<tr><td>

**03 — Agentic Debugger**

An autonomous coding agent that reads a codebase, locates bugs via failing pytest suites, writes fixes, and verifies them by rerunning tests before declaring success.

*Sandboxed tool-execution loop — list_files, read_file, write_file, run_tests, finish — with guardrails against path traversal and test-tampering, plus full JSON tracing.*

`Python` `LLM Tool-Use` `Agent Design` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/agentic-debugger)

</td></tr>
<tr><td>

**04 — Traceable Sales Forecasting Dashboard**

A full-stack forecasting system on the Rossmann Store Sales dataset (1M+ rows, 1,115 stores), using a Prophet model with holiday and promotion regressors.

*54% MAE reduction versus a moving-average baseline (10.8% vs. 24.4% MAPE). A traceability layer hashes every forecast's exact input data via SHA-256, with a per-run /explain API for deterministic, reproducible outputs.*

`Python` `FastAPI` `Prophet` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/traceable-sales-forecasting)

</td></tr>
<tr><td>

**05 — Webhook Notification Hub**

A production-style webhook processing system verifying GitHub events via HMAC-SHA256 with constant-time comparison, queued through Redis and Celery for decoupled async processing.

*Idempotency via delivery-ID and Redis TTL cache, a sliding-window rate limiter, and exponential-backoff retries. Real-time event dashboard, containerized with Docker.*

`FastAPI` `Redis` `Celery` `Docker` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/web-hook-notification-hub)

</td></tr>
<tr><td>

**06 — Kinfolk — Family Oral History Story Studio**

An AI-assisted storytelling app, built with MVVM and Clean Architecture, that records family interviews and uses the Gemini API to transcribe, polish narratives, and extract pull-quotes into keepsake cards.

*Offline-first Room persistence, custom audio waveform recording and playback, chaptered digital memory-book export.*

`Kotlin` `Compose` `Room` `Gemini` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/kinfolk)

</td></tr>
<tr><td>

**07 — StudyMate — Student Study Planner**

An offline-first Android app (MVVM, Kotlin StateFlow/Coroutines) featuring a Pomodoro focus timer, subject and task management, study analytics, and streak tracking — with a parallel Flutter/Dart implementation shipped alongside it.

`Kotlin` `Jetpack Compose` `Flutter/Dart` · [→ Repository](https://github.com/riyashikanedunchezhian-lgtm/Study-mate)

</td></tr>
</table>

<br>

<div align="center">

[![View all repositories](https://img.shields.io/badge/View_All_Repositories-0D0221?style=for-the-badge&logo=github&logoColor=B5541B&labelColor=0D0221)](https://github.com/riyashikanedunchezhian-lgtm?tab=repositories)

</div>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:A61E4D,50:B5541B,100:146356&height=2" />

<br>

<div align="center">
<h3>V. TECHNICAL SURFACE</h3>
</div>

<br>

<table align="center" width="92%">
<tr>
<td width="25%" valign="top">

**Languages**

Python · Kotlin
JavaScript · Go · SQL

</td>
<td width="25%" valign="top">

**AI / LLM**

Anthropic Claude · OpenAI
Gemini · LangGraph
RAG · ChromaDB

</td>
<td width="25%" valign="top">

**Backend**

FastAPI · Flask
Redis · Celery
MongoDB · Docker

</td>
<td width="25%" valign="top">

**ML & Mobile**

TensorFlow · PyTorch
scikit-learn · Prophet
Kotlin Compose · Flutter

</td>
</tr>
</table>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:146356,50:B5541B,100:A61E4D&height=2" />

<br>

<div align="center">
<h3>VI. GITHUB ANALYTICS</h3>
</div>

<br>

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=riyashikanedunchezhian-lgtm&show_icons=true&theme=gruvbox&hide_border=true&count_private=true&bg_color=0D0221&title_color=B5541B&icon_color=A61E4D" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=riyashikanedunchezhian-lgtm&layout=compact&theme=gruvbox&hide_border=true&bg_color=0D0221&title_color=B5541B" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=riyashikanedunchezhian-lgtm&theme=gruvbox&hide_border=true&background=0D0221&ring=A61E4D&fire=B5541B" />

<br>

<img src="https://github-profile-trophy.vercel.app/?username=riyashikanedunchezhian-lgtm&theme=gruvbox&no-frame=true&row=1&column=6&margin-w=8" />

</div>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:A61E4D,50:B5541B,100:146356&height=2" />

<br>

<div align="center">
<h3>VII. PROGRAMS & AFFILIATIONS</h3>
</div>

<br>

<div align="center">

AMD Developer Program &nbsp;·&nbsp; NVIDIA Developer Program &nbsp;·&nbsp; 6G Developer Program
&nbsp;&nbsp;/&nbsp;&nbsp;
FOSSASIA &nbsp;·&nbsp; FOSS CIT Technical Team &nbsp;·&nbsp; Google Product Expert

</div>

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:146356,50:B5541B,100:A61E4D&height=2" />

<br>

<div align="center">
<h3>VIII. CONTRIBUTION ACTIVITY</h3>
</div>

<br>

<div align="center">
<img src="https://raw.githubusercontent.com/riyashikanedunchezhian-lgtm/riyashikanedunchezhian-lgtm/output/github-contribution-grid-snake-dark.svg" />
</div>

<br><br>

<div align="center">

**Currently exploring:** open-source · distributed systems · Bitcoin

<sub>[Let's build something](mailto:riyashikanedunchezhian@gmail.com)</sub>

</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0221,25:A61E4D,50:B5541B,75:146356,100:0D0221&height=200&section=footer" />
