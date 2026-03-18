# NEXUS Finance — Public Audit Receipts

Auto-generated audit receipts from the NEXUS-120 Engine.
Updated hourly via GitHub Actions.

## Contents

### packages/

`AUD_001_PACKAGE_{timestamp}.json` — Full audit packages including:
- Live chain state (block, ETH/USD, collateral, debt, CR)
- SOV_001 / SOV_003 / SOV_005 pillar verdicts
- Overall verdict: `PASS` / `WARN` / `FAIL`
- Classified fail reasons: `testnet_env` / `structural` / `economic`
- SHA-256 receipt hash

### pillar-receipts/

Individual pillar receipts:
- `CAP_LIVE_RECEIPT_*.json` — SOV_003 Capital Adequacy
- `RL_LIVE_MASTER_*.json` — SOV_005 Risk Lattice

## Verification

Each receipt contains a SHA-256 hash. Receipts are append-only and immutable by design.

## Live System

- [nexus-finance.org](https://nexus-finance.org) — live protocol dashboard
- [nexus-finance.org/receipts](https://nexus-finance.org/receipts) — audit trail viewer

© 2026 NEXUS Finance
