# AI Governance Waiver Desk MCP

Approve AI exceptions with expiry dates, owners, and receipts.

Paid remote MCP for AI governance waiver checks, exception approvals, expiry review, allow/review/deny JSON, and audit receipts.

## Public Endpoints

- Website: https://aiwaiverdesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://aiwaiverdesk.clauxel.com/mcp
- Server card: https://aiwaiverdesk.clauxel.com/server-card.json
- Registry name: `com.clauxel.aiwaiverdesk/aiwaiverdesk-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `evaluate_ai_waiver`
- `request_policy_exception`
- `check_waiver_expiry`
- `issue_waiver_receipt`
- `export_governance_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://aiwaiverdesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://aiwaiverdesk.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://aiwaiverdesk.clauxel.com/server-card.json
- MCP endpoint: https://aiwaiverdesk.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
