# Ayush Patil

**I find the gap. I design the system. I ship it.**

Founding engineer at **Breathe**, previously **Anakin (YC S21)**. I've spent my career as one of the first one or two engineers at a company, owning products from the first diagnosis to production. I work remotely across time zones. Right now I'm building agent infrastructure in public, starting from the loop and moving up.

## Building now

### [harness](https://github.com/LifeAyush/harness): an agent runtime from first principles

The infrastructure that turns an LLM into an agent that uses tools, keeps state and stops reliably. It doesn't use LangChain or LangGraph: the loop, tool registry and provider boundary are written by hand so each piece can be understood and replaced.

- **Agent loop with hard stop conditions:** every run ends in a final answer, `max_iterations`, a wall-clock timeout, a token budget, or a model error. It never just hangs.
- **Typed tool registry:** one pydantic model gives both the JSON Schema the model sees and the validation, so they can't drift apart. Bad arguments, exceptions and timeouts go back to the model as errors it can correct.
- **Provider-agnostic:** works with any OpenAI-compatible `/chat/completions` server, with retries on 429/5xx. There are scripted and demo models for keyless tests.
- **Phase 1 of 8.** Next come event-sourced sessions, tool workers, a Docker sandbox, a context engine, subagents and a distributed deployment.

### Agent tooling

- **[webpage-audit](https://github.com/LifeAyush/webpage-audit)** (TypeScript, MCP): an MCP server that gives an agent a real browser to audit a site. It collects evidence (console, network, timing, axe) and blocks payment, account and password actions by default.
- **[meeting-api](https://github.com/LifeAyush/meeting-api)** (Python): streams meeting audio over a WebSocket, transcribes it with Whisper, matches speakers by voice embedding, and writes a summary with action items. Runs without a GPU.

### Infra

- **[falcon](https://github.com/LifeAyush/falcon)** (Go): an L7 reverse proxy and API gateway. **~54K req/s at 200 concurrent connections, zero errors** ([benchmarked against nginx](https://github.com/LifeAyush/falcon#benchmarks)). Round-robin, random and weighted balancing, runtime backend swaps, rate limiting and health checks.
- **[remote-desktop](https://github.com/LifeAyush/remote-desktop)** (Python, React): a web console for a Docker host, with live metrics, container management, log streaming and a real TTY inside any container. Token-gated and bound to localhost by default.

<sub>Other builds: [grocx](https://github.com/LifeAyush/grocx) (cheapest grocery basket across quick-commerce apps) · [persona](https://github.com/LifeAyush/persona) (ride fares across Ola, Rapido and Namma Yatri)</sub>

## Work

- **Breathe** · Founding Engineer · 2025 – present. ESG data platform used by 40+ enterprises (Swiggy, CEAT, Paytm, Rubix). I shipped the Supplier Intelligence product line, an AST-based Formula Manager (**~40% less manual entry**), Isolation Forest anomaly detection (**~20% fewer audit corrections**) and Scope 3 mapping on Pinecone (**1M+ vectors**).
- **Anakin (YC S21)** · Backend, Infra & Data · 2024 – 2025. Built an account system for **30+ services** at **~10 ms, 3–4K TPS**, and AWS ETL pipelines ingesting **200K+ products**.
- **Foxledger Studio** · Full-Stack & UI/UX · 2022 – 2024. Web3 products for 20+ communities (BAYC, Azuki, Doodles). **22K+ users** on Arcadeverse.

Day-job commits live on my company account, [AyushP672](https://github.com/AyushP672) (1,000+ private contributions this year).

**Stack:** Python, TypeScript, Go, React, Node · PostgreSQL, Redis, Pinecone · Docker, AWS (ECS, SQS, S3, EventBridge)

## Say hi

Stuck on an agent loop, a flaky pipeline, or a prototype that needs to become a real system? I'm always up to dig into it with you. No pitch, just two engineers looking at the problem.

<a href="https://cal.com/ayush-patil-s2zg3v/30min"><img alt="Book a 30 min chat on Cal.com" src="https://cal.com/book-with-cal-dark.svg" /></a>

[Cal.com](https://cal.com/ayush-patil-s2zg3v/30min) · [LinkedIn](https://www.linkedin.com/in/lifeayush/) · [X](https://x.com/ayushpatil_dev) · [Email](mailto:ayushypatil.work@gmail.com)

<sub>IIT Roorkee · Bengaluru, India</sub>
