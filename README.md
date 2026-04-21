<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=Pablo%20Piovano&fontSize=54&fontAlignY=38&fontColor=ffffff&animation=fadeIn" alt="header" />

### Microsoft MVP in AI · Director of AI · Community Leader · Author

Shipping AI agents, enterprise GenAI and **signed, multi-arch, SBOM-attested container images** — built on **Azure AI**, **Microsoft Foundry**, **MCP** and **Docker**.

[![Microsoft MVP](https://img.shields.io/badge/Microsoft-MVP_in_AI-0078D4?logo=microsoft&logoColor=white)](https://mvp.microsoft.com/en-us/PublicProfile/5004753)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pablo_Piovano-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ppiova/)
[![X / Twitter](https://img.shields.io/badge/X-@ppiova-000000?logo=x&logoColor=white)](https://twitter.com/ppiova)
[![dev.to](https://img.shields.io/badge/dev.to-ppiova-0A0A0A?logo=devdotto&logoColor=white)](https://dev.to/ppiova)
[![Meetup](https://img.shields.io/badge/Meetup-.NET_Baires-ED1C40?logo=meetup&logoColor=white)](https://www.meetup.com/es-es/net-baires/)
[![Book](https://img.shields.io/badge/Book-AI_102_Guide-FF9900?logo=amazon&logoColor=white)](https://a.co/d/0hJv775S)
[![GHCR](https://img.shields.io/badge/GHCR-ppiova-2496ED?logo=github&logoColor=white)](https://github.com/ppiova?tab=packages)
[![Profile views](https://komarev.com/ghpvc/?username=ppiova&label=Profile+views&color=0e75b6&style=flat)](https://github.com/ppiova)

</div>

---

> **Mission.** Make enterprise-grade AI samples that teams can _actually_ trust: reproducible, auditable, signed. No "works on my laptop" — everything ships as a multi-arch OCI image with SBOM and SLSA provenance, so security reviews become a one-liner.

---

## ⚡ Try it in 30 seconds

```bash
docker run --rm -p 8080:8080 ghcr.io/ppiova/mcp-docker-starter:latest
# then open http://localhost:8080
```

Every image below can be verified end-to-end:

```bash
cosign verify ghcr.io/ppiova/<image>:latest \
  --certificate-identity-regexp 'https://github.com/ppiova/.+' \
  --certificate-oidc-issuer 'https://token.actions.githubusercontent.com'
```

---

<div align="center">

### 🚢 Shipping in the open

**8 featured repos** · **7 signed images on GHCR** · **SBOM + SLSA provenance** · **multi-arch (amd64 / arm64)**

![GHCR](https://img.shields.io/badge/GHCR-published-2496ED?logo=github&logoColor=white)
![SBOM](https://img.shields.io/badge/SBOM-SPDX-4C1?logo=linuxfoundation&logoColor=white)
![Provenance](https://img.shields.io/badge/SLSA-provenance-1E90FF?logo=slsa&logoColor=white)
![Multi-arch](https://img.shields.io/badge/multi--arch-amd64_%7C_arm64-0db7ed?logo=docker&logoColor=white)
![Signed](https://img.shields.io/badge/cosign-signed-000?logo=sigstore&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

</div>

---

## 🏆 Recognition

| | |
|---|---|
| 🏅 **Microsoft MVP in AI** | [Public profile](https://mvp.microsoft.com/en-us/PublicProfile/5004753) — MVP since 2022 |
| 📘 **Author** | [AI-102 Certification Guide](https://a.co/d/0hJv775S) — Amazon |
| 🎤 **Community Leader** | Organizer at [.NET Baires](https://www.meetup.com/es-es/net-baires/) — one of LATAM's largest .NET communities |
| 💼 **Director of AI** | [OZ Digital Consulting](https://followoz.com/) — leading the AI Center of Excellence |

---

## What I Build

- AI agents, orchestration and multi-agent patterns
- Enterprise Generative AI on Azure AI and Microsoft Foundry
- MCP servers and developer workflows
- **Containerized AI tooling** — devcontainers, compose stacks, signed OCI images
- **Secure software supply chain for AI**: SBOMs, SLSA provenance, reproducible CI
- Reference implementations that scale from demo to production

---

## Tech Stack

![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?logo=microsoft&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Compose](https://img.shields.io/badge/Docker_Compose-2496ED?logo=docker&logoColor=white)
![Buildx](https://img.shields.io/badge/Buildx-multi--arch-2496ED?logo=docker&logoColor=white)
![Devcontainers](https://img.shields.io/badge/Devcontainers-007ACC?logo=visualstudiocode&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Cosign](https://img.shields.io/badge/Cosign-000?logo=sigstore&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?logoColor=white)

---

## Featured Work

🔹 **[mcp-servers-microsoft-ecosystem](https://github.com/ppiova/mcp-servers-microsoft-ecosystem)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/mcp-servers-microsoft-ecosystem?style=flat&label=%E2%98%85)
Community-curated catalog of **MCP servers** across the Microsoft ecosystem (Azure, M365, Fabric, Power Platform, GitHub, Copilot Studio) — complements the official [`microsoft/mcp`](https://github.com/microsoft/mcp) with community implementations, clients, starters and security guidance.

🔹 **[AgentFrameworkDemos](https://github.com/ppiova/AgentFrameworkDemos)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/AgentFrameworkDemos?style=flat&label=%E2%98%85)
AI agents, orchestration and real-world patterns with Microsoft Agent Framework on .NET.

🔹 **[AgentFX-MCP-MicrosoftLearn](https://github.com/ppiova/AgentFX-MCP-MicrosoftLearn)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/AgentFX-MCP-MicrosoftLearn?style=flat&label=%E2%98%85)
Reference integration between Agent Framework and the Microsoft Learn MCP Server.

🔹 **[TravelMCP](https://github.com/ppiova/TravelMCP)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/TravelMCP?style=flat&label=%E2%98%85)
End-to-end MCP server illustrating real-world tool workflows.

🔹 **[AzureOpenAI-EntraID-ConsoleApp](https://github.com/ppiova/AzureOpenAI-EntraID-ConsoleApp)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/AzureOpenAI-EntraID-ConsoleApp?style=flat&label=%E2%98%85)
Enterprise-grade Azure OpenAI auth with Entra ID — production-ready patterns.

🔹 **[AI-Custom-Avatar](https://github.com/ppiova/AI-Custom-Avatar)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/AI-Custom-Avatar?style=flat&label=%E2%98%85)
Azure AI Avatar Agent on .NET 10 + Blazor + .NET Aspire — Speech-to-Text, Azure OpenAI and a talking avatar with synchronized lip-sync. Built with [Bruno Capuano](https://github.com/elbruno).


### 🐳 Docker-first series — Microsoft Agent Framework

🔹 **[agent-framework-devcontainer](https://github.com/ppiova/agent-framework-devcontainer)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/agent-framework-devcontainer?style=flat&label=%E2%98%85)
Single-agent starter. Multi-stage Dockerfile (Alpine, non-root), Dev Container / Codespaces ready, `docker compose up` and you're running.

🔹 **[mcp-docker-starter](https://github.com/ppiova/mcp-docker-starter)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/mcp-docker-starter?style=flat&label=%E2%98%85)
Polyglot compose: Python **FastMCP** server + .NET Agent Framework client, connected via SSE over a private bridge network. Service discovery, healthchecks, non-root everywhere.


---

## 🔐 Container Supply Chain

Every image on **[ghcr.io/ppiova](https://github.com/ppiova?tab=packages)** ships with:

| Guarantee | How |
|---|---|
| **Multi-arch** | `docker buildx` — `linux/amd64` + `linux/arm64` |
| **SBOM** | SPDX attestation attached (`docker buildx --sbom=true`) |
| **Provenance** | SLSA build provenance (`--provenance=mode=max`) |
| **Signed** | Keyless `cosign` via GitHub OIDC |
| **Reproducible** | Pinned bases, deterministic builds in GitHub Actions |

### Published images

| # | Image | Source |
|---|---|---|
| 1 | `ghcr.io/ppiova/agentframeworkdemos` | [AgentFrameworkDemos](https://github.com/ppiova/AgentFrameworkDemos) |
| 2 | `ghcr.io/ppiova/agentfx-mcp-microsoftlearn` | [AgentFX-MCP-MicrosoftLearn](https://github.com/ppiova/AgentFX-MCP-MicrosoftLearn) |
| 3 | `ghcr.io/ppiova/travelmcp` | [TravelMCP](https://github.com/ppiova/TravelMCP) |
| 4 | `ghcr.io/ppiova/azureopenai-entraid-consoleapp` | [AzureOpenAI-EntraID-ConsoleApp](https://github.com/ppiova/AzureOpenAI-EntraID-ConsoleApp) |
| 5 | `ghcr.io/ppiova/ai-custom-avatar` | [AI-Custom-Avatar](https://github.com/ppiova/AI-Custom-Avatar) |
| 6 | `ghcr.io/ppiova/agent-framework-devcontainer` | [agent-framework-devcontainer](https://github.com/ppiova/agent-framework-devcontainer) |
| 7 | `ghcr.io/ppiova/mcp-docker-starter` | [mcp-docker-starter](https://github.com/ppiova/mcp-docker-starter) |

<details>
<summary>🔎 <b>Inspect any image</b></summary>

```bash
# Manifest + attestations
docker buildx imagetools inspect ghcr.io/ppiova/<image>:latest --format '{{ json . }}'

# SBOM
docker buildx imagetools inspect ghcr.io/ppiova/<image>:latest \
  --format '{{ json .SBOM }}'

# Provenance
docker buildx imagetools inspect ghcr.io/ppiova/<image>:latest \
  --format '{{ json .Provenance }}'

# Signature verification
cosign verify ghcr.io/ppiova/<image>:latest \
  --certificate-identity-regexp 'https://github.com/ppiova/.+' \
  --certificate-oidc-issuer 'https://token.actions.githubusercontent.com'
```

</details>

> **Why this matters.** Enterprises can't deploy unsigned samples. Shipping every image with SBOM + provenance turns "interesting demo" into "something I can put a ticket on."

---

## Currently

- 🔭 **Working on:** agent orchestration patterns, MCP tooling and containerized AI samples
- 🌱 **Learning:** advanced container orchestration and distributed agent runtimes
- 👯 **Looking to collaborate on:** OSS AI tooling, MCP servers, Docker + AI samples
- 💬 **Ask me about:** Azure AI, Agent Framework, the MVP journey, building community
- 📫 **Reach me at:** [LinkedIn](https://www.linkedin.com/in/ppiova/) · [X/Twitter](https://twitter.com/ppiova)

---

## Speaking & Teaching

Regular speaker at **Microsoft Reactor**, Microsoft Ignite, Microsoft Build and community events across LATAM. A selection:

### Microsoft Reactor

**🎤 Speaker — featured sessions**
- 🎙️ [**GitHub Copilot CLI & AI Agents**](https://www.youtube.com/watch?v=3lkcGkG8Vxg) — 2026
- 🎙️ [**Innovaciones clave en Microsoft Fabric & Microsoft Foundry**](https://www.youtube.com/watch?v=lKeGHSiPMw0) — 2026
- 🎙️ [**Crea tus propios Agentes de IA con Azure AI Foundry**](https://www.youtube.com/watch?v=dklTcCMSLsU) — 2026
- 🎙️ [**Lo mejor de Microsoft Build 2025**](https://www.youtube.com/live/9X3F7GJZhz8) — 2026
- 🎙️ [**Integración de MCP con LLMs**](https://reactor.microsoft.com/es-es/reactor/events/26167/) — 2025

**🧠 Sessions & contributor**

*Agentes & AI avanzada*
- 🤖 [**Introducción al Agent Framework y agentes individuales**](https://developer.microsoft.com/en-us/reactor/events/26463/) — 2025
- 🤖 [**Del Dato a la Inteligencia — Fabric + Foundry + Agents**](https://developer.microsoft.com/en-us/reactor/events/26004/) — 2025
- 🤖 [**Crea tus propios agentes (edición Reactor)**](https://developer.microsoft.com/en-us/reactor/events/25754/) — 2025

*Fundamentos de IA Generativa*
- 📘 [**Generative AI on Azure — The Fundamentals**](https://developer.microsoft.com/en-us/reactor/events/25063/) — 2025
- 📘 [**La base de la IA Generativa en Azure**](https://www.youtube.com/live/SQILlf0wkaY) — 2025
- 📘 [**Los Fundamentos de la IA Generativa en Azure**](https://www.youtube.com/watch?v=L1WvaVA4ftc) — 2025

*IA + .NET — Reactor LATAM series*
- 🧩 [**IA y .NET LATAM — Episodio 2**](https://www.youtube.com/live/kOLJlpqIO2o) — 2025
- 🧩 [**IA y .NET LATAM — Episodio 4**](https://www.youtube.com/live/jeC3VZLoJWU) — 2025

*Dev & AI tooling*
- 🛠️ [**VS Code Dev Days LATAM**](https://www.youtube.com/watch?v=O7jFJ38PQsQ) — 2025
- 🛠️ [**Trucos para automatizar tus proyectos con GitHub**](https://developer.microsoft.com/es-es/reactor/events/22779/) — 2024

*Series & panels*
- 📚 [**Season of AI for Developers (serie completa)**](https://techcommunity.microsoft.com/blog/educatordeveloperblog/season-of-ai-for-developers/4226639) — contributor
- 🎛️ [**Carrera y tecnología: AI (Panel)**](https://www.youtube.com/live/ItIRwZvQAJE) — 2023

### Microsoft Ignite & Build
- 🧪 **Lab Proctor** — Microsoft Ignite 2025 · [LAB324: Azure AI Foundry](https://www.linkedin.com/posts/ppiova_msignite-microsoftfoundry-aiagents-activity-7397466189163065344-SpNC/)
- 🧪 **Lab Proctor** — Microsoft Build 2025 · [LAB324: Azure AI Foundry](https://www.linkedin.com/posts/lbugnion_so-this-week-was-intense-my-team-produced-activity-7332058591065018369-JmU2/)
- 🧪 **Lab Proctor** — Microsoft Ignite 2024 · [LAB402-R1: Multimodal Generative AI](https://www.linkedin.com/posts/aliciamoniz_msignite-ugcPost-7265116994973179905-VssH)
- Contributor — [Microsoft Build 2025](https://build.microsoft.com) · [Microsoft Ignite 2025](https://ignite.microsoft.com)

### .NET Community
- 📺 [**.NET AI Community Standup — Ignite Highlights + Custom Avatar Deep Dive**](https://www.youtube.com/live/QLeFHFGLwa8) · official `dotnet` channel — 2025
   Covered Microsoft Ignite 2025 highlights and a live deep dive of the [AI-Custom-Avatar](https://github.com/ppiova/AI-Custom-Avatar) project — Azure AI Avatar on .NET 10 + Blazor + Aspire.

### Community & Conferences
- 🎤 [**Global AI Bootcamp 2025 — Buenos Aires Keynote**](https://www.youtube.com/live/8_t0GO-PJgk) — 2025
- 🎤 [**Global AI Bootcamp 2025 — Rosario · MCP: Model Context Protocol**](https://www.youtube.com/watch?v=2wgiWC4l7Cw) — 2025
- 🎤 [**AgentCon Córdoba**](https://www.linkedin.com/posts/ppiova_ai-agents-azure-activity-7374822413731082240-yi98) · Co-organizer & speaker — 2025
- 🎤 [**VS Code Dev Day Buenos Aires**](https://www.linkedin.com/posts/ppiova_vscodedevday-azureai-avatar-activity-7372898167958265856-1MCJ) · Co-organizer & speaker — 2025
- 🎤 [**Microsoft AI Workshop — Make AI Agents Work for You**](https://followoz.com/oz_events/microsoft-ai-workshop-make-ai-agents-work-for-you/) — 2025

---

## Writing & Content

📘 [**AI-102 Certification Guide**](https://a.co/d/0hJv775S) — practical guide for building real-world solutions with Azure AI, Generative AI and Microsoft Foundry.

📝 Recent articles:
- [Workflows en Microsoft Foundry](https://dev.to/ppiova/workflows-en-microsoft-foundry-1e5k) — `dev.to`
- [🔔 You're probably already using Responses API, you just don't know it yet](https://www.linkedin.com/pulse/youre-probably-already-using-responses-api-you-just-dont-piovano-hwpmf/) — LinkedIn Pulse
- [Azure OpenAI Realtime API + VoiceRAG](https://www.linkedin.com/pulse/azure-openai-realtime-api-voicerag-pablo-piovano-jgnmf) — LinkedIn Pulse
- [Azure OpenAI: Retiring GPT-4o (2024-05-13 & 2024-08-06) — What to Do](https://www.linkedin.com/pulse/azure-openai-retiring-gpt-4o-2024-05-13-2024-08-06-what-pablo-piovano-miolf) — LinkedIn Pulse
- [Azure Computer Vision Image Analysis: Retiring — What Actually Changes](https://www.linkedin.com/pulse/azure-computer-vision-image-analysis-retiring-actually-pablo-piovano-6jcff/) — LinkedIn Pulse
- [Microsoft Foundry & Agent Framework — Technical deep dive](https://www.linkedin.com/posts/ppiova_microsoftfoundry-responsesapi-microsoftagentframework-activity-7433603187938365440-91q1/)

Full technical series on **[dev.to](https://dev.to/ppiova)** and **[LinkedIn](https://www.linkedin.com/in/ppiova/recent-activity/articles/)** — covering Azure AI, Agents, MCP, Foundry and containerized AI.

---

## Open Source Contributions

Contributor to Microsoft and community OSS projects around AI and Agents, including:

- [`microsoft/agent-framework`](https://github.com/microsoft/agent-framework)
- [`microsoft/ai-agents-for-beginners`](https://github.com/microsoft/ai-agents-for-beginners)
- [`github/awesome-copilot`](https://github.com/github/awesome-copilot)
- [`microsoft/edgeai-for-beginners`](https://github.com/microsoft/edgeai-for-beginners)

---

## 🎓 Workshops & Engagements

Available for:

- **Hands-on workshops** — Azure AI Foundry · Agent Framework · MCP · Docker supply chain for AI
- **Conference talks & keynotes** — GenAI, Agents, secure container delivery
- **Advisory** — enterprise GenAI adoption, AI Center of Excellence setup

📫 **Reach out:** [LinkedIn](https://www.linkedin.com/in/ppiova/) · [X / Twitter](https://twitter.com/ppiova)

---

## Leadership & Community

**Director of AI at OZ Digital Consulting** — leading the AI Center of Excellence and driving enterprise GenAI adoption.

**Organizer at [.NET Baires](https://www.meetup.com/es-es/net-baires/)** — one of the largest .NET & AI communities in LATAM. Co-organizer of AgentCon Córdoba, VS Code Dev Days Córdoba, Global Azure Latino .NET Online, and Calendarios de Adviento IA.

Focused on making AI practical and usable for real-world applications.

---

## GitHub Stats

<div align="center">

![Pablo's GitHub stats](https://github-readme-stats.vercel.app/api?username=ppiova&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![GitHub Streak](https://streak-stats.demolab.com?user=ppiova&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ppiova&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

[![trophy](https://github-profile-trophy.vercel.app/?username=ppiova&theme=tokyonight&no-frame=true&column=7&margin-w=10)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Focus Areas

`AI Agents` `GenAI` `Azure AI` `Microsoft Foundry` `MCP` `RAG` `Docker` `Containers` `Supply Chain Security` `SBOM` `SLSA` `cosign` `Open Source`

---

## Connect

<div align="center">

[![MVP Profile](https://img.shields.io/badge/Microsoft_MVP-Profile-0078D4?logo=microsoft&logoColor=white)](https://mvp.microsoft.com/en-us/PublicProfile/5004753)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ppiova/)
[![X](https://img.shields.io/badge/X-@ppiova-000000?logo=x&logoColor=white)](https://twitter.com/ppiova)
[![dev.to](https://img.shields.io/badge/dev.to-ppiova-0A0A0A?logo=devdotto&logoColor=white)](https://dev.to/ppiova)
[![Meetup](https://img.shields.io/badge/.NET_Baires-Organizer-ED1C40?logo=meetup&logoColor=white)](https://www.meetup.com/es-es/net-baires/)
[![GHCR](https://img.shields.io/badge/GHCR-ppiova-2496ED?logo=github&logoColor=white)](https://github.com/ppiova?tab=packages)
[![Book](https://img.shields.io/badge/AI_102_Book-Amazon-FF9900?logo=amazon&logoColor=white)](https://a.co/d/0hJv775S)

</div>
