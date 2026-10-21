<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1f3a,50:0f4c75,100:14b8a6&height=200&section=header&text=Mehadi%20Hasan%20(Eshad)&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Senior%20Tech%20Lead%20%C2%B7%20AI%20Engineer%20%C2%B7%20Forward%20Deployed%20Engineer&descAlignY=58&descSize=17" width="100%"/>

<a href="https://github.com/eshad"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3200&pause=900&color=14B8A6&center=true&vCenter=true&width=760&lines=Building+mission-critical+systems+for+15%2B+years;Airport+security+platforms+%E2%80%94+PSIM+%C2%B7+VHMS+%C2%B7+AOP;Production+GenAI%2C+Agentic+AI%2C+RAG+%26+LoRA+%2F+QLoRA+fine-tuning;Government+transport+%C2%B7+Fintech+%C2%B7+Healthtech" alt="Typing SVG"/></a>

<p>
<a href="https://linkedin.com/in/eshad-hasan"><img src="https://img.shields.io/badge/LinkedIn-eshad--hasan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://eshad.github.io/profile"><img src="https://img.shields.io/badge/Portfolio-eshad.github.io-0f4c75?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Based%20in-Kuala%20Lumpur-14b8a6?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img src="https://komarev.com/ghpvc/?username=eshad&style=for-the-badge&color=0b1f3a&label=Profile+views"/>
</p>

<p>
<a href="https://eshad.github.io/profile/assets/pdf/mehadieu.pdf"><img src="https://img.shields.io/badge/Resume-US%20%2F%20UK%20(PDF)-0b1f3a?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
<a href="https://eshad.github.io/profile/assets/pdf/mehadi.pdf"><img src="https://img.shields.io/badge/Resume-EU%20Format%20(PDF)-14b8a6?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
</p>

</div>

---

### 👨‍💻 About me

I'm a **Senior Tech Lead and AI Engineer** with **15+ years** of building systems that can't go down: airport security, government rail signalling, payments and healthcare. I work as a **Forward Deployed Engineer**: I sit with the client, learn how their operation really runs, and turn that into production software.

- 🛫 **Sr. Tech Lead @ Eleware Technology Sdn. Bhd.** (Sep 2026 – now): I lead core modules of KLIA's airport security platforms:
  - **PSIM** (Physical Security Information Management)
  - **VHMS** (Visitor & Vehicle Handling Management)
  - **AOP** (airport pass & permit platform)
