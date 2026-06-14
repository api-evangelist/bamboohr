# BambooHR GraphQL Schema

## Overview

BambooHR is a cloud-based human resources software platform for small and medium-sized businesses. This conceptual GraphQL schema models the BambooHR REST API surface, covering employee records, time off, compensation, benefits, applicant tracking, performance management, onboarding, payroll, and webhook configuration.

BambooHR does not currently offer a native GraphQL endpoint. This schema is a conceptual representation derived from the BambooHR REST API documentation at https://documentation.bamboohr.com/reference/ and is intended for reference, integration planning, and tooling purposes.

## Source

- REST API Reference: https://documentation.bamboohr.com/reference/
- Developer Documentation: https://documentation.bamboohr.com/docs
- Developer Portal: https://developers.bamboohr.com/
- GitHub Organization: https://github.com/BambooHR

## Authentication

BambooHR supports two authentication mechanisms:

- **API Key (HTTP Basic Auth)**: Per-customer API keys sent as the username with any password over HTTPS Basic Auth. Suitable for single-customer integrations.
- **OAuth 2.0**: Authorization code flow for multi-customer applications accessing data across multiple BambooHR accounts.

## Schema Design Notes

The schema covers the following functional areas:

### Core HR
`Employee`, `EmployeeField`, `CustomField`, `EmploymentStatus`, `Department`, `Location`, `Division`, `Company`, `SubCompany`, `EEO`, `EmergencyContact`

### Job and Compensation
`Job`, `JobInfo`, `Compensation`, `CompensationHistory`, `EarningCode`, `PaystubDetails`, `Payroll`

### Time Off
`TimeOff`, `TimeOffRequest`, `TimeOffType`, `TimeOffBalance`, `Accrual`, `TimeOffPolicy`

### Benefits
`Benefit`, `BenefitPlan`, `BenefitGroup`, `BenefitEnrollment`

### Training
`Training`, `TrainingRecord`, `TrainingCategory`, `TrainingContent`

### Performance Management
`Performance`, `PerformanceReview`, `Goal`

### Applicant Tracking
`Applicant`, `Application`, `ApplicationStatus`, `JobOpening`, `Hiring`

### Surveys
`SurveyQuestion`, `SurveyAnswer`

### Assets and Documents
`Asset`, `AssetType`, `Document`, `DocumentCategory`

### Calendar
`Calendar`, `Holiday`, `HolidayList`

### Reports
`Report`, `ReportField`

### Onboarding and Offboarding
`OnboardingTask`, `OnboardingPacket`, `OffboardingTask`

### Webhooks and API Management
`Webhook`, `WebhookEvent`, `APIKey`

## Types Count

This schema defines 65 named GraphQL types including queries, mutations, enums, and object types.

## Usage

This schema file is located at `graphql/bamboohr-schema.graphql` and can be used with GraphQL tooling such as Apollo Studio, GraphQL Inspector, or Postman to explore the BambooHR data model, generate client code, or plan integrations against the BambooHR REST API.
