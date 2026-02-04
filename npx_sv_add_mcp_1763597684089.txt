It looks like you’re trying to run an MCP (Model Context Protocol) command with Svelte’s CLI — specifically:
npx sv add mcp

In Svelte’s CLI, sv add mcp is used to add MCP support to your project so that your development environment (like VS Code, Cursor, or Claude Code) can communicate with MCP servers.

Correct Usage
If you want to add MCP to your Svelte project, you should run:
Bashnpx sv add mcp

This will:

Install the MCP client dependencies.
Create a .mcp configuration folder in your project.
Add example MCP server configurations.


After Running the Command
Once installed, you can:

Configure MCP servers in .mcp/config.json.
Use npx sv mcp list to see available MCP servers.
Start an MCP server with:Bashnpx sv mcp start <server-name>




Example: Adding a Local MCP Server
If you want to add a local MCP server (e.g., for Svelte docs), you might edit .mcp/config.json like:
Json{
  "servers": {
    "svelte-docs": {
      "command": "npx",
      "args": ["@sveltejs/mcp-docs", "-y"]
    }
  }
}


✅ Tip: Make sure you have Node.js ≥ 18 installed before running MCP commands.

If you want, I can give you a full step-by-step guide to set up MCP in a Svelte project and connect it to your IDE so it works immediately.

Do you want me to prepare that?
