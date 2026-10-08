#  Epistemic Research & Active Experimentation Agent
### *Powered by @agentrhq/webcmd Browser Infrastructure*

An uncertainty-aware, hypothesis-testing research agent with full-stack interactive visualization, Provenance DAG de-duplication, and **`webcmd` browser automation**.

---

## The Core Synergy: Epistemic Agent + Webcmd

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                    EPISTEMIC AGENT (The Brain & Decision Engine)                │
│  - Evaluates Shannon Entropy H(P(H)) over competing hypotheses.                 │
│  - Builds Provenance DAGs to collapse syndicated echo-chamber scrapers.         │
│  - Calculates Expected Value of Information (EVOI) to decide WHEN to probe.     │
└────────────────────────────────────────┬────────────────────────────────────────┘
                                         │
                                         ▼ [EVOI > 0: Trigger Causal Probe]
┌─────────────────────────────────────────────────────────────────────────────────┐
│                    WEBCMD (The Causal Web Execution Engine)                     │
│  - Spins up sandboxed browser sessions (`webcmd session create`).               │
│  - Executes live DOM / Playwright assertion scripts (`webcmd browser run`).     │
│  - Extracts structured JSON outcomes and compiles them into reusable CLI skills!│
└─────────────────────────────────────────────────────────────────────────────────┘
```

1. **Why Standard Web Agents Waste Tokens:** Traditional agents browse blindly step-by-step, re-navigating full web pages and burning hundreds of thousands of tokens.
2. **How This Project Wins:** 
   - Uses **Provenance DAGs** to detect when web consensus is fake or contradictory.
   - Computes **EVOI** so it only launches browser sessions when active experiments yield high information value.
   - Leverages **`webcmd`** to run targeted browser scripts in sandboxed sessions, reducing token costs by **up to 90%** and compiling interactions into deterministic CLI skills!

---

##  Repository Structure

```
epistemic-agent/
├── README.md                  # Comprehensive architecture & setup documentation
├── requirements.txt           # Python dependencies
├── demo_benchmarks.json       # Pre-configured benchmark scenarios (including webcmd UI probe)
├── demo_runner.py             # CLI Benchmark Runner
├── simple_server.py           # Zero-dependency full-stack server
├── server.py                  # Production FastAPI + WebSocket server
├── core/
│   ├── belief_state.py        # Typed data models for Hypotheses, Provenance DAG, Claims, Probes
│   ├── entropy.py             # Shannon entropy, EIG, EVOI, & Bayesian updating math
│   ├── webcmd_engine.py       # @agentrhq/webcmd CLI integration for browser DOM probing
│   ├── auto_synthesizer.py    # Dynamic hypothesis & probe generator for custom queries
│   ├── sandbox_runner.py      # Micro-sandbox execution harness (isolated Python & HTTP)
│   ├── passive_agent.py       # Scraper/search interface with echo-chamber DAG reduction
│   ├── active_prober.py       # Discriminative experiment selector & Bayesian belief updater
│   └── orchestrator.py        # Main agent state machine loop
└── frontend/                  # Modern Interactive Web Dashboard
    ├── index.html             # Main dashboard layout (Tailwind CSS + D3.js)
    ├── css/
    │   └── styles.css         # Dark-mode dashboard aesthetics & terminal styling
    └── js/
        ├── app.js             # Dual-mode WebSocket/REST client & UI manager
        ├── dag_visualizer.js  # D3.js force-directed Provenance DAG visualizer
        └── belief_charts.js   # Real-time Bayesian probability meters & entropy gauge
```
Link : https://epistemic-research-active-probing-agent-u2mo.onrender.com
