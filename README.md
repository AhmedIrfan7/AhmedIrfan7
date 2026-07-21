<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2c47,100:238636&height=210&section=header&text=AHMED%20IRFAN&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=Agentic%20AI%20Engineer&descAlignY=62&descSize=20&fontAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=720&lines=agent.route(query)+%E2%86%92+agent.retry()+%E2%86%92+agent.ground();I+design+the+graph+agents+reason+through.;I+build+the+pipes+that+keep+them+honest.;I+ship+the+thing+a+real+user+can+click." alt="Typing SVG" />

<br/>

<a href="mailto:ahmedirfancodes@gmail.com"><img src="https://img.shields.io/badge/-ahmedirfancodes%40gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335" /></a>
<a href="https://github.com/AhmedIrfan7?tab=repositories"><img src="https://img.shields.io/badge/-24%20public%20repos-0d1117?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/ahmed-irfan-20351b288/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logoColor=white" /></a>

</div>

<br/>

<p align="center"><i>BSCS @ FAST NUCES, Islamabad — currently in progress · open to freelance &amp; full-time work</i></p>

<div align="center">

━━━━━━━━━  &nbsp; **if it doesn't deploy, it doesn't count** &nbsp;  ━━━━━━━━━

</div>

<br/>

## `01` &nbsp; the pipeline

Everything below is one shape, repeated: an idea goes in, agents reason over it, and something a stranger can click comes out the other end.

<div align="center">

<table>
<tr>
<td align="center" width="25%">

**REASON**
<br/><sub>design the graph</sub>
<br/><br/>
<img src="https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-Anthropic-0d1117?style=flat-square&logo=anthropic&logoColor=D4A27F"/><br/>
<img src="https://img.shields.io/badge/-OpenAI-0d1117?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/-Groq%20%2F%20LLaMA-F55036?style=flat-square"/>

</td>
<td align="center" width="25%">

**GROUND**
<br/><sub>keep it honest</sub>
<br/><br/>
<img src="https://img.shields.io/badge/-RAG-0d1117?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-FAISS-0d1117?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/-Pinecone-0d1117?style=flat-square"/>

</td>
<td align="center" width="25%">

**ORCHESTRATE**
<br/><sub>wire it together</sub>
<br/><br/>
<img src="https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-WebSocket-0d1117?style=flat-square"/><br/>
<img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

</td>
<td align="center" width="25%">

**SHIP**
<br/><sub>make it real</sub>
<br/><br/>
<img src="https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-React-0d1117?style=flat-square&logo=react&logoColor=61DAFB"/><br/>
<img src="https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>

</td>
</tr>
</table>

</div>

<br/>

---

<br/>

## `02` &nbsp; six systems, running

<sub>Every metric here is real — pulled from the repo's own README, not decoration.</sub>

<br/>

<table width="100%">
<tr>
<td width="60%" valign="top">

