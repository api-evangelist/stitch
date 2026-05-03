# Stitch

Stitch is an open banking and payments API platform providing unified access to financial data and payment rails across banks and financial institutions in Africa, primarily South Africa and Nigeria. Stitch enables businesses to accept payments via multiple channels, access bank account data, and issue disbursements through a single GraphQL API.

**URL:** [https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Africa
- Financial Data
- Open Banking
- Payments
- Unified API
- South Africa
- Nigeria

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## APIs

### Stitch GraphQL API

GraphQL API at api.stitch.money/graphql following Relay Server Specification. Supports payments, bank account data, and disbursements. OAuth 2.0 client credentials authentication.

**Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Payment Products (Pay-ins)

- Pay By Bank
- Capitec Pay
- Card Payments
- DebiCheck
- Manual EFT
- Cash Payments
- Crypto Payments

#### Payment Products (Pay-outs)

- Disbursements

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [stitch-openapi.yml](openapi/stitch-openapi.yml) | Stitch API — GraphQL endpoint and OAuth token flow |

## Capabilities

### Workflow Capabilities

| Capability | Tools | Description |
|---|---|---|
| [open-banking-payments.yaml](capabilities/open-banking-payments.yaml) | 5 | Unified African open banking — payments, account data, and disbursements |

### Shared Definitions

| Definition | Description |
|---|---|
| [shared/stitch.yaml](capabilities/shared/stitch.yaml) | Stitch GraphQL API consumed definition with 5 operations |

## Rules

| Ruleset | Description |
|---|---|
| [stitch-rules.yml](rules/stitch-rules.yml) | Spectral ruleset enforcing Stitch API conventions |

## JSON Schema

| Schema | Description |
|---|---|
| [stitch-payment-schema.json](json-schema/stitch-payment-schema.json) | Payment initiation request schema |
| [stitch-bank-account-schema.json](json-schema/stitch-bank-account-schema.json) | Linked bank account schema |

## JSON Structure

| Structure | Description |
|---|---|
| [stitch-payment-structure.json](json-structure/stitch-payment-structure.json) | Payment initiation response structure |

## JSON-LD

| Context | Description |
|---|---|
| [stitch-context.jsonld](json-ld/stitch-context.jsonld) | JSON-LD context mapping Stitch vocabulary to schema.org |

## Examples

| Example | Description |
|---|---|
| [stitch-initiate-payment-example.json](examples/stitch-initiate-payment-example.json) | Initiate a ZAR 250 Pay By Bank payment |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [stitch-vocabulary.yml](vocabulary/stitch-vocabulary.yml) | Domain vocabulary for African open banking and payments |

## GitHub Organization

- [github.com/stitch-money](https://github.com/stitch-money) — GraphQL tooling, financial message parsers, and integration examples

## Common Properties

- [Website](https://stitch.money/)
- [Documentation](https://docs.stitch.money/)
- [GitHub Organization](https://github.com/stitch-money)
- [Sign Up](https://stitch.money/contact)
- [Status](https://status.stitch.money/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