- 🚆 **Senior Engineer & Lead @ [Guildford Integrated System (GIS)](https://www.guildfordsys.com/)** (Sep 2024 – now): I lead the LRT3, RTS and Smart Car Parking programmes for the Malaysia Government.
- 🧠 I build production **GenAI and Agentic AI**: LLM integration, RAG, LangChain / LangGraph and MCP. I also train my own models with **LoRA / QLoRA**: see **NeoHorse-Coder-4B** below.
- 🎓 I'm a **PhD candidate in Computer Science**. My MSc thesis was an AI-driven medical assistant.

### 🏢 Domains

![Aviation Security](https://img.shields.io/badge/Aviation%20Security-0b1f3a?style=flat-square)
![Government](https://img.shields.io/badge/Government%20%26%20Transport-0f4c75?style=flat-square)
![Fintech](https://img.shields.io/badge/Fintech%20%26%20Payments-14b8a6?style=flat-square)
![Healthtech](https://img.shields.io/badge/Healthtech-0d9488?style=flat-square)
![Blockchain](https://img.shields.io/badge/Blockchain-334155?style=flat-square)
![Carbon Credit](https://img.shields.io/badge/Carbon%20Credit%20%2F%20ESG-15803d?style=flat-square)
![iGaming](https://img.shields.io/badge/iGaming-7c3aed?style=flat-square)
![Enterprise](https://img.shields.io/badge/Enterprise%20ERP-475569?style=flat-square)

### 🛡️ What I'm building now: airport security platforms

| System | What it does | Stack |
|---|---|---|
| **PSIM** | One control-room console for alarms with SOP workflows, maps of cameras and doors, live and recorded video, cardholder tracking and server health | .NET 9 · ABP · Angular 20 · SignalR · SQL Server Always On |
| **VHMS** | Visitor passes, vehicle inspection with under-vehicle scanners (UVSS), card printing, access-control sync | .NET 10 · ABP · MAUI / Flutter verifier app |
| **AOP** | Airport pass and permit applications, e-vetting, blacklist screening, AI face-quality checks | .NET 10 · ABP · SenseTime face API |

They integrate Milestone XProtect video, Security Expert access control, UVSS scanners and SenseTime AI search, and run with DC/DR failover.

### 🐴 My own model: NeoHorse-Coder-4B

A **fine-tuned coding LLM** I trained for offline patch / fix / code-review work inside my local AI agents (OpenCode + a custom model router).

- **Base:** 4B hybrid linear-attention model (Qwen3.5 family). **35+ training iterations.**
- **Method:** **QLoRA** 4-bit NF4 (PEFT + bitsandbytes, r=32, α=64) on **5.4k** curated examples from my own commits, CommitPackFT and agent traces.
- **Infra:** trained on RunPod A40 and AWS L4 GPUs, exported to GGUF (llama.cpp Q4_K_M), served with llama-server. A v34 specialist handles test writing.

| Held-out eval | Base | NeoHorse-Coder |
|---|---|---|
| Grounded agent edits | 10% | **91%** |
| Right-tool use | 34% | **94%** |
| Decode speed (speculative) | 15 tok/s | **45 tok/s** |

### 🧠 AI engineering toolbox

| Area | Tools |
|---|---|
| **LLMs** | OpenAI · Claude · Gemini · Mistral · Ollama · vLLM · llama.cpp |
| **Agents & orchestration** | LangChain · LangGraph · LlamaIndex · Semantic Kernel · MCP · AutoGen · n8n |
| **Fine-tuning** | **LoRA · QLoRA** (4-bit NF4) · PEFT · Hugging Face Transformers · bitsandbytes · MLX · llama.cpp GGUF |
| **RAG & vectors** | Pinecone · Weaviate · Qdrant · Chroma · FAISS · Milvus · pgvector |
| **Cloud AI** | AWS Bedrock · Azure OpenAI · Vertex AI |
| **Evals & LLMOps** | LangSmith · Langfuse · RAGAS · Promptfoo |
| **AI pair programming** | Claude Code · GitHub Copilot · Gemini Code Assist · OpenAI Codex |

### 🧰 Tech stack

<p align="center">
<img src="https://skillicons.dev/icons?i=py,ts,js,cs,dotnet,java,cpp,go,kotlin,dart,php&perline=11"/><br/>
<img src="https://skillicons.dev/icons?i=angular,react,vue,flutter,nodejs,nestjs,fastapi,spring,laravel,graphql&perline=10"/><br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka,rabbitmq,aws,azure,gcp&perline=9"/><br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,ansible,linux,nginx,grafana,githubactions,jenkins,git,vim&perline=10"/>
</p>

### 🚀 Featured open source

| Project | Description |
|---|---|
| [**kafkatui**](https://github.com/eshad/kafkatui) | Terminal UI for Kafka. The LRT3 ops team uses it as their standard diagnostic tool |
| [**rabbitmq-tui**](https://github.com/eshad/rabbitmq-tui) | Terminal UI for RabbitMQ queues, exchanges and messages |
| [**mydesk**](https://github.com/eshad/mydesk) | Self-hosted, AnyDesk-style remote desktop. Replaced 3 commercial licences |
| [**macscp**](https://github.com/eshad/macscp) | Native macOS SFTP / SCP client (Swift / AppKit) |
| [**snmp-alarm**](https://github.com/eshad/snmp-alarm) | SNMP trap daemon for alarm pipelines |
| [**supercharge-build-challenge**](https://github.com/eshad/supercharge-build-challenge) | SuperCharge SG 2026: Telegram RAG chatbot, smart energy dashboard, AGV brain proposal |
| [**Redmine plugin suite**](https://github.com/eshad/redmine_turbo_nav) | 6 plugins: [turbo-nav](https://github.com/eshad/redmine_turbo_nav), [dark-mode](https://github.com/eshad/redmine_dark_mode), [forum-pdf](https://github.com/eshad/redmine_forum_pdf_email), [doc-pdf](https://github.com/eshad/redmine_document_pdf_email), [issue-emailer](https://github.com/eshad/issue_emailer_redmine), [custom-mail](https://github.com/eshad/custom_mail_redmine_plugin) |

### 📊 GitHub stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=eshad&show_icons=true&count_private=true&hide_border=true&bg_color=0b1f3a&title_color=14b8a6&icon_color=14b8a6&text_color=e2e8f0"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=eshad&layout=compact&hide_border=true&bg_color=0b1f3a&title_color=14b8a6&text_color=e2e8f0"/>
</p>
<p align="center">
<img src="https://streak-stats.demolab.com?user=eshad&hide_border=true&background=0b1f3a&ring=14b8a6&fire=14b8a6&currStreakLabel=14b8a6&sideLabels=e2e8f0&dates=94a3b8&currStreakNum=e2e8f0&sideNums=e2e8f0"/>
</p>
<p align="center">
<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=eshad&theme=tokyonight"/>
</p>

<div align="center">

> *"The weakest link in any chain of security is not the technology itself, but the person operating it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14b8a6,50:0f4c75,100:0b1f3a&height=110&section=footer" width="100%"/>

</div>
