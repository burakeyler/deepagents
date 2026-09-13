# Files

- [Deep Agents Code Architecture](code-agent.md) - Architecture of dcode's normal terminal-client and local LangGraph-server boundary, durable workspace binding, streaming and state seams, startup and cleanup behavior, and separate ACP stdio mode.
- [SDK Middleware Stack](middleware-stack.md) - How create_deep_agent assembles, orders, filters, and delegates through middleware for the main agent and subagents. Covers profile exclusions, request transformation, private state, context compaction, and extension safety boundaries.
- [Monorepo Architecture Overview](overview.md) - System-level map of the independently versioned Deep Agents packages, their public entry points, dependency directions, and the boundaries between the SDK, dcode, ACP, Talon, evals, and partner integrations.
- [dcode Runtime Behavior and Failure Handling](runtime-behavior.md) - Operational semantics for dcode's remote LangGraph client, server-owned workspace runtimes, approval-mode persistence, and recovery boundaries.
- [SDK Construction and Execution](sdk-construction-execution.md) - Trace how create_deep_agent resolves its dependencies and policies into a LangChain-compiled LangGraph agent, then how state, streaming, tool calls, checkpoints, and interrupts behave at runtime.
- [Source Map and Change Routing](source-map.md) - Route a Deep Agents behavior change from its user-visible contract to the package that owns it, its implementation seam, focused tests, and release boundary. Use this as responsibility-based navigation rather than a file inventory.
