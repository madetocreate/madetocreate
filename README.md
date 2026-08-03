## Matthias Meyer

I run [StudioMeyer](https://studiomeyer.io), a small AI and design studio in Palma de Mallorca. I build websites and AI systems for smaller companies, and most of the tooling I write for that work ends up open source in [@studiomeyer-io](https://github.com/studiomeyer-io).

The through-line in almost everything here is memory. An agent that forgets everything between sessions is a demo, not a tool. So I keep building the pieces that make agents remember, evolve, and not blow up in production: memory servers, a self-evolution layer, and a fair amount of security tooling for the Model Context Protocol, because MCP servers are software you hand a shell to.

Nothing here is a weekend experiment that got abandoned. I use all of it daily, in my own work, before anyone else sees it.

### What I am working on

- [local-memory-mcp](https://github.com/studiomeyer-io/local-memory-mcp) — persistent memory for Claude, Cursor and Codex. SQLite, knowledge graph, no cloud, nothing leaves your machine.
- [darwin-agents](https://github.com/studiomeyer-io/darwin-agents) — agents that measure their own prompts and rewrite them when a variant wins. Plus a [LangGraph adapter](https://github.com/studiomeyer-io/darwin-langgraph).
- [mcp-armor](https://github.com/studiomeyer-io/mcp-armor) — a Rust sidecar that wraps a stdio MCP server and inspects what goes in and out. Part of a small family of MCP tools in Rust: [covenant](https://github.com/studiomeyer-io/mcp-covenant) for interface versioning, [herald](https://github.com/studiomeyer-io/mcp-herald) for spec migrations, [passport](https://github.com/studiomeyer-io/mcp-passport) for registry readiness.
- [mcp-personal-suite](https://github.com/studiomeyer-io/mcp-personal-suite) — local-first personal tooling, bring your own keys.

Mostly TypeScript, Rust where a single binary is the right answer, Python where the ecosystem already lives there. MIT unless a repo says otherwise.

### Elsewhere

[studiomeyer.io](https://studiomeyer.io) is the studio. [studiomeyer.academy](https://studiomeyer.academy) is a free six-level course on working with AI memory-first, in German, English and Spanish. [matthiasmeyer.tech](https://matthiasmeyer.tech) is where I write up the architecture behind these repos, including the trade-offs I would make differently now. [aifinca.es](https://aifinca.es) runs hands-on workshops on a finca here on the island.

If something in here helps you, an issue or a note to hello@studiomeyer.io genuinely makes my day. If it could be better, the issue is more useful than the compliment.
