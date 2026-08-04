# Microsoft Intune (microsoft-intune)

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

Microsoft Intune is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). It helps organizations control how their devices are used, including mobile phones, tablets, and laptops, and enables management of apps on those devices.

**APIs.json:** [https://www.microsoft.com/en-us/security/business/microsoft-intune](https://www.microsoft.com/en-us/security/business/microsoft-intune)

## Tags

- App Protection
- Azure
- Compliance
- Device Configuration
- Endpoint Management
- Enrollment
- MAM
- MDM
- Microsoft Graph
- Mobile Application Management
- Mobile Device Management
- Security

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Microsoft Intune API

The Microsoft Graph API for Intune enables programmatic access to Intune information and actions for your tenant. The API performs the same Intune operations as those available through the Azure Portal.

- **Human URL:** [https://docs.microsoft.com/en-us/graph/api/resources/intune-graph-overview](https://docs.microsoft.com/en-us/graph/api/resources/intune-graph-overview)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Applications
- Compliance
- Devices
- Groups
- Policies
- Users

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/graph/api/resources/intune-graph-overview)
- [X-openapi](https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml)
- [X-openapi-intune](openapi/microsoft-intune-openapi.yml)
- [X-json-schema-managed-device](json-schema/microsoft-intune-managed-device-schema.json)
- [X-json-ld-context](json-ld/microsoft-intune-context.jsonld)
- [X-authentication](https://docs.microsoft.com/en-us/graph/auth/)
- [X-postman-collection](https://www.postman.com/microsoftgraph/workspace/microsoft-graph/overview)
- [X-rate-limits](https://docs.microsoft.com/en-us/graph/throttling)
- [X-change-log](https://docs.microsoft.com/en-us/graph/changelog)
- [X-sdks](https://docs.microsoft.com/en-us/graph/sdks/sdks-overview)
- [X-pricing](https://www.microsoft.com/en-us/security/business/microsoft-intune-pricing)
- [X-getting-started](https://learn.microsoft.com/en-us/graph/intune-concept-overview)
- [X-permissions](https://learn.microsoft.com/en-us/graph/permissions-reference)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Data Warehouse API

The Intune Data Warehouse API provides access to your Intune data in a machine-readable format for use in your favorite analytics tool. You can use the API to generate reports that provide insight into your mobile environment.

- **Human URL:** [https://docs.microsoft.com/en-us/mem/intune/developer/reports-nav-create-intune-reports](https://docs.microsoft.com/en-us/mem/intune/developer/reports-nav-create-intune-reports)
- **Base URL:** `https://api.manage.microsoft.com/`

#### Tags

- Analytics
- Data Warehouse
- Odata
- Reporting

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/mem/intune/developer/reports-nav-intune-data-warehouse)
- [X-authentication](https://docs.microsoft.com/en-us/mem/intune/developer/reports-proc-data-rest)
- [X-data-model](https://docs.microsoft.com/en-us/mem/intune/developer/reports-ref-data-model)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Device Management API

The Microsoft Graph Device Management API enables programmatic management of devices enrolled in Intune, including listing managed devices, performing remote actions such as wipe and retire, and retrieving device compliance state and configuration status.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement`

#### Tags

- Device Compliance
- Devices
- Managed Devices
- Remote Actions

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0)
- [X-openapi](openapi/microsoft-intune-openapi.yml)
- [X-json-schema](json-schema/microsoft-intune-managed-device-schema.json)
- [X-json-ld-context](json-ld/microsoft-intune-context.jsonld)
- [X-list-endpoint](https://learn.microsoft.com/en-us/graph/api/intune-devices-manageddevice-list?view=graph-rest-1.0)
- [X-getting-started](https://learn.microsoft.com/en-us/graph/intune-concept-overview)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Device Configuration API

The Microsoft Graph Device Configuration API allows you to define and deploy device configuration policies across enrolled devices, including operating system platform and versioning, domain membership, and configuration setting management through configuration service providers (CSPs).

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-deviceconfiguration?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-deviceconfiguration?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement/deviceConfigurations`

#### Tags

- CSP
- Device Configuration
- Policies
- Settings

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-deviceconfiguration?view=graph-rest-1.0)
- [X-openapi](openapi/microsoft-intune-openapi.yml)
- [X-json-ld-context](json-ld/microsoft-intune-context.jsonld)
- [X-graph-apis](https://learn.microsoft.com/en-us/intune/intune-service/developer/graph-apis-used-by-intune-device-configuration-windows)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Device Compliance API

The Microsoft Graph Device Compliance API enables you to define and enforce device compliance policies, such as password complexity, encryption, and threat protection levels, and retrieve compliance state for managed devices.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-devicecompliancepolicy?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-devicecompliancepolicy?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement/deviceCompliancePolicies`

#### Tags

- Compliance
- Device Compliance
- Policies
- Security

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-devicecompliancepolicy?view=graph-rest-1.0)
- [X-openapi](openapi/microsoft-intune-openapi.yml)
- [X-json-ld-context](json-ld/microsoft-intune-context.jsonld)
- [X-overview](https://learn.microsoft.com/en-us/intune/intune-service/protect/device-compliance-get-started)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Device Enrollment API

The Microsoft Graph Device Enrollment API enables you to enroll organization-owned or corporate-owned devices for management with Intune, supporting various enrollment methods depending on device type and organizational needs.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-enrollment-conceptual?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/intune-enrollment-conceptual?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement`

#### Tags

- Corporate Devices
- Enrollment
- Onboarding

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-enrollment-conceptual?view=graph-rest-1.0)
- [X-onboarding](https://learn.microsoft.com/en-us/graph/api/resources/intune-onboarding-conceptual?view=graph-rest-1.0)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Mobile App Management API

The Microsoft Graph Mobile App Management (MAM) API enables you to manage app protection policies, deploy apps to devices, configure app settings, and manage app usage policies to protect organizational data within mobile applications.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-mam-conceptual?view=graph-rest-beta](https://learn.microsoft.com/en-us/graph/api/resources/intune-mam-conceptual?view=graph-rest-beta)
- **Base URL:** `https://graph.microsoft.com/beta/deviceAppManagement`

#### Tags

- App Protection
- Applications
- MAM
- Mobile App Management

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-mam-conceptual?view=graph-rest-beta)
- [X-app-protection-overview](https://learn.microsoft.com/en-us/intune/intune-service/apps/app-protection-policy)
- [X-app-configuration](https://learn.microsoft.com/en-us/intune/intune-service/apps/app-configuration-policies-overview)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Reports Export API

The Intune Reports Export API enables you to export Intune reporting data using Microsoft Graph API export jobs. You can create export jobs to generate reports that provide insight into device compliance, app usage, and other aspects of your managed environment.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement/reports`

#### Tags

- Analytics
- Compliance Reports
- Export
- Reports

#### Properties

- [X-documentation](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis)
- [X-available-reports](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-available-reports)
- [X-create-export-job](https://learn.microsoft.com/en-us/graph/api/intune-reporting-devicemanagementexportjob-create?view=graph-rest-1.0)
- [Postman Collection](collections/microsoft-intune.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-intune.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/microsoft-intune-product)
- [X-portal](https://endpoint.microsoft.com/)
- [X-blog](https://techcommunity.microsoft.com/t5/microsoft-intune-blog/bg-p/MicrosoftEndpointManagerBlog)
- [X-learning](https://docs.microsoft.com/en-us/learn/browse/?products=m365%2Cmem)
- [X-privacy](https://privacy.microsoft.com/)
- [X-terms-of-service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [X-status](https://status.azure.com/)
- [X-github](https://github.com/microsoftgraph)
- [X-github-samples](https://github.com/microsoft/mggraph-intune-samples)
- [X-powershell-samples](https://github.com/microsoftgraph/powershell-intune-samples)
- [X-developer-documentation](https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis)
- [X-sdk](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk)
- [X-sdk-getting-started](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started)
- [X-app-wrapping-tool](https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management)
- [X-community](https://techcommunity.microsoft.com/t5/microsoft-intune/ct-p/MicrosoftIntune)
- [X-support](https://learn.microsoft.com/en-us/mem/get-support)
- [X-twitter](https://twitter.com/MSIntune)
- [X-whatsnew](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
