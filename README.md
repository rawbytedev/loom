# loom

`loom` is a single-binary Git workflow and issue loom(coord)ination tool. It is designed around a small public contract in `pkg/model` and a set of focused internal packages for issues, worktrees, agents, and MCP tooling.

## Commands (Planned, can be changed any time)

- `loom proof` — run the proof workflow and validation checks.
- `loom serve` — start the MCP server surface.

## Package layout (Planned, can be changed any time)

- `cmd/loom` — CLI entrypoint
- `pkg/model` — public types and state contract
- `internal/issue` — issue graph and SQLite-backed persistence
- `internal/worktree` — worktree lifecycle and verification
- `internal/agent` — process supervision and registry
- `internal/mcp` — MCP server and tool definitions
- `testdata` — integration fixture repositories

