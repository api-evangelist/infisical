# Infisical (infisical)

Infisical is an open-source secrets management platform that provides developers with a centralized, end-to-end encrypted vault for storing, syncing, and rotating secrets across teams, environments, and cloud infrastructure. The platform offers a REST API enabling programmatic management of secrets, machine identities, PKI certificates, and privileged access controls. Infisical integrates with CI/CD pipelines, Kubernetes, cloud providers, and developer toolchains through official SDKs for Node.js, Python, Go, Java, Ruby, .NET, Rust, C++, and PHP. Available as both a managed cloud service and a self-hostable open-source deployment (MIT license), Infisical (YC W23) supports audit logging, SAML SSO, SCIM, dynamic secrets, and secret rotation workflows for enterprise teams.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/infisical/refs/heads/main/apis.yml
- **Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=infisical-api-evangelist&utm_content=repo

## Tags

- Secrets Management
- Security
- DevOps
- Developer Tools
- Open Source
- PKI
- Certificates
- Privileged Access Management
- CI/CD
- Kubernetes
- Environment Variables
- Encryption

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Infisical REST API | Programmatic access to secrets management, machine identities, PKI, and privileged access management via HTTPS with Bearer token authentication. | [Docs](https://infisical.com/docs/api-reference/overview/introduction) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans and Pricing | [plans/infisical-plans-pricing.yml](plans/infisical-plans-pricing.yml) |
| Rate Limits | [rate-limits/infisical-rate-limits.yml](rate-limits/infisical-rate-limits.yml) |
| FinOps | [finops/infisical-finops.yml](finops/infisical-finops.yml) |

**Pricing Summary:**
- **Free:** $0/month — up to 5 identities, 3 projects, 3 environments
- **Pro:** $18/identity/month — unlimited projects, SAML SSO, RBAC, secret rotation, 90-day audit logs
- **Enterprise:** Custom pricing — dedicated infrastructure, dynamic secrets, SCIM, LDAP, 99.99% SLA
- **Self-Hosted:** Free (MIT license) — no rate limits, full platform features

**Rate Limits (Cloud):**

| Operation | Free | Pro |
|-----------|------|-----|
| Read (GET/LIST) | 200/min | 350/min |
| Write (CREATE/UPDATE/DELETE) | 90/min | 200/min |
| Secret Operations | 120/min | 300/min |
| Identity/Project Creation | 30/min | 30/min |

Self-hosted deployments have no rate limits. Enterprise customers can request custom limits.

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://infisical.com |
| Documentation | https://infisical.com/docs |
| API Reference | https://infisical.com/docs/api-reference/overview/introduction |
| GitHub Org | https://github.com/Infisical |
| LinkedIn | https://www.linkedin.com/company/infisical |
| Blog | https://infisical.com/blog |
| Pricing | https://infisical.com/pricing |
| Status Page | https://status.infisical.com |
| X (Twitter) | https://twitter.com/infisical |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
