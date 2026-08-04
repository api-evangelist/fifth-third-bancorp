# Fifth Third Bancorp (fifth-third-bancorp)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
