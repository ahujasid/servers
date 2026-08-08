<div align="center">

# MCPBlender Servers

**A curated collection of Model Context Protocol server integrations**

[![Stars](https://img.shields.io/github/stars/MCPBlender/servers?style=flat-square&logo=github)](https://github.com/MCPBlender/servers/stargazers)
[![Forks](https://img.shields.io/github/forks/MCPBlender/servers?style=flat-square&logo=github)](https://github.com/MCPBlender/servers/network/members)
[![License](https://img.shields.io/github/license/MCPBlender/servers?style=flat-square)](https://github.com/MCPBlender/servers/blob/main/LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/SNqPn4TcKQ)

</div>

---

## Overview

MCPBlender Servers is a curated collection of [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) server integrations that connect creative and professional tools directly to Claude AI. Each server enables seamless, structured communication between an application and Claude, unlocking AI-assisted workflows without leaving your tool of choice.

Join the community on [Discord](https://discord.gg/SNqPn4TcKQ) to discuss integrations, get help, and share what you're building.

---

## Available Servers

| Server | Description | Install |
|--------|-------------|---------|
| [blender-mcp](https://github.com/MCPBlender/blender-mcp) | Connect Blender to Claude AI — generate geometry, write scripts, and control scenes through natural language | `uvx blender-mcp` |
| [ableton-mcp](https://github.com/MCPBlender/ableton-mcp) | Connect Ableton Live to Claude AI — compose, arrange, and manipulate sessions through natural language | `uvx ableton-mcp` |

---

## What is MCP?

The **Model Context Protocol (MCP)** is an open standard developed by Anthropic that defines how AI models communicate with external tools and data sources. Rather than relying on ad-hoc integrations, MCP provides a structured, secure protocol so that any MCP-compatible client (such as Claude Desktop) can connect to any MCP server.

Key properties:

- **Structured tool definitions** — servers declare their capabilities explicitly
- **Secure, sandboxed access** — the AI only interacts through well-defined interfaces
- **Language-agnostic** — servers can be implemented in Python, TypeScript, or any language
- **Composable** — multiple servers can run simultaneously, each covering a different domain

Learn more at [modelcontextprotocol.io](https://modelcontextprotocol.io/).

---

## Contributing

Contributions are welcome — bug fixes, new servers, documentation improvements, and feature requests all help the ecosystem grow.

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/my-server`)
3. Commit your changes with a clear message
4. Open a Pull Request describing what the integration does and how to test it

Please read [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before submitting.

For questions or to discuss an idea before opening a PR, join the [Discord community](https://discord.gg/SNqPn4TcKQ).

---

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

<div align="center">

[MCPBlender](https://github.com/MCPBlender) · [blendermcp.org](https://blendermcp.org)

</div>
