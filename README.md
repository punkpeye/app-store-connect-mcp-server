# App Store Connect MCP Server

A Model Context Protocol (MCP) server for interacting with the App Store Connect API. This server provides tools for managing beta testers, beta groups, and apps in App Store Connect.

## Installation
Add the following to your Claude Config JSON file
```
{
  "mcpServers": {
    "app-store-connect": {
      "command": "npx",
      "args": [
        "y",
        "@joshuarileydev/app-store-connect-mcp-server"
      ],
      "env": {
        "APP_STORE_CONNECT_KEY_ID": "KEY ID",
        "APP_STORE_CONNECT_ISSUER_ID": "ISSUER ID",
        "APP_STORE_CONNECT_P8_PATH": "P8 FILE PATH"
      }
    }
  }
}
```