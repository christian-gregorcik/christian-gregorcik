## Christian Gregorcik

I build with AI as the engineering team, and I read every line it writes.

I run **[Digitalkompaniet](https://digitalkompaniet.se)**, a one-person studio in Sweden:
client websites on Cloudflare Pages with Workers behind the forms, two React Native
apps on Supabase and PostgreSQL, and AI assistants that return structured JSON into
real workflows. Requirements, data model, security, deploys and the phone call
afterwards — all of it is mine.

Before this I spent ten years as a team leader and goods receiver. No computer science
degree; I started formal studies alongside the work in November 2026. What I bring
instead is that I finish things, and that I can explain any line in the repositories
below.

### Open source

| | |
| --- | --- |
| **[docsearch](https://github.com/christian-gregorcik/docsearch)** · TypeScript | Hybrid search over your own documents. Postgres full-text and pgvector in one database, merged with reciprocal rank fusion. On the eval set neither half answers every query and the pair answers all of them. |
| **[evalbox](https://github.com/christian-gregorcik/evalbox)** · Python · [PyPI](https://pypi.org/project/evalbox/) | Run a suite of checks against a language model and fail the build when it regresses. Each case is repeated and judged on the share that passed, because one sample of a non-deterministic system is an anecdote. |
| **[budgetloop](https://github.com/christian-gregorcik/budgetloop)** · Python · [PyPI](https://pypi.org/project/budgetloop/) | The tool-calling loop, written out. Schemas from type hints, parallel calls, a step and cost budget, a trace. A tool that fails comes back as a message the model can read, not a crash. No dependencies. |
| **[llmgate](https://github.com/christian-gregorcik/llmgate)** · Go | A reverse proxy in front of one API. Per-client rate limits, retries that give way to the upstream’s Retry-After, a circuit breaker and Prometheus counters. Standard library only; the clock is injected, so the suite tests retry behaviour without sleeping. |
| **[originguard](https://github.com/christian-gregorcik/originguard)** · Rust · [crates.io](https://crates.io/crates/originguard) | The rules a browser applies to every request, from the specifications: same-origin policy and opaque origins, public suffixes and the schemeful site, cookie scoping with the `__Host-`/`__Secure-` prefixes and SameSite, and Content-Security-Policy with the full directive fallback chain. 97 tests, no dependencies, and a CI job that proves the minimum Rust version rather than asserting it. |
| **[ruleblock](https://github.com/christian-gregorcik/ruleblock)** · C++23 | A tracker-blocking filter matcher. Each rule is filed under its rarest token across the whole list, and carries a 32-bit signature that discards it without reading it — which took the worst case from 5,262 ns to 556 ns. 56 tests, clean under the address and undefined sanitizers, built with warnings as errors. |
| **[llm-json](https://github.com/christian-gregorcik/llm-json)** · TypeScript | Parse and validate JSON from model output, with bounded repair retries. |
| **[scb-mcp](https://github.com/christian-gregorcik/scb-mcp)** · TypeScript | An MCP server over Statistics Sweden's business register. The protocol implemented, not wrapped. |
| **[sidgranskare](https://github.com/christian-gregorcik/sidgranskare)** · JavaScript | Measures a public web page and reports the most serious findings, with an SSRF guard on every request the page makes, not just the first. |

Every one of them has tests that run offline, no API key and nothing to sign up for.

### What I work with

Python · TypeScript · JavaScript · Go · Rust · C++23 · Node · React Native · PostgreSQL ·
pgvector · Supabase · Docker · Cloudflare Workers · MCP · LLM integration and structured
output · retrieval and evals · web security (CSP, same-origin, cookies) · performance
measurement · SQL · Git

### Reaching me

[christian.gregorcik95@hotmail.com](mailto:christian.gregorcik95@hotmail.com) ·
[LinkedIn](https://www.linkedin.com/in/christian-gregorcik-1a4149259/) ·
Strängnäs, Sweden — open to Stockholm and to remote work on US hours.
