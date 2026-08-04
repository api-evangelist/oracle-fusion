# Oracle Fusion Cloud Applications (oracle-fusion)

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

Oracle Fusion Cloud Applications represent a comprehensive suite of cloud-based enterprise resource planning (ERP), human capital management (HCM), customer experience (CX), supply chain management (SCM), and enterprise performance management (EPM) solutions. Oracle Fusion Cloud provides REST APIs across all application pillars, enabling programmatic access to business data and processes for integration, automation, and extension of cloud applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud
- CX
- Enterprise
- EPM
- ERP
- HCM
- Project Management
- REST API
- SaaS
- SCM

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Oracle Fusion ERP REST API

REST APIs for Oracle Fusion Cloud ERP, providing programmatic access to financials, procurement, project management, and risk management capabilities. The API supports viewing and managing financial data including general ledger, accounts payable, accounts receivable, fixed assets, and cash management.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/financials/](https://docs.oracle.com/en/cloud/saas/financials/)
- **Base URL:** `https://{instance}.oraclecloud.com/fscmRestApi/`

#### Tags

- ERP
- Financials
- Procurement
- Projects
- Risk Management

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html)
- [OpenAPI](https://docs.oracle.com/en/cloud/saas/financials/22r3/farfa/api-rest-api.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/financials/22r3/farfa/Authentication.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/financials/26a/index.html)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html)
- [OpenAPI](openapi/oracle-fusion-erp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-erp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-erp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion HCM REST API

REST APIs for Oracle Fusion Cloud Human Capital Management, enabling integration with core HR, talent management, workforce management, and payroll systems. The API provides access to employee records, absence management, benefits, compensation, recruiting, and learning resources.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/human-resources/](https://docs.oracle.com/en/cloud/saas/human-resources/)
- **Base URL:** `https://{instance}.oraclecloud.com/hcmRestApi/`

#### Tags

- HCM
- Human Resources
- Payroll
- Talent Management
- Workforce

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/human-resources/22r3/farws/)
- [OpenAPI](https://docs.oracle.com/en/cloud/saas/human-resources/22r3/farws/api-rest-api.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/human-resources/22r3/farws/Authentication.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/human-resources/26a/index.html)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/hcm/index.html)
- [OpenAPI](openapi/oracle-fusion-hcm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion SCM REST API

REST APIs for Oracle Fusion Cloud Supply Chain Management, providing access to inventory, order management, procurement, logistics, and manufacturing capabilities. The API enables integration with supply chain planning, product lifecycle management, service logistics, and supply chain execution processes.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/supply-chain-management/](https://docs.oracle.com/en/cloud/saas/supply-chain-management/)
- **Base URL:** `https://{instance}.oraclecloud.com/fscmRestApi/`

#### Tags

- Inventory
- Logistics
- Manufacturing
- Order Management
- SCM
- Supply Chain

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/supply-chain-management/22r3/fasrs/)
- [OpenAPI](https://docs.oracle.com/en/cloud/saas/supply-chain-management/22r3/fasrs/api-rest-api.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/supply-chain-management/22r3/fasrs/Authentication.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/supply-chain-management/26a/index.html)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/scm/index.html)
- [OpenAPI](openapi/oracle-fusion-scm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-scm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-scm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion CX Sales and Fusion Service REST API

REST APIs for Oracle Fusion Cloud Customer Experience, enabling integration with sales force automation, fusion service, customer data management, and commerce applications. The API provides access to accounts, contacts, opportunities, leads, service requests, activities, and other CRM resources.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/sales/](https://docs.oracle.com/en/cloud/saas/sales/)
- **Base URL:** `https://{instance}.oraclecloud.com/crmRestApi/`

#### Tags

- Commerce
- Customer Experience
- CX
- Marketing
- Sales

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/sales/faaps/index.html)
- [OpenAPI](https://docs.oracle.com/en/cloud/saas/cx-sales/rest-api.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.oracle.com/en/cloud/saas/cx-sales/rest-authentication.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/sales/index.html)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/sales.html)
- [OpenAPI](openapi/oracle-fusion-cx-sales-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-cx-sales.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-cx-sales.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion Common Features REST API

REST APIs for Oracle Fusion Cloud Applications Common features, providing access to shared services such as attachments, flexfields, lookup types, roles, users, security, and approval workflows used across all Fusion Cloud application pillars. This is the foundational API that supports cross-pillar integration capabilities.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/applications-common/](https://docs.oracle.com/en/cloud/saas/applications-common/)
- **Base URL:** `https://{instance}.oraclecloud.com/fscmRestApi/`

#### Tags

- Attachments
- Common
- Flexfields
- Roles
- Security
- Users

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/applications-common/26a/farca/index.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/applications-common/26a/index.html)
- [OpenAPI](openapi/oracle-fusion-common-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-common.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-common.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion Project Management REST API

REST APIs for Oracle Fusion Cloud Project Management, enabling integration with project planning, project costing, project billing, grants management, and project execution capabilities. The API supports managing project resources, tasks, budgets, and deliverables.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/project-management/](https://docs.oracle.com/en/cloud/saas/project-management/)
- **Base URL:** `https://{instance}.oraclecloud.com/fscmRestApi/`

#### Tags

- Grants
- Project Billing
- Project Costing
- Project Management

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/project-management/26a/fapap/index.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/project-management/26a/index.html)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html)
- [OpenAPI](openapi/oracle-fusion-project-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-project-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-project-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oracle Fusion EPM REST API

REST APIs for Oracle Fusion Cloud Enterprise Performance Management, enabling integration with planning, budgeting, forecasting, financial consolidation, account reconciliation, tax reporting, and narrative reporting capabilities. The EPM REST APIs allow infrastructure consultants to integrate environments with Oracle EPM Cloud services.

- **Human URL:** [https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/](https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/)
- **Base URL:** `https://{instance}.oraclecloud.com/HyperionPlanning/rest/`

#### Tags

- Budgeting
- Consolidation
- EPM
- Financial Close
- Planning

#### Properties

- [Documentation](https://docs.oracle.com/en/cloud/saas/enterprise-performance-management-common/prest/index.html)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/epm-cloud/index.html)
- [OpenAPI](openapi/oracle-fusion-epm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oracle-fusion-epm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oracle-fusion-epm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://docs.oracle.com/en/cloud/saas/)
- [Authentication](https://docs.oracle.com/en/cloud/saas/applications-common/26a/farca/index.html)
- [Support](https://support.oracle.com)
- [Getting Started](https://docs.oracle.com/en/cloud/saas/applications-common/)
- [Status Page](https://ocistatus.oraclecloud.com/)
- [Terms of Service](https://www.oracle.com/corporate/contracts/cloud-services/)
- [Privacy Policy](https://www.oracle.com/legal/privacy/)
- [Changelog](https://docs.oracle.com/en/cloud/saas/readiness/fusion-readiness/)
- [Website](https://www.oracle.com/applications/)
- [Sign Up](https://www.oracle.com/cloud/free/)
- [Login](https://cloud.oracle.com/)
- [GitHub Organization](https://github.com/oracle)
- [JSON-LD](json-ld/oracle-fusion-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/oracle-fusion-invoice-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-fusion-worker-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-fusion-sales-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/oracle-fusion-account-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
