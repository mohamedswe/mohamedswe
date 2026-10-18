## Mohamed Abdelgelil — Backend & AI Engineer

I build Python and TypeScript backends, and the AI systems that run on top of them. I care about one question more than most: does this software actually do what it claims?

### Now

**Founding Software Engineer · [InsectFlux](https://insectflux.com)** · Aug 2025 – present
Data logistics company serving the insect-farming industry. I own backend reliability: schema migrations that keep old and new records working, the backend test suite, Stripe webhooks, and messaging.
- Moved messaging to webhooks, cutting database reads by ~70%
- Built backend CI to 85% test coverage
- [Case study →](https://github.com/mohamedswe/insectflux-case-study)

**Software Engineer, AI Training · Mercor** · Sep 2026 – present
I evaluate AI coding models on software engineering tasks and write the human feedback used to improve them.

### Projects

| Project | What it is |
|---|---|
| [**Emara**](https://github.com/mohamedswe/emara) | Local CLI that maps a JS/TS/Python codebase into features, links each one to exact source lines, compares code against its docs, and flags dead-code candidates. Fully deterministic: zero LLM calls. [Live demos](https://mohamedswe.github.io/emara/) on uptime-kuma, the FastAPI full-stack template, and bulletproof-react. |
| [**agent-memory-gate**](https://github.com/mohamedswe/agent-memory-gate) | Research prototype: memory for coding agents that only keeps what repeats across sessions. Zero LLM tokens to write memories (vs. ~13k for A-MEM on the same corpus), 10–29% fewer input tokens per session. Null results published too. |
| [**AI Tutor**](https://github.com/mohamedswe/ai-tutor-case-study) | Solo RAG platform: students upload course files and ask questions grounded in them. FastAPI, pgvector, GPT-4 Vision for diagrams, Next.js. |
| [**B-link**](https://github.com/mohamedswe/b-link-case-study) | Campus app for Brock students, shipped to the App Store and Google Play. Lead engineer on a 3-person team: architecture, Apple compliance, trust & safety. |

### How I work

I build with AI coding agents, and I treat their output as untrusted. Agents write a lot of code fast and describe it confidently, not always accurately. So the design decisions, tests, and verification are mine. Emara exists because of that: I wanted a way to check what a codebase really does, independent of what anyone (or any agent) says about it.

### Stack

`Python` `FastAPI` `PostgreSQL` `pgvector` `TypeScript` `Node.js` `Next.js` `React Native` `Supabase` `Firebase` `Stripe` `Docker` `OpenAI` `Anthropic` `LangChain`

### Contact

Open to backend and AI engineering roles — remote, or anywhere in Canada.
📫 mohamedabdelgelil47@gmail.com · [LinkedIn](https://www.linkedin.com/in/mohamed-abdel-gelil)
