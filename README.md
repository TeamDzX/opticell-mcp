# Opticell tools for Claude

Free MCP servers and companion tools that connect Claude, and other AI
agents, to Opticell apps. Each tool has its own repository with install
steps, releases and an issue tracker. This page is the index.

## MCP servers

| | Runs on | Install | |
|---|---|---|---|
| **[WorkFlow Companion](https://github.com/TeamDzX/workflow-companion)**<br>Claude works in your WorkFlow tasks, notes and projects through your own iCloud, with WorkFlow on an iPhone, iPad or Mac doing the work. | Windows · Linux · macOS | `npx -y @opticell/workflow-companion setup`<br>or [`WorkFlow.mcpb`](https://github.com/TeamDzX/workflow-companion/releases/latest) for Claude Desktop | [MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=io.github.TeamDzX/workflow-companion) |
| **[WorkFlow Agent Bridge](https://github.com/TeamDzX/workflow-agent-bridge)**<br>The Mac route: the `wf` CLI plus an MCP server that reads WorkFlow's snapshot and writes through the running app. Open source (MIT). | macOS | `python3 workflow-mcp/server.py --print-config` | MIT |

## Companion apps and skills

| | |
|---|---|
| **[MyLLM Connect](https://github.com/TeamDzX/myllm-connect)** | Run your own private AI backend on a Mac or PC and connect MyLLM to it in one tap, over trusted HTTPS. |
| **[MyLLM Skills](https://github.com/TeamDzX/myllm-skills)** | Curated open Agent Skills for MyLLM, the on-device iOS AI agent. Install with `/skill add teamdzx/myllm-skills`. |

## How these tools treat your data

- **Your data stays yours.** The servers talk to the app on your own devices,
  or to your own private iCloud. Nothing passes through Opticell's servers.
- **No destructive tools.** An agent can create, comment, tick and complete.
  It can't delete your data.
- **Every write is visible.** The apps log each agent action, in Command
  History in WorkFlow for example.

## Help

Open an issue in the tool's own repository. For the apps themselves, see
[opticell-limited.com](https://www.opticell-limited.com).
