# UK Data MCP Servers

Remote [Model Context Protocol](https://modelcontextprotocol.io) servers for AI agents, built on official UK open data.

- **Free tier** on every server (no key)
- **Monthly Stripe subscription** for unlimited Pro tools
- **Pay-per-call USDC on Base** via [x402](https://x402.org) — no account

Vendor: Donnie Morrison · Contact: dmorrisonwebdesign@gmail.com

## Servers

| Worker | Title | Sub | x402/call | MCP | Manifest |
|--------|-------|-----|-----------|-----|----------|
| `uk-business-calendar-mcp` | UK Business Calendar | ? | $0.02 | https://uk-business-calendar-mcp.donniertf.workers.dev/mcp | https://uk-business-calendar-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-ch-mcp` | uk-ch-mcp | ? | $? | https://uk-ch-mcp.donniertf.workers.dev/mcp | https://uk-ch-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-cqc-mcp` | uk-cqc-mcp | ? | $? | https://uk-cqc-mcp.donniertf.workers.dev/mcp | https://uk-cqc-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-crime-mcp` | uk-crime-mcp | ? | $? | https://uk-crime-mcp.donniertf.workers.dev/mcp | https://uk-crime-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-energy-prices-mcp` | UK Electricity Price Slots | ? | $0.02 | https://uk-energy-prices-mcp.donniertf.workers.dev/mcp | https://uk-energy-prices-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-epc-mcp` | uk-epc-mcp | ? | $? | https://uk-epc-mcp.donniertf.workers.dev/mcp | https://uk-epc-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-flood-mcp` | uk-flood-mcp | ? | $? | https://uk-flood-mcp.donniertf.workers.dev/mcp | https://uk-flood-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-food-alerts-mcp` | UK Food Recall Alerts | ? | $0.02 | https://uk-food-alerts-mcp.donniertf.workers.dev/mcp | https://uk-food-alerts-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-fuel-prices-mcp` | UK Fuel Price Finder | ? | $0.02 | https://uk-fuel-prices-mcp.donniertf.workers.dev/mcp | https://uk-fuel-prices-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-hygiene-mcp` | uk-hygiene-mcp | ? | $? | https://uk-hygiene-mcp.donniertf.workers.dev/mcp | https://uk-hygiene-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-insolvency-alerts-mcp` | UK Insolvency Alerts | ? | $0.05 | https://uk-insolvency-alerts-mcp.donniertf.workers.dev/mcp | https://uk-insolvency-alerts-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-lr-mcp` | uk-lr-mcp | ? | $? | https://uk-lr-mcp.donniertf.workers.dev/mcp | https://uk-lr-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-places-mcp` | uk-places-mcp | ? | $? | https://uk-places-mcp.donniertf.workers.dev/mcp | https://uk-places-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-planning-mcp` | uk-planning-mcp | ? | $? | https://uk-planning-mcp.donniertf.workers.dev/mcp | https://uk-planning-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-postcode-report-mcp` | uk-postcode-report-mcp | ? | $? | https://uk-postcode-report-mcp.donniertf.workers.dev/mcp | https://uk-postcode-report-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-property-deals-mcp` | UK Property Deal Finder | ? | $0.02 | https://uk-property-deals-mcp.donniertf.workers.dev/mcp | https://uk-property-deals-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-salary-benchmarks-mcp` | UK Salary Benchmarks | ? | $0.02 | https://uk-salary-benchmarks-mcp.donniertf.workers.dev/mcp | https://uk-salary-benchmarks-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-sanctions-screen-mcp` | UK Sanctions Screening | ? | $0.08 | https://uk-sanctions-screen-mcp.donniertf.workers.dev/mcp | https://uk-sanctions-screen-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-sponsor-register-mcp` | UK Visa Sponsor Register | ? | $0.05 | https://uk-sponsor-register-mcp.donniertf.workers.dev/mcp | https://uk-sponsor-register-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-tender-alerts-mcp` | UK Tender Alerts | ? | $0.02 | https://uk-tender-alerts-mcp.donniertf.workers.dev/mcp | https://uk-tender-alerts-mcp.donniertf.workers.dev/.well-known/x402 |
| `uk-tenders-mcp` | uk-tenders-mcp | ? | $? | https://uk-tenders-mcp.donniertf.workers.dev/mcp | https://uk-tenders-mcp.donniertf.workers.dev/.well-known/x402 |

## Bundles

- https://uk-mcp-bundles.donniertf.workers.dev/

## Agent discovery

- `/.well-known/mcp` — MCP server card
- `/llms.txt` — agent docs
- `/pricing.json` — Stripe + x402 pricing
- `/.well-known/x402` — x402 pay-per-call manifest
- `/sitemap.xml` · `/robots.txt`

## Topics

`mcp` `model-context-protocol` `x402` `usdc` `cloudflare-workers` `open-data` `uk-data` `ai-agents`
