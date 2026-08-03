## Matthias Meyer

I run [StudioMeyer](https://studiomeyer.io) in Palma de Mallorca. Websites and AI systems for companies, plus six MCP servers I host and keep running. Whatever turns out to be reusable ends up open source in [@studiomeyer-io](https://github.com/studiomeyer-io).

Most of it comes back to memory. An agent that forgets everything between sessions is a demo, not a tool. So I build the parts that make agents remember, evolve, and hold up under load.

### Current work

- [local-memory-mcp](https://github.com/studiomeyer-io/local-memory-mcp) — persistent memory for Claude, Cursor and Codex. Hybrid BM25 and vector retrieval, contradiction detection, knowledge graph. Runs on SQLite. No cloud, no API keys.
- [darwin-agents](https://github.com/studiomeyer-io/darwin-agents) — agents that improve themselves. Self-evolving prompts via A/B testing, multi-model critics, safety gates. Plus a [LangGraph adapter](https://github.com/studiomeyer-io/darwin-langgraph).
- [mcp-armor](https://github.com/studiomeyer-io/mcp-armor) — a Rust sidecar that wraps a stdio MCP server and inspects everything crossing the boundary. Companion tools: [covenant](https://github.com/studiomeyer-io/mcp-covenant) for interface versioning, [herald](https://github.com/studiomeyer-io/mcp-herald) for spec migrations, [passport](https://github.com/studiomeyer-io/mcp-passport) for registry readiness, [gauntlet](https://github.com/studiomeyer-io/mcp-gauntlet) for fuzzing and load.
- [mcp-personal-suite](https://github.com/studiomeyer-io/mcp-personal-suite) — local-first personal tooling, bring your own keys.

TypeScript for most of it, Rust where a single binary is the right answer, Python where the ecosystem already lives there. MIT unless a repo says otherwise.

### Elsewhere

[studiomeyer.academy](https://studiomeyer.academy) is a free six-level course on working memory-first with AI, in German, English and Spanish. [matthiasmeyer.tech](https://matthiasmeyer.tech) is where I write up the architecture behind these repos, including the trade-offs I would make differently now. [aifinca.es](https://aifinca.es) runs AI operator workshops on a finca here on the island. [meetmyagent.io](https://meetmyagent.io) is a free AI-native visibility platform. [aklow-labs.com](https://aklow-labs.com) is where the research that is not ready for customers lives.

Issues and pull requests get answered. If you build something with any of this, I want to hear about it: hello@studiomeyer.io
