Install this MCP server by adding the following JSON code to your JSON config file

```json
{
  "mcpServers": {
    "mcp-chess-server": {
      "command": "uvx",
      "args": [
        "from",
        "git+https://github.com/gaurav743/mcp-chess-server.git",
        "chess"
      ]
    }
  }
}
```