# Changelog

## 0.1.1

- Updated `zod` to `4.4.3` after the initial public repository dependency check.
- Kept package, runtime and MCP registry manifest versions aligned for the first public release line.

## 0.1.0

- Initial Withings MCP implementation.
- Added OAuth setup/auth/doctor CLI with local config and token storage under `~/.withings-mcp/`.
- Added 16 MCP tools, 6 resources and 3 prompts.
- Added signed Withings token flow plus Public API tools for body measures, daily activity, workouts, sleep summaries, sleep periods and heart records.
- Added daily and weekly summaries, privacy modes, SQLite cache support, privacy audit, connection status and Hermes agent manifest checks.
