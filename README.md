# Installation

To install the MCP server, add the following configuration to your setup:

```json
{
    "mcpServers": {
        "Demo" : {
            "command": "uvx",
            "args": ["--from", "git+https://github.com/rogueplanet-x/deployment.git", "mcp-server"]
        }
    }
}
```

This configuration specifies:
- A Demo MCP server instance
- Uses the `uvx` command for deployment
- Pulls from the deployment repository
- Targets the `mcp-server` component