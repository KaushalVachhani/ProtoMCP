# MCP Model Context Protocol

This script demonstrates the use of a Model Context Protocol (MCP) setup using a Groq-hosted LLM and a custom MCP client/agent architecture.

## Description

- Loads configuration from `mcp_configs.json`
- Initializes an MCP client
- Uses `llama-3.1-8b-instant` via Groq
- Executes a single query:  
  _"Give me the best restaurant in San Francisco"_

## Files

- `main.py` – Entry point
- `mcp_use.py` – Contains `MCPAgent` and `MCPClient` implementations
- `.env` – Contains the `GROQ_API_KEY`
- `mcp_configs.json` – Configuration for the MCP client

## Output

Prints the result of the agent's response to the terminal.
