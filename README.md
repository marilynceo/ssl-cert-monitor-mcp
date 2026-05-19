# ssl-cert-monitor-mcp

Comprehensive SSL certificate monitoring u2014 check expiry, chain validation, OCSP stapling, SSL Labs grade, HTTP redirects. Monitor multiple domains with alerting and exportable reports.

## Quick Start

```bash
git clone https://github.com/marilynceo/ssl-cert-monitor-mcp.git
cd ssl-cert-monitor-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://ssl-cert-monitor.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/ssl-cert-monitor-mcp

# Or connect directly via MCP client
# Endpoint: https://ssl-cert-monitor.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
