# Cademí

Cademí is a platform for online courses. This is where developers and AI agents build on it.

## Build with Cademí

- **[MCP](https://cademi.dev/mcp)**: connect Claude and other AI assistants to your account at `https://mcp.cademi.dev/mcp`. Sign in with Cademí; there is no API key to paste.
- **[CLI](https://cademi.dev/cli/installation)**: every API operation as a command, with webhooks forwarded to your machine, config as code, and a sandbox.
- **[API v3](https://cademi.dev/api)**: REST API with OpenAPI, cursor pagination, idempotent writes, events, and webhooks.
- **[Webhooks](https://cademi.dev/webhooks)**: signed deliveries, with filters per event type and payload detail levels.

Install the CLI and sign in. On macOS and Linux:

```sh
curl -fsSL https://cli.cademi.dev/install.sh | bash
cademi auth login
```

On Windows PowerShell:

```powershell
irm https://cli.cademi.dev/install.ps1 | iex
cademi auth login
```

## Repositories

- [**developers**](https://github.com/minhacademi/developers): report bugs, request features, and ask questions about the MCP, the CLI, the API, and webhooks.
- [**skills**](https://github.com/minhacademi/skills): Agent Skills that teach Claude Code, Cursor, Codex, and other agents to work with Cademí. The first one covers the `cademi` CLI.

## Get help

- Documentation: [cademi.dev](https://cademi.dev)
- Bugs and questions: [minhacademi/developers](https://github.com/minhacademi/developers/issues/new/choose)
- Security issues: follow the [security policy](https://github.com/minhacademi/developers/security/policy), never a public issue.
- Cademí: [cademi.com.br](https://cademi.com.br)
