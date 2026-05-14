# FDA AI/ML SaMD Compliance MCP

[![PyPI](https://img.shields.io/pypi/v/fda-samd-mcp)](https://pypi.org/project/fda-samd-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

FDA AI/ML Software as a Medical Device Action Plan + 510(k) + PMA + De Novo pathways for US MedTech and digital health firms.

## Install

```bash
pip install fda-samd-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `classify_sw_device` | FDA SaMD vs SiMD classification + IMDRF risk framework |
| `regulatory_pathway` | 510(k) / De Novo / PMA pathway selection |
| `pccp_template` | Predetermined Change Control Plan generator (locked vs adaptive AI) |
| `good_ml_practice` | FDA Good Machine Learning Practice (GMLP) 10 principles |
| `ai_ml_action_plan` | FDA AI/ML Action Plan focus area assessment |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/fda-samd-mcp -->
