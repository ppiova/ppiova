<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=Pablo%20Piovano&fontSize=54&fontAlignY=38&fontColor=ffffff&animation=fadeIn" alt="header" />

### Microsoft MVP in AI · 🐳 Docker Captain · Director of AI · Community Leader · Author

Shipping AI agents, enterprise GenAI and **signed, multi-arch, SBOM-attested container images** — built on **Azure AI**, **Microsoft Foundry**, **MCP** and **Docker**.

[![Microsoft MVP](https://img.shields.io/badge/Microsoft-MVP_in_AI-0078D4?logo=microsoft&logoColor=white)](https://mvp.microsoft.com/en-us/PublicProfile/5004753)
[![Docker Captain](https://img.shields.io/badge/Docker-Captain-2496ED?logo=docker&logoColor=white)](https://www.docker.com/contributors/pablo-piovano/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pablo_Piovano-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ppiova/)
[![X / Twitter](https://img.shields.io/badge/X-@ppiova-000000?logo=x&logoColor=white)](https://twitter.com/ppiova)
[![dev.to](https://img.shields.io/badge/dev.to-ppiova-0A0A0A?logo=devdotto&logoColor=white)](https://dev.to/ppiova)
[![Meetup](https://img.shields.io/badge/Meetup-.NET_Baires-ED1C40?logo=meetup&logoColor=white)](https://www.meetup.com/es-es/net-baires/)
[![Book](https://img.shields.io/badge/Book-AI_102_Guide-FF9900?logo=amazon&logoColor=white)](https://a.co/d/0hJv775S)
[![GHCR](https://img.shields.io/badge/GHCR-ppiova-2496ED?logo=github&logoColor=white)](https://github.com/ppiova?tab=packages)

</div>

---

> **Mission.** Make enterprise-grade AI samples that teams can _actually_ trust: reproducible, auditable, signed. No "works on my laptop" — everything ships as a multi-arch OCI image with SBOM and SLSA provenance, so security reviews become a one-liner.

---

## ⚡ Try it — and verify it — in 30 seconds

```bash
# Run a signed, multi-arch image (Blazor chat UI from the Docker Model Runner lab)
docker run --rm -p 8080:8080 ghcr.io/ppiova/docker-model-runner-lab/blazor-chat:latest
# then open http://localhost:8080
```

Every image is multi-arch, SBOM-attested and carries keyless-signed SLSA provenance — verify any of them end-to-end:

```bash
# Multi-arch manifest + attached SBOM & SLSA provenance
docker buildx imagetools inspect ghcr.io/ppiova/docker-model-runner-lab/blazor-chat:latest

# Verify the keyless-signed build provenance (GitHub OIDC, via Sigstore)
gh attestation verify oci://ghcr.io/ppiova/docker-model-runner-lab/blazor-chat:latest --owner ppiova
```

---

<div align="center">

### 🚢 Shipping in the open

**12 featured repos** · **1 app on the Microsoft Store** · **6 signed images on GHCR** · **SBOM + SLSA provenance** · **multi-arch (amd64 / arm64)**

![GHCR](https://img.shields.io/badge/GHCR-published-2496ED?logo=github&logoColor=white)
![SBOM](https://img.shields.io/badge/SBOM-SPDX-4C1?logo=linuxfoundation&logoColor=white)
![Provenance](https://img.shields.io/badge/SLSA-provenance-1E90FF?logo=slsa&logoColor=white)
![Multi-arch](https://img.shields.io/badge/multi--arch-amd64_%7C_arm64-0db7ed?logo=docker&logoColor=white)
![Signed](https://img.shields.io/badge/Sigstore-signed_provenance-000?logo=sigstore&logoColor=white)
![CI](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

</div>

---

## 🏆 Recognition

| | |
|---|---|
| 🏅 **Microsoft MVP in AI** | [Public profile](https://mvp.microsoft.com/en-us/PublicProfile/5004753) — MVP since 2022 |
| 🐳 **Docker Captain** | [Docker profile](https://www.docker.com/contributors/pablo-piovano/) — recognized for expertise in containers & secure software supply chain |
| 📘 **Author** | [AI-102 Certification Guide](https://a.co/d/0hJv775S) — Amazon |
| 🎤 **Community Leader** | Organizer at [.NET Baires](https://www.meetup.com/es-es/net-baires/), one of LATAM's largest .NET & AI communities — co-organizer of AgentCon Córdoba, VS Code Dev Days and Global Azure Latino |
| 💼 **Director of AI** | [OZ Digital Consulting](https://followoz.com/) — leading the AI Center of Excellence and enterprise GenAI adoption |

---

## 🛠️ What I Build

- AI agents, orchestration and multi-agent patterns
- Enterprise Generative AI on Azure AI and Microsoft Foundry
- MCP servers and developer workflows
- **Containerized AI tooling** — devcontainers, compose stacks, signed OCI images
- **Secure software supply chain for AI**: SBOMs, SLSA provenance, reproducible CI
- Reference implementations that scale from demo to production

---

## 🧰 Tech Stack

![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?logo=microsoft&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?logoColor=white)

---

## 📌 Featured Work

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


### 🪟 Published on the Microsoft Store

🔹 **[VMAzureApp — Cloud VM Manager for Windows](https://github.com/ppiova/VMAzureApp)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/VMAzureApp?style=flat&label=%E2%98%85) &nbsp;[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Get_it-0078D4?logo=microsoft&logoColor=white)](https://apps.microsoft.com/detail/9ngrmhhvcv4b)
Manage Azure VMs across all your subscriptions without opening the portal — start / stop / restart / hibernate with bulk actions, local scheduling and real-time power-state monitoring. WPF on .NET 10 with Entra ID sign-in, shipped as MSIX through GitHub Actions. [**Get it from the Microsoft Store**](https://apps.microsoft.com/detail/9ngrmhhvcv4b).


### 🐳 Docker-first series — Microsoft Agent Framework

🔹 **[agent-framework-devcontainer](https://github.com/ppiova/agent-framework-devcontainer)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/agent-framework-devcontainer?style=flat&label=%E2%98%85)
Single-agent starter. Multi-stage Dockerfile (Alpine, non-root), Dev Container / Codespaces ready, `docker compose up` and you're running.

🔹 **[mcp-docker-starter](https://github.com/ppiova/mcp-docker-starter)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/mcp-docker-starter?style=flat&label=%E2%98%85)
Polyglot compose: Python **FastMCP** server + .NET Agent Framework client, connected via SSE over a private bridge network. Service discovery, healthchecks, non-root everywhere.

🔹 **[ai-agents-compose-stack](https://github.com/ppiova/ai-agents-compose-stack)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/ai-agents-compose-stack?style=flat&label=%E2%98%85)
Multi-agent workflow (Researcher → Writer) with Microsoft Agent Framework, **OpenTelemetry + Aspire Dashboard** observability — fully in Docker Compose. Published image ships multi-arch with SBOM + SLSA provenance.


### 🐳 Docker Model Runner — run LLMs locally

🔹 **[docker-model-runner-lab](https://github.com/ppiova/docker-model-runner-lab)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/docker-model-runner-lab?style=flat&label=%E2%98%85)
Hands-on lab for **Docker Model Runner** — run LLMs locally behind an OpenAI-compatible API with .NET and Docker Compose. No cloud, no API keys, nothing leaves your machine.

🔹 **[docker-model-runner-multi-sdk-demo](https://github.com/ppiova/docker-model-runner-multi-sdk-demo)** &nbsp;![stars](https://img.shields.io/github/stars/ppiova/docker-model-runner-multi-sdk-demo?style=flat&label=%E2%98%85)
One endpoint, three SDKs: DMR serves the same local model through **OpenAI, Anthropic and Ollama** formats on a single port — dev/prod parity with Microsoft Foundry, six runnable Python + .NET examples.


---

## 🔐 Container Supply Chain

> 🐳 As a **[Docker Captain](https://www.docker.com/contributors/pablo-piovano/)**, I focus on making containers reproducible, portable and trustworthy for real AI workloads — the practices below are exactly what that recognition is about.

Every image **listed below** ships from **[GitHub Actions](https://github.com/ppiova?tab=packages)** with:

| Guarantee | How |
|---|---|
| **Multi-arch** | `docker buildx` — `linux/amd64` + `linux/arm64` |
| **SBOM** | SPDX attestation attached (buildx `sbom: true`) |
| **Provenance** | SLSA build provenance attached (buildx `provenance: true`) |
| **Signed** | Keyless build-provenance attestation via GitHub OIDC — Sigstore (`actions/attest-build-provenance`) |
| **Reproducible** | Pinned bases, deterministic builds in GitHub Actions |

### Published images

| # | Image | Source |
|---|---|---|
| 1 | `ghcr.io/ppiova/agent-framework-devcontainer` | [agent-framework-devcontainer](https://github.com/ppiova/agent-framework-devcontainer) |
| 2 | `ghcr.io/ppiova/mcp-docker-starter/mcp-server` | [mcp-docker-starter](https://github.com/ppiova/mcp-docker-starter) |
| 3 | `ghcr.io/ppiova/mcp-docker-starter/agent-client` | [mcp-docker-starter](https://github.com/ppiova/mcp-docker-starter) |
| 4 | `ghcr.io/ppiova/ai-agents-compose-stack` | [ai-agents-compose-stack](https://github.com/ppiova/ai-agents-compose-stack) |
| 5 | `ghcr.io/ppiova/docker-model-runner-lab/compose-api` | [docker-model-runner-lab](https://github.com/ppiova/docker-model-runner-lab) |
| 6 | `ghcr.io/ppiova/docker-model-runner-lab/blazor-chat` | [docker-model-runner-lab](https://github.com/ppiova/docker-model-runner-lab) |

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

# Verify the keyless-signed build provenance (GitHub OIDC, via Sigstore)
gh attestation verify oci://ghcr.io/ppiova/<image>:latest --owner ppiova
```

</details>

> **Why this matters.** Enterprises can't deploy unsigned samples. Shipping every image with SBOM + provenance turns "interesting demo" into "something I can put a ticket on."

---

## 🎤 Speaking & Teaching

Regular speaker at **Microsoft Reactor**, Microsoft Ignite, Microsoft Build and community events across LATAM. Highlights:

- 🎙️ [**GitHub Copilot CLI & AI Agents**](https://www.youtube.com/watch?v=3lkcGkG8Vxg) — Microsoft Reactor · 2026
- 🎙️ [**Innovaciones clave en Microsoft Fabric & Microsoft Foundry**](https://www.youtube.com/watch?v=lKeGHSiPMw0) — Microsoft Reactor · 2026
- 🎙️ [**Crea tus propios Agentes de IA con Azure AI Foundry**](https://www.youtube.com/watch?v=dklTcCMSLsU) — Microsoft Reactor · 2026
- 📺 [**.NET AI Community Standup — Ignite Highlights + Custom Avatar Deep Dive**](https://www.youtube.com/live/QLeFHFGLwa8) — official `dotnet` channel · 2025 — live deep dive of [AI-Custom-Avatar](https://github.com/ppiova/AI-Custom-Avatar) (.NET 10 + Blazor + Aspire)
- 🧪 **Lab Proctor** — [Microsoft Ignite 2025](https://www.linkedin.com/posts/ppiova_msignite-microsoftfoundry-aiagents-activity-7397466189163065344-SpNC/) & [Microsoft Build 2025](https://www.linkedin.com/posts/lbugnion_so-this-week-was-intense-my-team-produced-activity-7332058591065018369-JmU2/) · LAB324: Azure AI Foundry
- 🎤 [**Global AI Bootcamp 2025 — Buenos Aires Keynote**](https://www.youtube.com/live/8_t0GO-PJgk) — 2025

<details>
<summary>📚 <b>More sessions & community events (2023–2026)</b></summary>

### Microsoft Reactor

- 🎙️ [**Lo mejor de Microsoft Build 2025**](https://www.youtube.com/live/9X3F7GJZhz8) — 2026
- 🎙️ [**Integración de MCP con LLMs**](https://reactor.microsoft.com/es-es/reactor/events/26167/) — 2025

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
- 🧪 **Lab Proctor** — Microsoft Ignite 2024 · [LAB402-R1: Multimodal Generative AI](https://www.linkedin.com/posts/aliciamoniz_msignite-ugcPost-7265116994973179905-VssH)
- Contributor — [Microsoft Build 2025](https://build.microsoft.com) · [Microsoft Ignite 2025](https://ignite.microsoft.com)

### Community & Conferences
- 🎤 [**AgentCon Córdoba**](https://www.linkedin.com/posts/ppiova_ai-agents-azure-activity-7374822413731082240-yi98) · Co-organizer & speaker — 2025
- 🎤 [**VS Code Dev Day - Sunchales**](https://www.linkedin.com/posts/ppiova_vscodedevday-ai-githubcopilot-activity-7377780692564406272-b9nv) · Co-organizer & speaker — 2025
- 🎤 [**VS Code Dev Day Buenos Aires**](https://www.linkedin.com/posts/ppiova_vscodedevday-azureai-avatar-activity-7372898167958265856-1MCJ) · Speaker — 2025
- 🎤 [**Microsoft AI Workshop — Make AI Agents Work for You**](https://followoz.com/oz_events/microsoft-ai-workshop-make-ai-agents-work-for-you/) · Speaker — 2025

</details>

---

## ✍️ Writing & Content

📘 [**AI-102 Certification Guide**](https://a.co/d/0hJv775S) — practical guide for building real-world solutions with Azure AI, Generative AI and Microsoft Foundry.

📝 Recent articles:
- [Docker Model Runner: Models Are the New Containers](https://www.linkedin.com/pulse/docker-model-runner-models-new-containers-pablo-piovano-ibljf/) — LinkedIn Pulse · 2026
- [Your engineers aren't the bottleneck anymore. Your org chart is.](https://www.linkedin.com/pulse/your-engineers-arent-bottleneck-anymore-org-chart-pablo-piovano-jiz4f/) — LinkedIn Pulse · 2026
- [Microsoft Just Retired Prompt Flow. Don't Mistake This for a Migration Story.](https://www.linkedin.com/pulse/microsoft-just-retired-prompt-flow-dont-mistake-story-pablo-piovano-6fgvf/) — LinkedIn Pulse · 2026
- [The End of All-You-Can-Eat AI: How April 2026 Killed the Flat-Rate Era for Developers](https://dev.to/ppiova/the-end-of-all-you-can-eat-ai-how-april-2026-killed-the-flat-rate-era-for-developers-5260) — `dev.to` · 2026
- [Workflows en Microsoft Foundry](https://dev.to/ppiova/workflows-en-microsoft-foundry-1e5k) — `dev.to`

Full technical series on **[dev.to](https://dev.to/ppiova)** and **[LinkedIn](https://www.linkedin.com/in/ppiova/recent-activity/articles/)** — covering Azure AI, Agents, MCP, Foundry and containerized AI.

---

## 🤝 Open Source Contributions

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

<div align="center">

_Focused on making AI practical, verifiable and usable for real-world applications._

</div>
