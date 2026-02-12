# 👋 Hi, I'm Peter – the mind behind Mindcockpit.ai

🚀 **Dipl.-Ing. • Senior Software Architect • AI Systems Engineer • Open-Source AI Infrastructure Builder**

33 years of enterprise IT experience across **military aerospace** (EADS, Eurocopter, Airbus Defence & Space), **air traffic control** (Comsoft), **rail transport** (Swiss Federal Railways), **finance** (UniCredit, C1 FinCon), and **internet-scale platforms** (Lycos Europe) — now building the next generation of self-hosted, sovereign AI systems.

🎓 Dipl.-Ing. (Uni.) Computer Science, Technical University Košice — graduated with distinction  
🌍 7 languages: German, English, Russian, Slovak, Czech, Polish, Ukrainian

---

## 🧠 What I'm Building

### [TIMS — Task Information Management System](https://github.com/wolaschka/TIMS/wiki) *(private)*

> Enterprise-grade task and project management for **Airbus Defence & Space — Tornado aircraft program**. Migrated from legacy MS Access to a modern DDD architecture handling 1M+ task records across 20+ years of operational data.

**Built with:** Perl 5.40 / Dancer2 / Moose / Oracle 19c / K3s / Evolutionary CI/CD / Claude Code Agent Teams

Three isolated K3s stages (dev/it/qa) at `tims.mindcockpit.ai` with automated TLS, Prometheus/Grafana monitoring behind WireGuard, and 215 tests at >80% coverage. Domain-Driven Design with repository pattern, CQRS-lite, and event sourcing for audit trails.

### [Cognitive Core](https://github.com/mindcockpit-ai/cognitive-core)

> A production-grade, self-hosted AI assistant framework with plugin-extensible architecture — designed for future humanoid robot embodiment.

**Key features:**
- 🔌 **Plugin-first architecture** — every capability (channels, memory, tools, voice) delivered as a plugin
- 🧬 **Biomimetic skill hierarchy** — Atomic → Molecular → Cellular → Organism organization
- 🛡️ **Immune-system security** — 5-layer defense-in-depth with CaMeL pattern
- 🤖 **Embodiment-ready** — layered abstraction model designed to transition from screen to physical robot
- 🔀 **Hybrid inference** — Claude API for complex reasoning + local open-weight models for privacy & latency
- 🏠 **Fully self-hosted** — zero SaaS dependencies beyond Claude API (deliberate, audited exception)

**Architecture:**
```
┌─────────────────────────────────────┐
│  1. Reasoning Layer                 │  Claude API + Ollama (Llama, Qwen, DeepSeek)
├─────────────────────────────────────┤
│  2. Memory & Context Layer          │  PostgreSQL + Qdrant + Redis
├─────────────────────────────────────┤
│  3. Interface Abstraction Layer     │  Matrix today, ROS2 tomorrow
├─────────────────────────────────────┤
│  4. Action Execution Layer          │  Tools, MCP, multi-agent orchestration
├─────────────────────────────────────┤
│  5. Safety & Validation Layer       │  Zero-trust, prompt injection defense, kill-switch
└─────────────────────────────────────┘
```

**Status:** Phase 0 complete. Active development — AI-agent-accelerated at 8–12x velocity using Claude Code.

### [PharmaSynth AI](https://pharmasynth.mindcockpit.ai:8443/) *(MVP, private repo)*