**[Dental Clinic RAG Voice Assistant](https://github.com/AhmedIrfan7/n8n_dental_rag_orchestration)**
<br/>
A voice-and-text AI receptionist as a **10-workflow multi-agent system in n8n**. Give it a clinic URL — it scrapes, extracts facts, then fans a query out to pricing / booking / FAQ agents **in parallel** and merges the replies.

</td>
<td width="40%" valign="top" align="right">

<sub>hallucination evals</sub> **14/14 pass**
<br/>
<sub>workflows</sub> **10, authenticated**
<br/>
`n8n` `Qdrant` `Postgres` `Voice`

</td>
</tr>
<tr><td colspan="2"><sub>&nbsp;</sub></td></tr>
<tr>
<td width="60%" valign="top">

**[Multi-Agent Research Assistant](https://github.com/AhmedIrfan7/multi-agent-research-assistant)**
<br/>
Four **LangGraph** agents — Clarity, Research, Validator, Synthesis — that route between each other on confidence scores and pause to ask when a question is ambiguous, before streaming the answer word-by-word.

</td>
<td width="40%" valign="top" align="right">

<sub>coordinated agents</sub> **4**
<br/>
<sub>response delivery</sub> **SSE, live**
<br/>
`LangGraph` `FastAPI` `React 19` `Anthropic`

</td>
</tr>
<tr><td colspan="2"><sub>&nbsp;</sub></td></tr>
<tr>
<td width="60%" valign="top">

**[PEERLESS.AI](https://github.com/AhmedIrfan7/PeerLess.AI)** — National AI Hackathon '26
<br/>
Seven agents that surface research-integrity concerns in scientific papers — GRIM checks, statcheck p-value recomputation, DOI verification against Crossref. Findings only, never verdicts.

</td>
<td width="40%" valign="top" align="right">

<sub>specialized agents</sub> **7**
<br/>
<sub>review model</sub> **human-in-the-loop**
<br/>
`Streamlit` `Groq` `LLaMA-3.3` `Crossref`

</td>
</tr>
<tr><td colspan="2"><sub>&nbsp;</sub></td></tr>
<tr>
<td width="60%" valign="top">

**[Enterprise Agentic Workflow Engine](https://github.com/AhmedIrfan7/Enterprise_Agentic_Workflow_Engine)**
<br/>
A **LangChain AgentExecutor** driving web, file, and knowledge tools live, streaming every step over WebSocket to a real-time dashboard with per-session cost tracking.

</td>
<td width="40%" valign="top" align="right">

<sub>search</sub> **FAISS-indexed**
<br/>
<sub>execution</sub> **live over WebSocket**
<br/>
`LangChain` `React 18` `SQLite`

</td>
</tr>
<tr><td colspan="2"><sub>&nbsp;</sub></td></tr>
<tr>
<td width="60%" valign="top">

**[ResumeIQ](https://github.com/AhmedIrfan7/hr_resume_screening)** — [**live demo ↗**](https://resume-iq-by-ahmed-irfan.vercel.app/)
<br/>
A two-stage pipeline extracts a structured candidate profile, scores it against the role, and hands HR an AI-drafted reply — that **never sends without a human click**.

</td>
<td width="40%" valign="top" align="right">

<sub>pipeline</sub> **extract → score**
<br/>
<sub>deployment</sub> **live on Vercel**
<br/>
`n8n` `Next.js` `OpenAI` `Gmail API`

</td>
</tr>
<tr><td colspan="2"><sub>&nbsp;</sub></td></tr>
<tr>
<td width="60%" valign="top">

**[German Driving-School Chatbot](https://github.com/AhmedIrfan7/RagPipelineChatBot-GermanDataset)**
<br/>
A bilingual pricing bot built on one rule: **it must never guess a price.** Every number is read verbatim from a verified store and cross-checked against the source PDF.

</td>
<td width="40%" valign="top" align="right">

<sub>price accuracy</sub> **100%**
<br/>
<sub>test suite</sub> **80, all passing**
<br/>
`RAG` `Docker` `DE / EN`

</td>
</tr>
</table>

<br/>

---

<br/>

## `03` &nbsp; the automation line

<div align="center">

| | | |
|:---|:---|:---|
| **[Lead Generation System](https://github.com/AhmedIrfan7/LeadGenerationSystem)** <br/> [live dashboard ↗](https://lead-generation-system-alpha.vercel.app) | **[AI Support Router](https://github.com/AhmedIrfan7/AI_Support_Router_N8N)** | **[RAG Pipeline Chatbot](https://github.com/AhmedIrfan7/RAG_Pipeline_Chatbot_N8N)** |
| A sheet row becomes a scraped, redesigned, deployed preview site. Zero manual steps, idempotent by construction. | A local model classifies incoming Gmail and routes it to the right team. | Watches a Drive folder, indexes new docs into Pinecone, answers questions over them. |
| `n8n` `GitHub API` | `n8n` `Local LLM` | `n8n` `Pinecone` |

</div>

<br/>

<details>
<summary><b>&nbsp;:file_folder: everything else in the repo</b></summary>
<br/>

| Project | What it is |
|:--|:--|
| **[UrbanFix](https://github.com/AhmedIrfan7/UrbanFix_WebApp)** · [live ↗](https://urbanfix-eight.vercel.app) | Civic issue tracker — citizens pin problems on a live map, admins manage via dashboard |
| **[LinkedIn Content Creator](https://github.com/AhmedIrfan7/LinkedInContentCreatorN8N)** | Sheets topics → Tavily research → AI-drafted posts, queued automatically |
| **[Customer Support Workflow](https://github.com/AhmedIrfan7/CustomerSupportWorkflow_N8N)** | Classifies and routes support email end-to-end |
| **[RACE QuizEngine](https://github.com/AhmedIrfan7/RACE-QuizEngine)** | Classical-ML reading comprehension on the RACE dataset — no LLM, just LR/SVM/NB |
| **[Super Mario Bros. in x86 Assembly](https://github.com/AhmedIrfan7/SuperMarioBros_MASM)** | Mario rebuilt at the register level — physics, collisions, day/night cycle |
| **[SmartCity Simulation](https://github.com/AhmedIrfan7/SmartCity-DS-Project)** | Custom graphs, heaps, hash tables — Dijkstra routing over a city map |
| **[Sonic Classic Heroes](https://github.com/AhmedIrfan7/SonicClassicHeroes)** | Momentum-based Sonic physics engine, C++ and SFML |

</details>

<br/>

---

<br/>

## `04` &nbsp; the range

<div align="center">
<sub>most people who build agents have never written a line of assembly — I move the whole stack</sub>
<br/><br/>

<img src="https://img.shields.io/badge/-x86%20Assembly%20%2F%20MASM-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

<br/><br/>

<img src="https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>

</div>

<br/>

---

<br/>

<div align="center">

### `05` &nbsp; open a channel

<sub>building with agents, RAG, or automation — or want the whole pipeline handled? I'd like to hear about it.</sub>

<br/>

[<img src="https://img.shields.io/badge/-email%20me-238636?style=for-the-badge&logo=gmail&logoColor=white"/>](mailto:ahmedirfancodes@gmail.com)
[<img src="https://img.shields.io/badge/-see%20every%20repo-181717?style=for-the-badge&logo=github&logoColor=white"/>](https://github.com/AhmedIrfan7?tab=repositories)
[<img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logoColor=white"/>](https://www.linkedin.com/in/ahmed-irfan-20351b288/)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:238636,50:1a2c47,100:0d1117&height=120&section=footer&animation=fadeIn" width="100%"/>
