# LexSocket Plugin Marketplace

Official plugin marketplace for [LexSocket.ai](https://lexsocket.ai) — European public procurement data for your AI assistant.

## Available plugins

| Plugin | Description |
|--------|-------------|
| **tenders** | Search, analyze, and monitor European public tenders (TED + 18 national sources) |

## Installation

### 1. Add the marketplace

In Claude Code, run:

```
/plugin marketplace add lexsocket/marketplace
```

### 2. Install a plugin

```
/plugin install tenders@lexsocket
```

### 3. Authenticate

Run `/mcp` in Claude Code and complete the OAuth2 login with your [lexsocket.ai](https://lexsocket.ai) account (free registration required).

### 4. Start using it

```
/tenders:hello
```

Or just ask Claude directly:

```
Find open IT tenders in France above 100,000 EUR
```

## What you get

The **tenders** plugin connects Claude Code to a unified MCP server with two data sources:

- **TED** — Above-threshold EU/EEA tenders from Tenders Electronic Daily
- **National Tenders** — Below-threshold tenders from 18 countries (FR, GB, DE, ES, IT, NL, IE, PT, DK, PL, AT, CH, BE, NO, CZ, HU, RO, HR)

## Support

- Website: [lexsocket.ai](https://lexsocket.ai)
- Email: support@lexsocket.ai
