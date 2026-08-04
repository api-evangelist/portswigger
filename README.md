# PortSwigger (portswigger)

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
