# AI Governance Waiver Desk MCP

Approve AI exceptions with expiry dates, owners, and receipts.

AI Governance Waiver Desk is a paid remote MCP approval gate for AI use cases, model risk, exception reasons, owners, approvers, expiry dates, and governance receipts.

This is a public documentation project for AI Governance Waiver Desk MCP. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://aiwaiverdesk.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=aiwaiverdesk_public_docs&utm_content=readme_primary_home
- Pricing: https://aiwaiverdesk.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=aiwaiverdesk_public_docs&utm_content=readme_pricing
- Checkout: https://aiwaiverdesk.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=aiwaiverdesk_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://aiwaiverdesk.clauxel.com/mcp
- Server card: https://aiwaiverdesk.clauxel.com/server-card.json
- Registry name: `com.clauxel.aiwaiverdesk/aiwaiverdesk-mcp`
- Tools: `evaluate_ai_waiver`, `request_policy_exception`, `check_waiver_expiry`, `issue_waiver_receipt`, `export_governance_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

AI governance, risk, compliance, product, and platform teams.

## Capabilities

- waiver policy queue
- risk level review
- expiry conditions
- reviewer signoff
- allow/review/deny JSON

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
