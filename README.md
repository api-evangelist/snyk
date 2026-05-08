# Snyk (snyk)

Snyk is a developer-first security platform covering code, open-source dependencies, container images, and infrastructure-as-code. The Snyk REST API and V1 API expose groups, organizations, projects, issues, targets, integrations, audit logs, SBOMs, container images, custom base images, webhooks, exports, and OAuth Apps for application-security teams.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/snyk/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=snyk-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags

- Security, DevSecOps, Vulnerability Management, Application Security, SCA, SAST, Container Security, IaC

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Snyk REST API - Groups | Top-level tenancy: list groups, list orgs in a group, manage memberships and group settings. |
| Snyk REST API - Organizations | Manages orgs, memberships, roles, and service accounts; the scope for projects and policy. |
| Snyk REST API - Projects | List, retrieve, update, delete, and re-test Snyk projects (code, container, IaC, manifests). |
| Snyk REST API - Issues | Queries open and resolved issues with filters by severity, project, target, and ignore reason. |
| Snyk REST API - Targets | Manages upstream import sources (SCM repos, registries, IaC sources). |
| Snyk REST API - Integrations | Connections to GitHub/GitLab/Bitbucket/Azure Repos, container registries, and clouds. |
| Snyk REST API - Audit Logs | Group- and org-level audit events for compliance pipelines. |
| Snyk REST API - SBOMs | Generates CycloneDX or SPDX SBOMs from a project's resolved dependency graph. |
| Snyk REST API - Container Images | Inspects scanned images, base-image relationships, and vulnerability views. |
| Snyk REST API - Custom Base Images | Registers internal-approved base images for upgrade recommendations. |
| Snyk REST API - Webhooks | Signed event subscriptions for project, issue, and test events. |
| Snyk REST API - Export | Asynchronous bulk export of issues, projects, dependencies, and license data. |
| Snyk REST API - Apps (OAuth) | Manages Snyk Apps - OAuth2 extensibility for third-party tools. |
| Snyk V1 API (Legacy) | Original Snyk REST API; project import/test/monitor and reporting endpoints not yet ported. |

## Regional Endpoints

- **US:** https://api.snyk.io
- **EU:** https://api.eu.snyk.io
- **AU:** https://api.au.snyk.io

## Common Properties

- [Website](https://snyk.io/)
- [Documentation](https://docs.snyk.io/snyk-api)
- [API Reference](https://apidocs.snyk.io/)
- [Plans](plans/snyk-plans-pricing.yml) - API Commons Plans 0.1
- [RateLimits](rate-limits/snyk-rate-limits.yml) - API Commons Rate Limits 0.1
- [FinOps](finops/snyk-finops.yml) - FOCUS-aligned FinOps Framework 1.0

## Plans

- **Free** - $0; unlimited contributing developers; hard test caps per product; no API token use.
- **Team** - From $25/contributing-dev/month; 5-dev minimum, 10-dev maximum; API access included.
- **Ignite** - $1,260/contributing-dev/year; up to 50 developers; SCA/SAST/IaC/Container plus 10 DAST targets.
- **Enterprise** - Custom; SSO/SAML, FedRAMP, data residency, group governance, service accounts, add-ons.

## Rate Limits

- 429 Too Many Requests on per-token throttling with Retry-After.
- Free/Team plans cannot use personal access tokens for the API; use service accounts on Enterprise/Ignite.
- Bulk Export jobs run async with limited per-org concurrency.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
