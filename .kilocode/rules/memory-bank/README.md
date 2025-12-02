# Zai IHA Memory Bank

This project is preconfigured for the Zai Prime Orchestrator's MEM0 memory MCP endpoint. The agent should request long-term context, user preferences, and project breadcrumbs through the `mem0-memory` tool provided by the orchestrator.

- Treat MEM0 as the single source of truth for persistent recall.
- Memory fetches should precede high-risk edits or quality gate checks.
- When updating memory, include concise diffs and links to relevant commits.
