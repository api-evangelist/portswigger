# PortSwigger (portswigger)

PortSwigger is the UK-based security research company behind Burp Suite, the industry-standard web and API security testing platform used by penetration testers and enterprise AppSec teams worldwide. The platform spans three editions — Community (free), Professional (annual per-user subscription), and DAST (enterprise dynamic application security testing) — and exposes developer APIs including a GraphQL API and REST API for automation and CI/CD integration, a Java-based Montoya extension API for building custom Burp Suite extensions, and an official MCP Server for AI client integration.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/portswigger/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/portswigger/refs/heads/main/apis.yml)

Naftiko Run: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=portswigger-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=portswigger-api-evangelist&utm_content=repo)

## Tags

Security, Web Security, Penetration Testing, DAST, API Security, Developer Tools

## APIs

- **Burp Suite DAST GraphQL API** — Primary automation API for DAST; manages sites, scans, issues, agents, and reports via GraphQL at `your-server/graphql/v1`.
  - Docs: https://portswigger.net/burp/documentation/dast/user-guide/api-documentation/graphql-api
  - Schema: https://portswigger.net/burp/extensibility/enterprise/graphql-api/index.html

- **Burp Suite DAST REST API** — Legacy-compatible REST API for CI/CD scan initiation; API-key authenticated.
  - Docs: https://portswigger.net/burp/documentation/dast/user-guide/api-documentation/rest

- **Burp Suite Professional REST API** — Local REST API embedded in Burp Suite Professional for tool integration during manual pentests.
  - Docs: https://portswigger.net/burp/documentation/desktop/settings/suite/rest-api

- **Burp Suite Montoya Extension API** — Java SDK for building custom Burp Suite extensions published to the BApp Store.
  - Docs: https://portswigger.github.io/burp-extensions-montoya-api/javadoc/burp/api/montoya/MontoyaApi.html
  - GitHub: https://github.com/PortSwigger/burp-extensions-montoya-api

- **Burp Suite MCP Server** — Official MCP server extension bridging Burp Suite with AI clients (Claude Desktop, etc.) via SSE on localhost:9876.
  - BApp Store: https://portswigger.net/bappstore/9952290f04ed4f628e624d0aa9dccebc
  - GitHub: https://github.com/PortSwigger/mcp-server

## Plans / Rate Limits / FinOps

- [Plans & Pricing](plans/portswigger-plans-pricing.yml) — Community (free), Professional (annual per-user), DAST Enterprise (custom quote + PAYS option with 500 scan-hour/month default cap)
- [Rate Limits](rate-limits/portswigger-rate-limits.yml) — No published per-minute API rate limits; PAYS enforces 500 scan-hours/month default cap
- [FinOps](finops/portswigger-finops.yml) — FOCUS-aligned cost tracking for scan hours and user license consumption

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://portswigger.net |
| Documentation | https://portswigger.net/burp/documentation |
| GitHub Organization | https://github.com/portswigger |
| LinkedIn | https://www.linkedin.com/company/portswigger |
| Blog | https://portswigger.net/blog |
| Pricing | https://portswigger.net/pricing |
| X / Twitter | https://twitter.com/PortSwigger |
| Releases | https://portswigger.net/burp/releases |

## Maintainers

- Kin Lane / kin@apievangelist.com
