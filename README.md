# Nikita Khava

I build LLM systems and data pipelines in Python: agents that take on real work, evaluation that shows whether a
change actually helped, and the guardrails and source tracking that make the output checkable. I am also an
investigative journalist and OSINT researcher, which is where the habit of tracing every claim back to its source
comes from.

## Repositories

- **[leadscout](https://github.com/csakegyruszki/leadscout)**: lead triage service. A lead from a web form, the API
  or an incoming e-mail is researched, screened for compliance and sanctions and scored against a profile. Mail
  leads come back with a reply draft. Every fact links to the source it came from.
- **[agent-governance-hooks](https://github.com/csakegyruszki/agent-governance-hooks)**: nine hooks for coding agents.
  They block destructive SQL, recursive deletes and secret leaks, keep delegation scoped, and refuse to close a task
  without passing evidence. 350+ tests.
- **[evalfloor](https://github.com/csakegyruszki/evalfloor)**: runs the same Claude Code task several times per
  configuration and reports a difference only when it is larger than run-to-run noise. On PyPI.
- **[provtrail](https://github.com/csakegyruszki/provtrail)**: append-only, hash-chained log of the sources used in
  LLM-assisted research, with a CLI, a Claude Code hook, an agent skill and an MCP server. On PyPI.
- **[langgraph-digest](https://github.com/csakegyruszki/langgraph-digest)**: news digest pipeline built as a LangGraph
  state machine, with Langfuse tracing and automatic repair of broken links.
- **[quick-read](https://github.com/csakegyruszki/quick-read)**: page reader for LLM agents. It checks every redirect
  against private address ranges and marks the extracted text as untrusted.

## Elsewhere

- [aiforradalom.hu](https://aiforradalom.hu): Hungarian AI news site I built and run. A chain of agents collects
  the sources, writes the daily items and sends weak drafts back for another pass.
- [dontes.app](https://dontes.app): legal search over about 311,000 Hungarian and EU court decisions. I am one of
  its developers.
- Investigations into company ownership, sanctions and influence networks, published with
  [VSquare](https://vsquare.org).

Python, FastAPI, Pydantic, PostgreSQL, SQLite, Docker, Qdrant, LangGraph, the Anthropic and OpenAI SDKs.

[LinkedIn](https://www.linkedin.com/in/khavanikita)
