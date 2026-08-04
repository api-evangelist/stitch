# Stitch (stitch)

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

Stitch is an open banking and payments API platform providing unified access to financial data and payment rails across banks and financial institutions in Africa, primarily South Africa and Nigeria. Stitch enables businesses to accept payments via multiple channels, access bank account data, and issue disbursements through a single GraphQL API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-19

## APIs

### Stitch GraphQL API

The core Stitch API using GraphQL, available at api.stitch.money/graphql. Follows the Relay Server Specification for pagination. Supports all Stitch products including pay-ins, payouts, bank account data, and payments. Authentication uses OAuth 2.0 client credentials.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- GraphQL
- Open Banking
- Payments

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Graph Q L](https://api.stitch.money/graphql)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/stitch/refs/heads/main/openapi/stitch-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch Pay By Bank

Stitch Pay By Bank enables merchants to accept instant bank transfer payments directly from customers' bank accounts in South Africa and Nigeria.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payments
- Bank Transfer
- Pay-ins

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch Capitec Pay

Stitch integration with Capitec Bank's Capitec Pay payment method, enabling customers to pay via Capitec mobile banking.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payments
- Capitec
- South Africa

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch Card Payments

Stitch card payment processing enabling businesses to accept debit and credit card payments through the Stitch unified platform.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payments
- Card Payments
- Pay-ins

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch DebiCheck

Stitch DebiCheck integration providing authenticated debit orders for recurring payment collection in South Africa.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payments
- DebiCheck
- Recurring Payments
- South Africa

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch Manual EFT

Stitch Manual EFT (Electronic Funds Transfer) enabling customers to pay via standard bank EFT with Stitch's streamlined reference management.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payments
- EFT
- Bank Transfer

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stitch Disbursements

Stitch Disbursements (Payouts) API enabling businesses to programmatically send funds to bank accounts, enabling mass payments, refunds, and marketplace disbursements.

- **Human URL:** [https://docs.stitch.money/](https://docs.stitch.money/)

#### Tags

- Payouts
- Disbursements
- Bank Transfer

#### Properties

- [Documentation](https://docs.stitch.money/)
- [Postman Collection](collections/stitch.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stitch.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/stitchdata)
- [Website](https://stitch.money/)
- [Documentation](https://docs.stitch.money/)
- [GitHub Organization](https://github.com/stitch-money)
- [Sign Up](https://stitch.money/contact)
- [Status Page](https://status.stitch.money/)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
