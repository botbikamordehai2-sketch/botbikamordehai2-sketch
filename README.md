# Hi, I'm Mordehai (Moti) Botbika 👋

**AI Automation Engineer** · programming, automation and AI agents · based in Israel 🇮🇱

I build AI-powered automation systems: multi-agent workflows with human-in-the-loop governance, event-driven agent infrastructure, and research-only data pipelines for markets. Alongside that, I study Computer Science on the path toward security and vulnerability research.

---

### 🛠 What I build

- **Multi-agent systems with governance.** Several AI agents working across GitHub, Notion, monday.com, Slack, ClickUp and WordPress, coordinated by written rules: one source of truth per layer, no external write without human approval, every claim tagged FACT / OBSERVATION / UNVERIFIED.
- **Event-driven agent infrastructure.** An append-only event log (SQLite) where agents write events and handlers react, with correlation IDs for traceability.
- **Workflow automation.** n8n (self-hosted on Docker), Make, Google Sheets/Gmail OAuth, Notion as the business source of truth.
- **Research pipelines.** Python scripts that fetch market data, build currency-strength matrices across 8 major currencies, and log signals for evaluation. Research only: no live execution.
- **Web.** WordPress (incl. WordPress Studio), static sites, a small React PWA.

### 🧰 Tech stack

**Languages:** Python · Bash/Shell · SQL (SQLite) · JavaScript / HTML / CSS · PowerShell / Batch · MQL5
**Automation & AI:** n8n · Make · Claude API & agent workflows · MCP · GitHub Actions
**Platforms:** GitHub · Notion · monday.com · Slack · ClickUp · WordPress · Docker
**Practices:** human-in-the-loop approvals · PR-based changes · idempotent syncs · no secrets in repos

### 📌 Featured projects

| Project | What it is |
|---|---|
| [github-sync](https://github.com/botbikamordehai2-sketch/github-sync) | Governance and sync layer for my multi-agent ecosystem: GitHub ↔ Notion ↔ apps ↔ model wrappers, with safety rules, a platform map and a scheduled GitHub Actions repo scan. |
| [trinity-os-core](https://github.com/botbikamordehai2-sketch/trinity-os-core) | Minimal event-sourcing kernel for autonomous agent systems in Python: agents append events to SQLite, a poller dispatches them to handlers. |
| [memory-for-all](https://github.com/botbikamordehai2-sketch/memory-for-all) | Shared memory and documentation hub for the agent team, unified non-destructively with github-sync. |
| [n8n-learning](https://github.com/botbikamordehai2-sketch/n8n-learning) | n8n on Docker (Windows), Google Sheets/Gmail OAuth notes and workflow exports with no credentials. |

### 📚 Currently learning

- CS fundamentals: algorithms, data structures, networking, operating systems
- Debugging and security fundamentals, working toward vulnerability research
- Agent orchestration patterns (MCP, multi-agent coordination, evaluation)

### 📫 Contact

- LinkedIn: [Mordehai Botbika](https://www.linkedin.com/in/mordehai-botbika-433973406)
- X: [@MotiBotbik13251](https://x.com/MotiBotbik13251)
- Languages: Hebrew · English
