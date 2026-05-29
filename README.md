# Kunwar Sangram Singh

I build AI-native systems, agentic workflows, and infrastructure that holds up in production.
My focus is on the gap between a model that can do something and a system that reliably does it.

## What I Work On

- Spec-driven agentic pipelines — turning intent into implementable steps with enough structure to catch failures early
- MCP servers and context systems — practical interfaces between language models, tools, and real-world data
- Cloud and observability infrastructure — tracing, repeatable environments, and stacks that are debuggable under pressure

## Current Technical Themes

### Grounded AI Systems

Models improvise when they lack context. I build around that: deterministic tooling, source-grounded retrieval, explicit interfaces, and failure modes that are visible rather than silent.

### Specification as Engineering

Most AI-assisted development breaks at the handoff between idea and implementation. Better specs, tighter feedback loops, and disciplined workflows make the handoff explicit instead of implicit.

### Infrastructure You Can Operate

Observability by default. Simple enough to reason about at 2am. I care more about tracing and repeatability than clever abstractions.

## Now

Building an AI infrastructure layer — the plumbing that makes agentic systems operable at scale:

- **Federated MCP gateway** — actions router with a thin IAM layer for agent registration and qualification (OAuth 2.1, OBO flows)
- **Decision trace observability** — capturing the full reasoning trail, not just inputs and outputs
- **Lakehouse for agentic data** — mining structured signal from SOR systems to ground agent decisions
- **K8s-based orchestration** — continuous tasks, long-horizon workflows, and on-demand workloads under one scheduler
- **Local AI gateway** — routing to cloud-hosted OSS models for cost and latency optimization

OSS vs managed is still an open decision.

## How I Work

- Clarity first. Speed follows from clear interfaces, not the other way around.
- Explicit tradeoffs over implicit assumptions.
- I work best where product ambiguity, technical depth, and execution pressure overlap — and someone needs to translate between them.
