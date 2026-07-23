# Fifth Third Bancorp (fifth-third-bancorp)

Fifth Third Bancorp is a Fortune 500 super-regional financial services company
providing commercial banking, branch banking, consumer lending, and wealth and
asset management services across multiple U.S. states. Its public, documented
API surface is delivered through **Newline by Fifth Third** — an API-first
Banking-as-a-Service platform (built on the 2023 Rize Money acquisition) that
lets fintechs and enterprises embed payments, deposit, and card products
directly with Fifth Third Bank. This repository captures the APIs, developer
tools, and machine-readable API artifacts for Fifth Third Bancorp.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fifth-third-bancorp/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Producing
- **Access:** Partner (sandbox self-serve, partner onboarding for production)

## Tags

- Banking
- United States
- Embedded Finance
- Banking as a Service
- Payments (ACH, Wire, Real-Time Payments)
- Deposits / Card Issuing
- Commercial Banking
- Consumer Lending
- Wealth Management
- Treasury Management
- Super-Regional Bank
- Fortune 500

## APIs

The **Newline Platform API** (OpenAPI 3.0.2, 53 operations across 13 resource
groups) is documented at [developers.newline53.com](https://developers.newline53.com/)
with a downloadable spec, official TypeScript/Java/.NET SDKs, a Postman
collection, and an MCP server. Product families captured here:

- **Auth** — JWS/HMAC-HS512 token exchange
- **Customers** and **Customer Products** — onboarding + KYC/AML lifecycle
- **Products**, **Pools**, **Custodial Accounts**, **Synthetic Accounts**
- **Transfers** and **Combined Transfers** — ACH, wire, RTP, book transfers
- **Transactions**, **Returns**, **Virtual Reference Numbers**
- **Sandbox** — simulation and error-scenario testing

Consumer (retail) account data access at the 53.com brand remains
aggregator-mediated (e.g. Plaid); there is no published first-party FDX/CFPB
1033 endpoint. See `review.yml` for the full reviewer finding and spec
provenance.

## Common Properties

- [Website](https://www.53.com/)
- [Developer Portal](https://developers.newline53.com/)
- [Documentation](https://developers.newline53.com/docs/welcome)
- [OpenAPI](https://developers.newline53.com/openapi/newline-platform-api.json)
- [GitHub Organization](https://github.com/newline53)
- [Status Page](https://status.newline53.com)
- [Investor Relations](https://ir.53.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
