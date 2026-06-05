# BambooHR (bamboohr)

BambooHR is a cloud-based human resources software platform for small and medium-sized businesses, providing core HR, applicant tracking, onboarding, time tracking, payroll, performance management, and employee self-service. The BambooHR REST API allows developers to read and update employee data, generate reports, manage time-off, and integrate with the HRIS using either OAuth 2.0 or per-customer API keys over HTTPS Basic Auth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bamboohr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bamboohr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- HR
- HRIS
- Human Resources
- Payroll
- Time Tracking
- Applicant Tracking
- Performance Management

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### BambooHR REST API

RESTful HTTPS API for accessing and manipulating employee data, directories, time-off, reports, and other BambooHR HRIS resources. Supports OAuth 2.0 for multi-customer apps and API key (HTTP Basic) for single-customer integrations.

- **Human URL:** [https://documentation.bamboohr.com/docs](https://documentation.bamboohr.com/docs)
- **Base URL:** `https://api.bamboohr.com/api/gateway.php`

#### Tags

- HR
- Employees
- Time Off
- Reports
- Directory

#### Properties

- [Documentation](https://documentation.bamboohr.com/docs)
- [API Reference](https://documentation.bamboohr.com/reference)
- [Getting Started](https://documentation.bamboohr.com/docs/getting-started)
- [Authentication](https://documentation.bamboohr.com/docs/getting-started)
- [S D Ks](https://documentation.bamboohr.com/docs/sdks)
- [Postman Collection](collections/bamboohr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bamboohr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BambooHR Webhooks

Event-driven webhook surface for BambooHR. Webhooks fire when monitored fields change on Employee records (and when employee records are created or deleted). Subscribers register an HTTPS URL per monitored field; BambooHR POSTs an event-based or field-based JSON payload carrying the employee identifier and the list of changed fields, signed with an SHA-256 HMAC.

- **Human URL:** [https://documentation.bamboohr.com/docs/webhooks](https://documentation.bamboohr.com/docs/webhooks)

#### Tags

- Webhooks
- Events
- Employees
- HRIS

#### Properties

- [Documentation](https://documentation.bamboohr.com/docs/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/bamboohr/refs/heads/main/openapi/bamboohr-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Documentation](https://documentation.bamboohr.com/docs/event-based-webhooks)
- [Documentation](https://documentation.bamboohr.com/docs/field-based-webhooks)
- [Documentation](https://documentation.bamboohr.com/docs/global-webhooks)
- [Documentation](https://documentation.bamboohr.com/docs/permissioned-webhooks)
- [Postman Collection](collections/bamboohr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bamboohr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/BambooHR)
- [LinkedIn](https://www.linkedin.com/company/bamboohr)
- [Website](https://www.bamboohr.com/)
- [Documentation](https://documentation.bamboohr.com/docs)
- [Developer  Portal](https://developers.bamboohr.com/)
- [API Reference](https://documentation.bamboohr.com/reference)
- [Sign Up](https://www.bamboohr.com/signup/)
- [Pricing](https://www.bamboohr.com/pricing/)
- [Support](https://help.bamboohr.com/)
- [L L Ms Txt](https://developers.bamboohr.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
