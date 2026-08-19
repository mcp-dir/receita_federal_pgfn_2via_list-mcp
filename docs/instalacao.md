# Instalação detalhada

Receita Federal: PGFN (CND Federal) - Lista Segunda Via é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_receita_federal_pgfn_2via_list`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_receita_federal_pgfn_2via_list` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_receita_federal_pgfn_2via_list` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_receita_federal_pgfn_2via_list` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.receita_federal_pgfn_2via_list` (ou `servers.receita_federal_pgfn_2via_list` no VS Code) do config do cliente e reinicie.
