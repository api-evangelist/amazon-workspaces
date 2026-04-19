# Amazon WorkSpaces (amazon-workspaces)
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
