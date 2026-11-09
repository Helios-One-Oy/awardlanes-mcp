# awardlanes MCP

awardlanes is a read-only MCP connector for USDA food-purchase award lanes. Ask Claude, ChatGPT, Claude Code or Cursor to search lanes in your up-to-three-state territory, open an award, summarize states, find a vendor's awards, or check your trial. Every result carries a USDA source link and a matching awardlanes view. During the trial or on a paid plan it uses the full territory; after an unpaid trial it returns the same 20-lane sample shown on the web. Equipment is inferred from the commodity name when USDA does not state it.

Connect at `https://awardlanes.com/mcp` with OAuth 2.1, DCR, and PKCE S256:

- Claude: add a custom connector using the URL above.
- ChatGPT: add a remote MCP connector in developer mode.
- Claude Code: `claude mcp add awardlanes https://awardlanes.com/mcp` and authenticate.
- Cursor: add a streamable HTTP MCP server with the URL above.

Documentation: https://awardlanes.com/docs/mcp  
Privacy: https://awardlanes.com/privacy  
Terms: https://awardlanes.com/terms  
Support: hello@awardlanes.com
