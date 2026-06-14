# PortSwigger GraphQL

## Overview

PortSwigger exposes a native GraphQL API for Burp Suite DAST (Dynamic Application Security Testing). This is the recommended integration path for all new Burp Suite DAST integrations, providing the broadest feature surface including site management, scan orchestration, vulnerability retrieval, agent configuration, and report generation.

PortSwigger is also the industry's leading researcher on GraphQL API security vulnerabilities, publishing attack techniques, lab exercises, and tooling through the Web Security Academy.

## Burp Suite DAST GraphQL API

**Endpoint:** `https://your-server/graphql/v1`

**Authentication:** API key in the `Authorization` header.

**Documentation:** https://portswigger.net/burp/documentation/dast/user-guide/api-documentation/graphql-api

**Schema Reference:** https://portswigger.net/burp/extensibility/enterprise/graphql-api/index.html

The DAST GraphQL API exposes operations for:

- **Sites** — register and manage target applications for scanning
- **Scans** — initiate, monitor, and cancel security scans
- **ScanConfigurations** — reusable scan config profiles
- **Issues** — retrieve discovered vulnerabilities with severity, confidence, and evidence
- **Agents** — manage Burp Suite DAST scanning agents
- **Reports** — generate vulnerability reports in multiple formats
- **AgentPools** — group and allocate agents for distributed scanning

## Web Security Academy (Conceptual Model)

The Web Security Academy at https://websecurity.academy (portswigger.net/web-security) provides free interactive security training. While the platform does not expose a public API, the learning platform data model is documented here for reference and integration planning.

**Platform URL:** https://portswigger.net/web-security

The schema file `portswigger-schema.graphql` documents both the DAST GraphQL API types and the Web Security Academy conceptual model, along with GraphQL-specific vulnerability patterns that PortSwigger researches and teaches.

## GraphQL Security Research

PortSwigger's Web Security Academy includes a dedicated GraphQL API attacks topic covering:

- Introspection-based reconnaissance
- Bypassing introspection defenses
- Finding hidden endpoints
- Exploiting overpowered queries and mutations
- IDOR via GraphQL
- GraphQL injection

Labs are available at: https://portswigger.net/web-security/graphql
