# Snyk (snyk)

Snyk is a developer-first security platform covering code, open-source dependencies, container images, and infrastructure-as-code. The Snyk REST API and V1 API expose groups, organizations, projects, issues, targets, integrations, audit logs, SBOMs, container images, custom base images, webhooks, and exports for application-security teams.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/snyk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/snyk/refs/heads/main/apis.yml)

## Tags

- Security
- DevSecOps
- Vulnerability Management
- Application Security
- SCA
- SAST
- Container Security
- IaC

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Snyk REST API - Groups

Group-level resource for managing top-level Snyk tenancy. Lists groups, lists organizations within a group, manages group memberships, group-level service accounts, and group-level settings.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15](https://apidocs.snyk.io/?version=2024-10-15)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Groups
- Tenancy
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Organizations

Manages organizations, organization-level memberships, organization roles, and service accounts. Organizations are the unit at which projects, integrations, and most policy and reporting are scoped.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Orgs](https://apidocs.snyk.io/?version=2024-10-15#tag/Orgs)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Organizations
- Memberships
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Orgs)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Projects

Lists, retrieves, updates, deletes, and re-tests Snyk projects. A project represents a single tracked artifact (code repo, container image, IaC manifest, package manifest). Includes per-project settings, attributes, tags, and policy attachment.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Projects](https://apidocs.snyk.io/?version=2024-10-15#tag/Projects)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Projects
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Projects)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Issues

Queries open and resolved issues (vulnerabilities, license violations, code weaknesses) across organizations and groups. Supports rich filters by severity, type, project, target, status, and ignore reason for vulnerability management.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Issues](https://apidocs.snyk.io/?version=2024-10-15#tag/Issues)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Issues
- Vulnerabilities
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Issues)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Targets

Lists and manages targets (the upstream import sources - e.g. GitHub repositories, ECR registries, Terraform sources). Each target may carry many projects under different scan types (SCA, SAST, Container, IaC).

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Targets](https://apidocs.snyk.io/?version=2024-10-15#tag/Targets)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Targets
- Import Sources
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Targets)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Integrations

Manages connections to source-code managers (GitHub, GitLab, Bitbucket, Azure Repos), CI/CD systems, container registries (ECR, ACR, GCR, Docker Hub), and cloud providers used as ingest sources for Snyk scans.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Integrations](https://apidocs.snyk.io/?version=2024-10-15#tag/Integrations)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Integrations
- SCM
- Registries
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Integrations)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Audit Logs

Streams group- and organization-scoped audit log events for security and compliance use cases. Returns event type, actor, timestamp, and content hash.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Audit-Logs](https://apidocs.snyk.io/?version=2024-10-15#tag/Audit-Logs)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Audit Logs
- Compliance
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Audit-Logs)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - SBOMs

Generates and exports Software Bill of Materials documents in CycloneDX or SPDX format for a Snyk project, captured from the resolved dependency graph.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/SBOM](https://apidocs.snyk.io/?version=2024-10-15#tag/SBOM)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- SBOM
- CycloneDX
- SPDX
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/SBOM)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Container Images

Lists and inspects scanned container images and their relationships to projects and target images, including vulnerability and base-image-recommendation views.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Container-Images](https://apidocs.snyk.io/?version=2024-10-15#tag/Container-Images)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Container Images
- Container Security
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Container-Images)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Custom Base Images

Registers custom base images so Snyk can recommend internal-approved base-image upgrades for container projects.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Custom-Base-Images](https://apidocs.snyk.io/?version=2024-10-15#tag/Custom-Base-Images)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Custom Base Images
- Container Security
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Custom-Base-Images)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Webhooks

Subscribes a partner application to Snyk events (project added, issue created, issue ignored, test completed). Each delivery is signed for verification.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Webhooks](https://apidocs.snyk.io/?version=2024-10-15#tag/Webhooks)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Webhooks
- Events
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Webhooks)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Export

Asynchronous bulk-export of issues, projects, dependencies, and license data for large estates. Supports column filtering and produces CSV files retrievable from a generated URL.

- **Human URL:** [https://apidocs.snyk.io/?version=2024-10-15#tag/Issues-Export](https://apidocs.snyk.io/?version=2024-10-15#tag/Issues-Export)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Export
- Reporting
- Bulk
- REST API

#### Properties

- [Documentation](https://apidocs.snyk.io/?version=2024-10-15#tag/Issues-Export)
- [OpenAPI](openapi/snyk-rest-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk REST API - Apps (OAuth)

Manages Snyk Apps, the OAuth2-based extensibility surface that lets third-party applications act on behalf of Snyk users, organizations, and groups.

- **Human URL:** [https://docs.snyk.io/snyk-api/snyk-apps](https://docs.snyk.io/snyk-api/snyk-apps)
- **Base URL:** `https://api.snyk.io/rest`

#### Tags

- Apps
- OAuth
- Extensibility
- REST API

#### Properties

- [Documentation](https://docs.snyk.io/snyk-api/snyk-apps)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snyk V1 API (Legacy)

The original Snyk REST API. Still in use for project import, monitor, test, and certain reporting endpoints not yet ported to the dated REST API. Subject to end-of-life migration; new integrations should prefer the REST API where coverage exists.

- **Human URL:** [https://snyk.docs.apiary.io/](https://snyk.docs.apiary.io/)
- **Base URL:** `https://api.snyk.io/v1`

#### Tags

- V1
- Legacy
- Test
- Monitor

#### Properties

- [Documentation](https://snyk.docs.apiary.io/)
- [Postman Collection](collections/snyk-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snyk-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/snyk)
- [LinkedIn](https://www.linkedin.com/company/snyk)
- [Website](https://snyk.io/)
- [Documentation](https://docs.snyk.io/snyk-api)
- [API Reference](https://apidocs.snyk.io/)
- [Plans](plans/snyk-plans-pricing.yml)
- [Rate Limits](rate-limits/snyk-rate-limits.yml)
- [Fin Ops](finops/snyk-finops.yml)
- [Integrations](https://snyk.io/integrations/)
- [L L Ms Txt](https://docs.snyk.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
