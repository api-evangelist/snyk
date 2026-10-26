# Snyk (snyk)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