> AI-driven pharmaceutical formulation platform — a collaboration with **Tomáš Wolaschka, PhD** ([Google Scholar](https://scholar.google.com/citations?user=p0k6ZXUAAAAJ), University of Veterinary Medicine and Pharmacy in Košice). Ingredient compatibility prediction, formulation optimization, and regulatory compliance validation against international pharmacopoeia standards (Ph. Eur., USP, BP, JP).

**Built with:** Perl 5 / Dancer2 / Moose / Tailwind CSS / REST API / i18n (EN, DE, IT, SK, JP)

Clean architecture with proper layering (api/gui/impl/dao/model/schema). Live deployment at `pharmasynth.mindcockpit.ai`. MIT licensed.

---

## ✈️ Military, Aerospace & Air Traffic Control

Two decades of defense and aviation systems engineering:

| Period | Client | Project | Platform |
|--------|--------|---------|----------|
| 2019–present | **Airbus Defence & Space** | TIMS — Task Information Management | Tornado aircraft |
| 2010–2013 | **Comsoft GmbH** | CADAS-IMS — Aeronautical Information Management | ATC / NOTAM / OPMET |
| 2008–2009 | **EADS Defence & Security** | A400M MilSwP — SIRIUS Simulation Framework | A400M military transport |
| 2006–2007 | **Eurocopter / ABSC** | TMMT — Configuration Management (NATO classified) | NH90 helicopter |
| 2001–2002 | **EADS / ABSC** | TPMS — Technical Publications Management | Eurofighter & Tornado |

Avionics bus expertise: ARINC429, AFDX, MIL-Bus, VCOM

---

## 🏦 Financial Technology & Capital Markets

11+ years in banking infrastructure at UniCredit:

**SWIFT Messaging:** MT202, MT103, MT527, MT535, MT558, MT569 · ISO 20022: pacs.008, pacs.009

**Collateral Management:** OTC derivatives, margin call calculation, CCP clearing, repo business, risk analysis, reconciliation

**Custodian Integration:** Euroclear, Clearstream, BNY Mellon, JP Morgan, State Street Bank

**Market Data:** Bloomberg Terminal & API, Reuters API, ECB data feeds

**Regulatory:** EMIR compliance, EDIA eligibility, ISDA margin call disputes, NMR (New Margin Requirements)

**3rd-Party Systems:** Calypso, Anvil, Sophis, Murex, Aramis, TriOptima, LCH Clearing

---

## 🔧 Tech Stack

**AI & Inference**
`Claude API` • `Ollama` • `Llama 3` • `Qwen 2.5` • `DeepSeek` • `Whisper` • `Piper TTS` • `Qdrant` • `RAG`

**Languages & Frameworks**
`Java 21 (Spring Boot 3, Hibernate, JPA)` • `Perl 5.40 (Moose/Dancer2/DBIx::Class)` • `Python 3.12+` • `C/C++` • `Rust` (evaluating) • `FastAPI`

**Infrastructure**
`Docker` • `K3s` • `WireGuard` • `Matrix/Synapse` • `PostgreSQL` • `Oracle 19c` • `Redis` • `Prometheus` • `Grafana`

**CI/CD & DevOps**
`GitHub Actions` • `Jenkins` • `Evolutionary CI/CD` (5-gate fitness pipeline) • `GitOps` • `Maven`

**Domain Expertise**
`Military Aerospace (EADS/Airbus/Eurocopter)` • `Air Traffic Control` • `Rail Transport (SBB)` • `Collateral Management (ALGO)` • `SWIFT Messaging (MT/ISO 20022)` • `Bloomberg/Reuters API` • `EMIR/EDIA/ISDA RegTech` • `Pharmaceutical Formulation (PharmaSynth)` • `Enterprise Migration` • `Legacy Modernization`

---

## 📜 Career Highlights

**2019–present** · **Airbus Defence & Space** — SW Architect, Senior Developer & Development Lead. TIMS for Tornado aircraft program — ongoing active development with Claude Code Agent Teams, evolutionary CI/CD, K3s deployment.

**2014–present** · **UniCredit** — Senior IT Consultant, Collateral Management (ALGO). Java/Spring Boot, Perl, Oracle. Custodian Cockpit (Euroclear, Clearstream, BNY Mellon, JP Morgan, State Street), Collateral Tools microservices platform, Payment Tool with host mainframe interfaces. Bloomberg API & Reuters API integration. Automatic Eligibility Tool (EDIA). Margin Call Disputes (ISDA). Reconciliation management (WBP). EMIR regulatory compliance.

**2010–2013** · **Comsoft GmbH** — Senior Developer, Architect & Java Coach. CADAS-IMS air traffic control system (NOTAM, OPMET, EAD). JEE/JBoss architecture refactoring. Reference: *"stability, scalability, and maintainability improved to the desired level through his significant contribution."*

**2008–2009** · **EADS Defence & Security** — Development Engineer & ICD Manager. A400M military software integration. SIRIUS OSGi simulation framework. Avionics interface control documents. Multi-platform CI/CD (Hudson).

**2007–2008** · **Swiss Federal Railways (SBB CFF FFS)** — Software Architect, Division Passenger Transport. Multi Channel Services platform (Ticket Shop, Business Travel, Prisma, BATS) — 100+ subprojects. SOA/WebServices architecture review. Complete Build & Deployment process redesign and unification.

**2006–2007** · **Eurocopter / ABSC** — System Analyst & Software Architect. TMMT configuration management for NH90 helicopter variants. NATO-classified document handling with JAAS multi-role access control.

**2005–2006** · **be2 GmbH** — CTO Deputy & Development Lead. Platform migration from Perl/FCGI to J2EE. Managed offshore team.

**2002–2005** · **Lycos Europe GmbH** — Senior Developer, Search Department. Trend-O-Meter, Paperball 2.1 vertical search engine, Live Search. Reference: *"exceptional judgment enabling independent, balanced decisions even in difficult situations."*

**2001–2002** · **EADS / ABSC** — Software Developer. TPMS for Eurofighter & Tornado technical publications. CCMS for Eurocopter.

---

## 🧭 Guiding Principles

- **Open-source first** — every component evaluated for open-source availability before considering alternatives
- **Self-hosted & sovereign** — full control over data, models, and infrastructure
- **Security is non-negotiable** — zero-trust, defense-in-depth, no telemetry phoning home
- **Embodiment-forward** — every architectural decision evaluated against future physical deployment
- **Production-grade only** — no toy demos, no quick hacks that become permanent
- **Quality over quantity** — peer-reviewed sources, validated documentation, no SEO noise

---

## 🌐 Projects & Domains

| Project | Purpose |
|---------|---------|
| [TIMS](https://github.com/wolaschka/TIMS/wiki) | Enterprise task management — Airbus Defence & Space / Tornado *(private)* |
| [cognitive-core](https://github.com/mindcockpit-ai/cognitive-core) | Open-source AI assistant framework |
| [PharmaSynth AI](https://pharmasynth.mindcockpit.ai:8443/) | AI pharmaceutical formulation platform — with T. Wolaschka, PhD (UVLF Košice) *(private)* |
| [mindcockpit.ai](https://mindcockpit.ai) | Organization & framework hub |
| [multivac42.ai](https://multivac42.ai) | Personal AI deployment instance — Multivac + 42 🏃‍♂️📚 |

---

## 💬 Let's Connect

I'm interested in collaborations around self-hosted AI infrastructure, embodied AI, AI in pharmaceutical research, open-source assistant frameworks, defense/aerospace IT systems, and enterprise legacy modernization.

🔗 [LinkedIn](https://www.linkedin.com/in/peter-wolaschka-48908214/)

---

*Currently: building cognitive-core full-time with AI-agent-accelerated development — from terminal to embodiment.*
