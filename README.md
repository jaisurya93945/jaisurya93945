# Badathala Jaisurya

### AI Security Researcher & Engineer

I research and build defences for LLM applications and AI agents — and test how they fail.

[LinkedIn](https://www.linkedin.com/in/badathala-jaisurya) · [Portfolio](https://jaisurya93945.github.io/portfolio) · [TryHackMe — top 3%](https://tryhackme.com/p/nikki1602) · [Email](mailto:jaisurya524126@gmail.com)

---

## Research & tools

**[IDENSEC](https://github.com/jaisurya93945/idensec)** — *Can deterministic provenance stop indirect prompt injection in AI agents?* Values from untrusted content (emails, web pages, tool outputs) are sealed, and tool calls whose authority-bearing arguments can't be attributed to the user are denied — with no model in the decision path. Research prototype; AgentDojo benchmark next.

**[SentinelCore](https://github.com/jaisurya93945/sentinelcore)** — *How far can a transparent, auditable gateway go against prompt injection?* An OpenAI-compatible security gateway that scans prompts, RAG context, tool calls, MCP tool definitions and streamed output, with a policy engine (allow / sanitize / human-approval / block). Every detector change is replayed against 744 labelled attacks, and precision, recall and false-positive rate are published — weak spots included. `v0.3.0`

**[CipherAI security case study](https://github.com/jaisurya93945/cipherai-security-case-study)** — the threat model and controls behind a live AI SaaS I founded and secure: role-based admin access, rate limiting, abuse prevention and prompt guardrails.

**[AI security guide](https://github.com/jaisurya93945/ai-security-guide)** — a curated reading list on LLM and agent security.

## Research interests

- Indirect prompt injection and agent hijacking
- Tool-call and MCP security
- Evaluating guardrails under adaptive attacks
- Prompt injection in Indic and code-mixed languages *(planned)*

## Security practice

- **Top 3% globally on TryHackMe** — [public profile](https://tryhackme.com/p/nikki1602)
- 2nd Prize, National-Level Cybersecurity Hackathon — ACM Student Chapter, VIT (2024)
- CEH — EC-Council (2025) · Red Teaming LLM Applications — DeepLearning.AI (2026)
- Cybersecurity intern — CFSS (network monitoring, log analysis, web app testing)

## Stack

Python · FastAPI · TypeScript/React · Supabase/Firebase · Docker · Azure DevOps CI/CD · Linux · scikit-learn · Hugging Face datasets

## Next up

- Benchmark IDENSEC on AgentDojo and publish the results
- Add a machine-learning detection layer to SentinelCore

<sub>By day: DevOps engineer at Stackly · Founder of <a href="https://cipherai.in">CipherAI</a> · Bengaluru, India</sub>
