# Amazon WorkSpaces (amazon-workspaces)

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

Amazon WorkSpaces is a managed, secure Desktop-as-a-Service (DaaS) solution that enables you to provision cloud-based virtual desktops for your users. It eliminates the need to procure and deploy hardware or install complex software, providing persistent desktops accessible from various devices with built-in security and management capabilities. The API provides 65 operations for workspace lifecycle management, bundle and directory management, image management, and IP access control groups.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Desktop, Desktop as a Service, End User Computing, Virtual Desktop

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon WorkSpaces API
The Amazon WorkSpaces API provides programmatic access to manage cloud-based virtual desktops. It enables developers to create, modify, and terminate WorkSpaces, manage workspace bundles and directories, configure IP access control groups, and automate desktop provisioning and lifecycle management at scale. 65 operations for workspace lifecycle, bundles, directories, images, and access control.

**Human URL:** [https://aws.amazon.com/workspaces/](https://aws.amazon.com/workspaces/)

#### Tags:

 - AWS, Desktop, End User Computing, Virtual Desktop

#### Properties

- [Documentation](https://docs.aws.amazon.com/workspaces/)
- [OpenAPI](openapi/amazon-workspaces-openapi-original.yaml)
- [Pricing](https://aws.amazon.com/workspaces/pricing/)
- [GettingStarted](https://aws.amazon.com/workspaces/getting-started/)
- [FAQ](https://aws.amazon.com/workspaces/faqs/)
- [APIReference](https://docs.aws.amazon.com/workspaces/latest/api/welcome.html)
- [JSONSchema](json-schema/workspaces-workspace-schema.json)
- [JSONLD](json-ld/amazon-workspaces-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/workspaces/)
- [Documentation](https://docs.aws.amazon.com/workspaces/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/workspaces/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Persistent Virtual Desktops | Cloud-based Windows or Linux desktops with persistent storage accessible from any device or location. |
| Desktop Bundle Catalog | Configurable compute bundles from Value to Graphics.g4dn to match workload requirements and cost targets. |
| Active Directory Integration | Integration with AWS Managed Microsoft AD and AD Connector for user authentication and policy management. |
| Application Management | Deploy and manage applications across WorkSpaces using application assignment and streaming capabilities. |
| IP Access Control Groups | Restrict workspace access by IP address ranges to enforce network-based access controls. |
| Running Mode Flexibility | AlwaysOn mode for power users and AutoStop mode for cost optimization of occasional-use desktops. |
| BYOD Support | Thin client, web browser, iOS, Android, Linux, macOS, and Windows client access for bring-your-own-device scenarios. |
| Workspace Snapshots and Restore | Automated snapshots enable restoring workspaces to previous states for disaster recovery and user error correction. |

## Use Cases

| Name | Description |
|------|-------------|
| Remote Work Enablement | Provide secure cloud desktops to remote and distributed employees without managing physical hardware. |
| Contractor and Temporary Worker Access | Quickly provision and terminate secure desktops for contractors with time-limited access needs. |
| Desktop Refresh and Modernization | Replace aging desktop hardware with cloud-based virtual desktops to reduce capital expenditure. |
| BYOD Security | Enable personal device usage while keeping corporate data and applications in the secure cloud environment. |
| Regulated Industry Compliance | Maintain data residency and security compliance in regulated industries like healthcare and finance. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Directory Service | Managed Microsoft AD and AD Connector for user authentication and group policy management. |
| AWS IAM | IAM-based access control for WorkSpaces API operations and resource-level permissions. |
| Amazon S3 | User storage and workspace image storage backed by Amazon S3. |
| AWS CloudTrail | Audit logging of all WorkSpaces API calls for compliance and security monitoring. |
| Amazon CloudWatch | Metrics and monitoring for workspace performance, connectivity, and health status. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon WorkSpaces OpenAPI](openapi/amazon-workspaces-openapi-original.yaml)

### JSON Schema

336 JSON Schema files extracted from the OpenAPI specification.

### JSON Structure

336 JSON Structure files converted from JSON Schema definitions.

### JSON-LD

- [Amazon WorkSpaces Context](json-ld/amazon-workspaces-context.jsonld)

### Examples

145 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon WorkSpaces API](capabilities/shared/workspaces.yaml) — 7 operations for workspace lifecycle, bundle, directory, and image management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Virtual Desktop Management](capabilities/virtual-desktop-management.yaml) | Amazon WorkSpaces | 7 | IT Administrator, End User Computing Engineer |

## Vocabulary

- [Amazon WorkSpaces Vocabulary](vocabulary/amazon-workspaces-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon WorkSpaces Spectral Rules](rules/amazon-workspaces-spectral-rules.yml) — 16 rules across 8 categories enforcing Amazon WorkSpaces API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
