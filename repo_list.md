### List of Repos via Context 7 MCP
This is a list of GitHub repos that you should be able to access via the Context 7 MCP.

Here are the Context 7 MCP settings: https://github.com/upstash/context7

#### For VS Code

#### Remote
```
{
  "mcpServers": {
    "context7": {
      "type": "http",
      "url": "https://mcp.context7.com/mcp"
    }
  }
}
```

#### Local
```
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7-mcp"]
    }
  }
}
```


