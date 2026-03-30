<p align="center">
  <strong>EU First</strong>
</p>

<h3 align="center">The open-source directory of EU-sovereign AI tools</h3>

<p align="center">
  A curated list of AI tools built, hosted, and governed within the EU.<br>
  Verified for origin. Organized by category. Community-maintained.<br><br>

</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</p>

---

**Currently tracking: 50+ tools across 16 categories**

---

## Why This List Exists

US cloud providers hold **85%** of the European cloud market. Over **74%** of European companies depend on US-based services for critical operations. Under the US CLOUD Act, American authorities can compel access to data stored by US companies — even when that data sits on EU soil.

The **EU AI Act** enforcement begins **August 2, 2026**. European companies adopting AI need to know which tools are built, hosted, and governed within EU jurisdiction — not just which ones claim GDPR compliance on a landing page.

This list brings those tools together in one place. Every entry is verified for EU origin.

---

## Contents

- [LLMs & Foundation Models](#llms--foundation-models)
- [Sovereign National LLMs](#sovereign-national-llms)
- [AI Chat & Assistants](#ai-chat--assistants)
- [Cloud & GPU Infrastructure](#cloud--gpu-infrastructure)
- [Vector Databases](#vector-databases)
- [AI Dev Tools & MLOps](#ai-dev-tools--mlops)
- [AI-Powered Productivity](#ai-powered-productivity)
- [Translation & NLP](#translation--nlp)
- [Search Engines](#search-engines)
- [Secure Communication](#secure-communication)
- [Privacy-First Analytics](#privacy-first-analytics)
- [Self-Hosted AI Stack](#self-hosted-ai-stack)
- [AI for Healthcare](#ai-for-healthcare)
- [AI for Finance](#ai-for-finance)
- [AI for Legal](#ai-for-legal)
- [AI for HR & Recruitment](#ai-for-hr--recruitment)
- [AI for Security & Compliance](#ai-for-security--compliance)
- [EU AI Act Resources](#eu-ai-act-resources)
- [EU Digital Sovereignty Resources](#eu-digital-sovereignty-resources)
- [Contributing](#contributing)

---

## Legend

| Symbol | Meaning |
|--------|---------|
| 🇫🇷 🇩🇪 🇳🇱 🇫🇮 🇪🇪 🇵🇱 🇦🇹 🇱🇻 🇨🇭 🇱🇺 🇵🇹 🇩🇰 🇨🇾 | Country of headquarters |
| `OSS` | Open-source code available |
| `FREE` | Free tier or free plan available |
| `API` | Programmatic API access |
| `SELF-HOST` | Can run on your own EU infrastructure |
| `GOV` | Government-backed or publicly funded initiative |

---

## LLMs & Foundation Models

EU-headquartered companies building or providing large language models.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Mistral AI](https://mistral.ai) | 🇫🇷 France | Frontier open-weight and commercial LLMs. Mistral Large, Mixtral, Mistral 7B. EU-hosted API via Le Plateforme | `OSS` `FREE` `API` |
| [Aleph Alpha](https://aleph-alpha.com) | 🇩🇪 Germany | Enterprise LLMs (Luminous, PhariaAI). Strong public sector and regulated industry focus. On-premise deployment available | `API` |
| [LightOn](https://lighton.ai) | 🇫🇷 France | Private LLMs for sensitive and confidential data. On-premise or dedicated EU cloud. Built for organizations that cannot expose internal data to external APIs | `API` `SELF-HOST` |
| [Bloom](https://huggingface.co/bigscience/bloom) | 🇫🇷 France | 176B parameter open-access multilingual LLM. Trained on 46 languages by the BigScience research collective | `OSS` `FREE` |
| [Tilde](https://tilde.com) | 🇱🇻 Latvia | 30B+ parameter LLM designed for Baltic and Eastern European languages. Strong on underserved EU languages | `OSS` |
| [LLaMA on EU infra](https://huggingface.co/meta-llama) | Self-host 🇪🇺 | Meta's open-weight models deployed on Hetzner, OVH, or Scaleway. Not EU-made, but fully EU-controllable when self-hosted | `OSS` `SELF-HOST` |

> **🏛 AI Act note:** LLMs are classified as General Purpose AI (GPAI). Providers must comply with transparency and documentation requirements — active since August 2025.

---

## Sovereign National LLMs

Government-backed AI models built for national language preservation and digital sovereignty. A growing trend across Europe — these models are designed to serve public sector, education, and domestic industry.

| Model | Country | What it does | Tags |
|-------|---------|-------------|------|
| [SOOFI](https://www.bmbf.de) | 🇩🇪 Germany | Sovereign Open Source Foundation Models. German government initiative backed by Deutsche Telekom and Leibniz University Hannover. Advanced open-source AI for robotics, administration, and industry | `OSS` `GOV` |
| [PLLuM](https://pllumai.pl) | 🇵🇱 Poland | Polish Large Language Model. Government-launched, tailored for Polish language inflection and complex syntax. Designed for text generation, document summarization, and education | `OSS` `GOV` |
| [Apertus](https://public.ai) | 🇨🇭 Switzerland | Swiss AI Initiative model. Available on Public AI platform. Exploring domain-specific models for law, climate, health, and education | `OSS` `GOV` |
| [Amalia](https://www.fct.unl.pt) | 🇵🇹 Portugal | Portuguese sovereign AI by consortium of universities. Answers questions, generates code, explains concepts, summarizes text in Portuguese with local context. Public release expected mid-2026 | `OSS` `GOV` |
| [EuroHPC AI](https://eurohpc-ju.europa.eu) | 🇪🇺 EU | EU's public supercomputing initiative providing compute for AI research and sovereign model training across European research centers | `GOV` |

> **💡 Why this matters:** These models represent a shift from depending on US-built AI to building European AI capabilities from the ground up. They prioritize local languages, cultural context, and public-sector use cases that commercial LLMs often ignore.

---

## AI Chat & Assistants

EU-hosted alternatives to ChatGPT, Claude, and Gemini.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Le Chat](https://chat.mistral.ai) | 🇫🇷 France | Mistral's consumer AI assistant. Web search, code generation, image understanding. Free, EU-hosted | `FREE` |
| [HuggingChat](https://huggingface.co/chat) | 🇫🇷 France | Open-source chat interface with multiple model options. Runs on HuggingFace's EU infrastructure | `OSS` `FREE` |
| [TextCortex](https://textcortex.com) | 🇩🇪 Germany | AI writing and productivity assistant for business. Browser extension, API, integrations | `FREE` `API` |

---

## Cloud & GPU Infrastructure

EU-headquartered providers for hosting AI workloads. No US hyperscalers.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Hetzner Cloud](https://hetzner.com/cloud) | 🇩🇪 Germany | High-performance VPS and dedicated servers with GPU options. Frankfurt, Nuremberg, Falkenstein, Helsinki. Exceptional price-to-performance | `API` |
| [OVHcloud](https://ovhcloud.com) | 🇫🇷 France | Major EU cloud with AI-specific GPU offerings (NVIDIA H100, A100). 40+ data centers globally, strong EU presence | `API` |
| [Scaleway](https://scaleway.com) | 🇫🇷 France | Developer-friendly cloud with GPU instances (H100, L40S). Paris and Amsterdam | `API` |
| [IONOS](https://ionos.de) | 🇩🇪 Germany | Cloud & hosting by United Internet group. Strong SMB and Mittelstand focus. German data centers only | `API` |
| [UpCloud](https://upcloud.com) | 🇫🇮 Finland | High-performance cloud. Helsinki, Frankfurt, Amsterdam, Madrid, Warsaw | `API` |
| [Exoscale](https://exoscale.com) | 🇨🇭 Switzerland | European cloud with GPU compute. Swiss privacy jurisdiction. Zurich, Vienna, Frankfurt, Munich | `API` |
| [STACKIT](https://stackit.de) | 🇩🇪 Germany | Sovereign cloud by Schwarz Group (Lidl/Kaufland parent company). Fully German-owned. German data centers | `API` |
| [T-Systems Open Telekom Cloud](https://open-telekom-cloud.com) | 🇩🇪 Germany | Enterprise cloud by Deutsche Telekom. Sovereign cloud for regulated industries. EU data residency guaranteed | `API` |
| [Fuga Cloud](https://fuga.cloud) | 🇳🇱 Netherlands | OpenStack-based cloud. Amsterdam data center. Dutch-owned | `API` |
| [Gcore](https://gcore.com) | 🇱🇺 Luxembourg | Edge cloud, CDN, and AI inference. EU-headquartered. Strong edge network across Europe | `API` |
| [Infomaniak](https://infomaniak.com) | 🇨🇭 Switzerland | Swiss cloud and hosting. Runs on 100% renewable energy. Privacy-first approach | `API` |

---

## Vector Databases

EU-built databases for AI embeddings, semantic search, and RAG applications.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Qdrant](https://qdrant.tech) | 🇩🇪 Germany | High-performance vector database written in Rust. Built for production AI applications at scale | `OSS` `FREE` `API` `SELF-HOST` |
| [Weaviate](https://weaviate.io) | 🇳🇱 Netherlands | AI-native vector database with built-in vectorization, hybrid search, and generative modules | `OSS` `FREE` `API` `SELF-HOST` |

---

## AI Dev Tools & MLOps

EU-built tools for developing, training, deploying, and monitoring AI systems.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Hugging Face](https://huggingface.co) | 🇫🇷 France | The largest open-source ML platform. Model hub, datasets, Spaces, inference API. EU-headquartered in Paris | `OSS` `FREE` `API` |
| [Jina AI](https://jina.ai) | 🇩🇪 Germany | Embedding, reranking, and search APIs. Multi-modal AI infrastructure for search and retrieval | `FREE` `API` |
| [Neptune.ai](https://neptune.ai) | 🇵🇱 Poland | ML experiment tracking, model registry, and metadata management | `FREE` `API` |
| [Valohai](https://valohai.com) | 🇫🇮 Finland | ML pipeline orchestration. Automates training, evaluation, and deployment workflows | `API` |
| [Dataiku](https://dataiku.com) | 🇫🇷 France | End-to-end AI/ML platform. Data preparation, model building, MLOps, and AI governance in one | `FREE` `API` |

---

## AI-Powered Productivity

EU-built AI tools for documents, collaboration, and daily work.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [DeepL](https://deepl.com) | 🇩🇪 Germany | AI translation and writing assistant. Consistently outperforms Google Translate on European languages. Translation API + DeepL Write for grammar and style | `FREE` `API` |
| [Nextcloud](https://nextcloud.com) | 🇩🇪 Germany | Self-hosted collaboration platform with AI features — smart inbox, text generation, image recognition, assistant | `OSS` `FREE` `SELF-HOST` |
| [CryptPad](https://cryptpad.org) | 🇫🇷 France | End-to-end encrypted docs, spreadsheets, presentations, kanban. Zero-knowledge architecture | `OSS` `FREE` `SELF-HOST` |
| [AppFlowy](https://appflowy.io) | Community | Open-source Notion alternative. Self-hostable. AI features in development | `OSS` `FREE` `SELF-HOST` |

---

## Translation & NLP

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Tilde MT](https://tilde.com) | 🇱🇻 Latvia | Machine translation specializing in Baltic and lesser-resourced EU languages | `API` |
| [Lingvanex](https://lingvanex.com) | 🇨🇾 Cyprus | Translation API with on-premise deployment option. 100+ languages | `API` `SELF-HOST` |

---

## Search Engines

EU-based search engines with AI features and no tracking.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Qwant](https://qwant.com) | 🇫🇷 France | Privacy-first search engine. Own index. No profiling. No tracking. EU jurisdiction | `FREE` |
| [Ecosia](https://ecosia.org) | 🇩🇪 Germany | Privacy search engine that plants trees with ad revenue. Co-building an EU web index with Qwant | `FREE` |
| [Stract](https://stract.com) | 🇩🇰 Denmark | Open-source search engine with user-configurable ranking. No tracking | `OSS` `FREE` |

---

## Secure Communication

EU-built messaging and communication tools with strong encryption.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Element / Matrix](https://element.io) | 🇬🇧 UK / 🇫🇷 France | Decentralized messaging on the Matrix protocol. End-to-end encrypted. Used by French and German governments | `OSS` `FREE` `SELF-HOST` |
| [Wire](https://wire.com) | 🇩🇪 Germany / 🇨🇭 Switzerland | End-to-end encrypted messaging, calls, and file sharing. Used by German federal government | `OSS` `FREE` |
| [Threema](https://threema.ch) | 🇨🇭 Switzerland | Privacy-first messenger. No phone number required. Swiss-hosted | `OSS` |
| [Proton Mail](https://proton.me) | 🇨🇭 Switzerland | End-to-end encrypted email. Swiss privacy jurisdiction. No ads, no tracking | `OSS` `FREE` |

---

## Privacy-First Analytics

Not AI-specific, but essential for deploying sovereign AI products in the EU.

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Plausible](https://plausible.io) | 🇪🇪 Estonia | Lightweight, cookie-free web analytics. EU-hosted. GDPR compliant without consent banners | `OSS` `SELF-HOST` |
| [Umami](https://umami.is) | Self-hostable | Simple, fast, privacy-focused analytics. Deploy on any EU server | `OSS` `FREE` `SELF-HOST` |
| [Matomo](https://matomo.org) | 🇳🇿 NZ origin | Full-featured analytics platform. Self-host on EU infrastructure for full sovereignty | `OSS` `FREE` `SELF-HOST` |
| [Fathom](https://usefathom.com) | 🇨🇦 CA origin | Privacy-first analytics with EU data isolation. EU-routed processing | `FREE` |

---

## Self-Hosted AI Stack

Run AI on your own EU infrastructure for maximum sovereignty. Combine these with any EU cloud provider above.

| Tool | Origin | What it does | Tags |
|------|--------|-------------|------|
| [Ollama](https://ollama.com) | Community | Run LLMs locally with one command. Drop-in API compatible with OpenAI format | `OSS` `FREE` `SELF-HOST` |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | Community | Run LLMs on CPU and low-end GPUs. GGUF format. Ideal for EU edge and on-premise deployment | `OSS` `FREE` `SELF-HOST` |
| [vLLM](https://github.com/vllm-project/vllm) | Community | High-throughput LLM serving engine. PagedAttention. Deploy on EU GPU servers | `OSS` `FREE` `SELF-HOST` |
| [LocalAI](https://localai.io) | Community | OpenAI-compatible API that runs models locally. No internet required after download | `OSS` `FREE` `SELF-HOST` |
| [Open WebUI](https://github.com/open-webui/open-webui) | Community | Self-hosted ChatGPT-like interface. Works with Ollama and any OpenAI-compatible API | `OSS` `FREE` `SELF-HOST` |
| [LibreChat](https://librechat.ai) | Community | Multi-model AI chat interface. Self-host and connect to any LLM provider | `OSS` `FREE` `SELF-HOST` |

> **💡 Sovereignty tip:** Self-hosting open-source models on EU infrastructure (Hetzner, OVH, Scaleway) gives you maximum data sovereignty. Your data never leaves your server, and no US entity has legal jurisdiction over it.

---

## AI for Healthcare

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [Ada Health](https://ada.com) | 🇩🇪 Germany | AI-powered symptom assessment and clinical decision support | `FREE` |

> **🏛 AI Act note:** AI in healthcare is classified as **high-risk** under Annex III. Strict requirements for accuracy, transparency, human oversight, and post-market monitoring apply from August 2026.

**Know an EU healthcare AI tool?** [Open an issue →](../../issues/new?template=suggest-tool.md)

---

## AI for Finance

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| *Contributions welcome* | | EU-built AI for credit scoring, fraud detection, risk assessment, AML | |

> **🏛 AI Act note:** AI used in credit scoring, insurance pricing, and financial risk assessment is **high-risk** under Annex III. These systems must also comply with **DORA** (Digital Operational Resilience Act) requirements for third-party ICT risk management.

**Know an EU financial AI tool?** [Open an issue →](../../issues/new?template=suggest-tool.md)

---

## AI for Legal

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| *Contributions welcome* | | EU-built AI for contract analysis, legal research, case prediction | |

**Know an EU legal AI tool?** [Open an issue →](../../issues/new?template=suggest-tool.md)

---

## AI for HR & Recruitment

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| *Contributions welcome* | | EU-built AI for CV screening, candidate matching, performance evaluation | |

> **🏛 AI Act note:** AI used in recruitment, CV screening, promotion decisions, and employee evaluation is **high-risk** under Annex III. These are among the most scrutinized categories. Fines for non-compliance: up to €35M or 7% of global turnover.

**Know an EU HR AI tool?** [Open an issue →](../../issues/new?template=suggest-tool.md)

---

## AI for Security & Compliance

| Tool | Country | What it does | Tags |
|------|---------|-------------|------|
| [BitAtlas](https://bitatlas.com) | 🇳🇱 Netherlands | Zero-knowledge encrypted cloud drive for humans and AI agents. Client-side AES-256-GCM encryption — the server never sees plaintext. MCP server for AI agent integration. Hosted on Hetzner (Germany) | `OSS` `FREE` `API` `SELF-HOST` |

**Know an EU security AI tool?** [Open an issue →](../../issues/new?template=suggest-tool.md)

---

## EU AI Act Resources

### ⏰ Key Dates

| Date | Status | What happens |
|------|--------|-------------|
| Feb 2, 2025 | ✅ Done | Prohibited AI practices banned (social scoring, manipulative AI, emotion recognition at work) |
| Aug 2, 2025 | ✅ Done | GPAI transparency rules active. Providers must publish training data summaries |
| **Aug 2, 2026** | ⏳ **Coming** | **High-risk AI system rules activate. Transparency obligations (Art. 50). National enforcement begins. Regulatory sandboxes operational** |
| Aug 2, 2027 | Upcoming | Remaining provisions. High-risk AI in regulated products (medical devices, vehicles) |

### Official Sources

- [EU AI Act — Full Official Text](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) — EUR-Lex
- [AI Act Service Desk](https://ai-act-service-desk.ec.europa.eu/) — European Commission's official guidance portal
- [AI Act Compliance Checker](https://ai-act-service-desk.ec.europa.eu/en/eu-ai-act-compliance-checker) — Official tool to check your obligations
- [AI Act Explorer](https://artificialintelligenceact.eu/) — Searchable text with independent analysis
- [GPAI Code of Practice](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) — Voluntary compliance framework for GPAI providers
- [EU AI Act Implementation Timeline](https://artificialintelligenceact.eu/implementation-timeline/) — All milestones
- [IAPP Compliance Matrix](https://iapp.org/resources/article/eu-ai-act-compliance-matrix) — Requirements overview by role

---

## EU Digital Sovereignty Resources

### Key Reports

- [Atlantic Council: Digital Sovereignty — Europe's Declaration of Independence](https://www.atlanticcouncil.org/in-depth-research-reports/report/digital-sovereignty-europes-declaration-of-independence/) (Feb 2026)
- [Bertelsmann Stiftung: EuroStack Report](https://www.bertelsmann-stiftung.de/en/our-projects/reframetech-algorithmen-fuers-gemeinwohl/project-news/eurostack-a-european-alternative-for-digital-sovereignty) — €300B proposal for EU digital infrastructure
- [Wire: State of Digital Sovereignty in Europe 2025](https://wire.com/en/blog/state-digital-sovereignty-europe) — Survey of 270+ EU tech and policy leaders
- [Berlin Declaration for European Digital Sovereignty](https://data.consilium.europa.eu/) (Nov 2025) — Signed by all 27 EU member states

### Other Directories

- [European Alternatives](https://european-alternatives.eu/) — General EU software and services directory
- [EU Alternative](https://eualternative.eu/) — EU SaaS alternatives
- [GoEuropean](https://goeuropean.org/) — Community-driven EU product directory with browser extension
- [Switch-to.eu](https://switch-to.eu/) — EU tech swap recommendations

### Communities

- [r/eufirst](https://reddit.com/r/eufirst) — EU-sovereign AI tools and AI Act compliance
- [r/buyeu](https://reddit.com/r/buyeu) — EU-made products and services
- [r/eufounders](https://reddit.com/r/eufounders) — EU founders building sovereign tech
- [r/BuyFromEU](https://reddit.com/r/BuyFromEU) — The original EU buying movement (122k+ members)
- [r/europrivacy](https://reddit.com/r/europrivacy) — European privacy and data protection
- [r/selfhosted](https://reddit.com/r/selfhosted) — Self-hosting community (relevant for sovereign deployment)

---

## Contributing

Contributions are welcome and encouraged. This list grows through the community.

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines, inclusion criteria, and style guide.

### Quick contribution

**Easiest:** [Open an issue](../../issues/new?template=suggest-tool.md) with the tool name, website, country of HQ, and a short description. We'll add it.

**Faster:** Submit a pull request editing this README directly.

---

## About

This list is maintained as an independent, community-driven project to help Europeans find AI tools they can trust.

We evaluate tools on **5 sovereignty criteria:**

| Criterion | What we check |
|-----------|---------------|
| HQ Location | Is the company headquartered in the EU? |
| Data Centers | Is data processed exclusively in the EU? |
| Legal Jurisdiction | Is the service governed by EU law? |
| GDPR Compliance | Is there audited/certified GDPR compliance? |
| AI Act Readiness | Is the company actively preparing for AI Act compliance? |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=GINIUS123/EUfirst&type=Date)](https://star-history.com/#GINIUS123/EUfirst&Date)

---

<p align="center">
  <sub>Independent project. Not affiliated with the European Union or any listed company.</sub><br>
  <sub>Built in Darmstadt, Germany 🇩🇪</sub>
</p>

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This work is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). You can copy, modify, and distribute it without asking permission.
