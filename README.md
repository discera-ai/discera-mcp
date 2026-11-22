# Discera MCP server

<img src="assets/logo.png" alt="Discera" width="72">

Discera (discera.ai) is an AI-native competitive and buyer intelligence platform for B2B companies.
It turns your competitors' moves and your sales calls into instant answers with sources and
battlecards that stay current.

This repository holds the connection details for the Discera MCP server. It does not contain the
server itself.

## Connect

| | |
| --- | --- |
| Endpoint | `https://mcp.discera.ai/mcp` |
| Transport | Streamable HTTP |
| Sign-in | OAuth 2.1. Sign in with your Discera account. |
| Works with | Claude, ChatGPT, Gemini |

You need a Discera workspace. Plans start at $99 a month, with a 14-day trial and no credit card:
https://discera.ai/pricing

Setup guide: https://discera.ai/product/mcp

### Claude Code

```
/plugin marketplace add discera-ai/discera-mcp
/plugin install discera@discera
```

This adds the connector. Claude asks you to sign in to Discera the first time it uses a tool.

### Other clients

Add a custom connector (or remote MCP server) with the endpoint above and sign in when prompted.

## What you can ask

- What changed on our competitors' pricing pages this week?
- How does their entry plan compare with ours?
- Does our battlecard claim about their SSO still hold?
- Which objections came up most in last month's calls?
- Give me a deal-prep brief on one of my tracked competitors.

Deal-level win/loss questions need the Team plan, from $299 a month, with Gong and HubSpot
connected.

## How Discera handles your data

Gong and HubSpot connections are read-only. Your team controls which competitive findings enter the
shared knowledge base. A SOC 2 program is underway. Details: https://discera.ai/security

## Support

hello@discera.ai · [Privacy](https://discera.ai/privacy) · [Terms](https://discera.ai/terms)

## License

The manifests in this repository are released under the MIT License. The Discera name
and logo are trademarks of Discera Inc.
