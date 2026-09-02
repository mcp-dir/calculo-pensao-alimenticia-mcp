# Instalação detalhada

Cálculo de Pensão Alimentícia é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculo-pensao-alimenticia`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculo-pensao-alimenticia` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculo-pensao-alimenticia` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculo-pensao-alimenticia` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculopensaoalimenticia` (ou `servers.calculopensaoalimenticia` no VS Code) do config do cliente e reinicie.
