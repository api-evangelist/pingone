# PingOne (pingone)

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

PingOne is Ping Identity's cloud-based identity and access management platform providing authentication, authorization, single sign-on, MFA, identity verification, risk evaluation, and user lifecycle management for workforce and customer identities. The platform unifies Ping Identity capabilities into a multi-region cloud service across the US, EU, Canada, and Asia-Pacific. PingOne exposes a comprehensive REST Platform API secured with OAuth 2.0 access tokens issued by its authentication service.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pingone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pingone/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Identity
- Authentication
- Authorization
- Single Sign-On
- Multi-Factor Authentication
- IAM
- CIAM

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### PingOne Platform API

REST API for managing PingOne environments, users, populations, applications, identity providers, MFA, risk policies, and authentication flows. Authentication uses OAuth 2.0 access tokens obtained from auth.pingone.com; the platform API base endpoint is api.pingone.com.

- **Human URL:** [https://apidocs.pingidentity.com/pingone/main/v1/api/](https://apidocs.pingidentity.com/pingone/main/v1/api/)
- **Base URL:** `https://api.pingone.com`

#### Tags

- Identity
- Authentication
- IAM
- OAuth 2.0
- REST

#### Properties

- [Documentation](https://apidocs.pingidentity.com/pingone/main/v1/api/)
- [Postman  Collection](https://www.postman.com/ping-identity/pingone/collection/xu0baxr/pingone-platform-api)
- [Authentication](https://auth.pingone.com)
- [Postman Collection](collections/pingone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pingone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PingOne Advanced Identity Cloud API

REST API for the PingOne Advanced Identity Cloud tenant providing identity management, access management, and tenant operations. Supports two authentication methods - API key and secret for read-only tenant operations, and OAuth 2.0 access tokens for access management, identity management, and tenant write operations.

- **Human URL:** [https://developer.pingidentity.com/pingoneaic-api/_attachments/api/index.html](https://developer.pingidentity.com/pingoneaic-api/_attachments/api/index.html)
- **Base URL:** `https://openam.example.com`

#### Tags

- Identity
- Access Management
- IAM
- REST

#### Properties

- [Documentation](https://developer.pingidentity.com/pingoneaic-api/_attachments/api/index.html)
- [A P I  Docs](https://apidocs.id.forgerock.io/)
- [Postman Collection](collections/pingone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pingone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pingidentity)
- [LinkedIn](https://www.linkedin.com/company/ping-identity)
- [Website](https://www.pingidentity.com)
- [Documentation](https://docs.pingidentity.com/pingone/)
- [Developer  Portal](https://apidocs.pingidentity.com/pingone/main/v1/api/)
- [Pricing](https://www.pingidentity.com/en/platform/pricing.html)
- [Sign Up](https://www.pingidentity.com/en/try-ping.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
