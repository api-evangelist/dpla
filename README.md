# Digital Public Library of America (dpla)

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

The Digital Public Library of America (DPLA) provides a free REST API that gives access to metadata for 50 million+ cultural heritage items aggregated from 4,000+ US libraries, archives, and museums. The API supports full-text search, field-specific queries, geographic and date range filtering, faceted browsing, and JSONP callbacks. All results are returned as JSON-LD. API keys are issued free of charge via a self-service email-based registration endpoint. DPLA aggregates contributions from cultural heritage institutions across the United States and makes the combined metadata freely available to researchers, developers, and the public.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Cultural Heritage
- Libraries
- Archives
- Museums
- Open Data
- Metadata
- Digital Collections
- Public Domain

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### DPLA Items API

The DPLA Items API provides search and retrieval of metadata records for cultural heritage objects aggregated from 4,000+ US institutions. Supports full-text search, field-level queries, boolean and wildcard operators, geographic distance queries, date range filtering, and faceted aggregations. Returns JSON-LD records containing title, creator, date, subject, rights, provider, and thumbnail information. Pagination supports up to 100 results per page and batch retrieval of up to 50 items by ID in a single request.

- **Human URL:** [https://pro.dp.la/developers/api-codex](https://pro.dp.la/developers/api-codex)
- **Base URL:** `https://api.dp.la/v2`

#### Tags

- Items
- Search
- Metadata
- Cultural Heritage
- Libraries
- Archives
- Museums
- JSON-LD

#### Properties

- [Documentation](https://pro.dp.la/developers/api-codex)
- [Getting Started](https://pro.dp.la/developers/api-codex)
- [Authentication](https://pro.dp.la/developers/api-codex)
- [GitHub Repository](https://github.com/dpla/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### DPLA API Key Registration

Self-service API key registration endpoint that issues free access keys via email. Developers submit their email address via HTTP POST and receive an API key by email. The key is then passed as the api_key query parameter or Authorization header on all subsequent Items API requests.

- **Human URL:** [https://pro.dp.la/developers/api-codex](https://pro.dp.la/developers/api-codex)
- **Base URL:** `https://api.dp.la/v2`

#### Tags

- Authentication
- API Keys
- Registration

#### Properties

- [Documentation](https://pro.dp.la/developers/api-codex)

## Common Properties

- [Website](https://dp.la/)
- [Developer Portal](https://pro.dp.la/developers)
- [Documentation](https://pro.dp.la/developers/api-codex)
- [GitHub Organization](https://github.com/dpla)
- [GitHub Repository](https://github.com/dpla/api)
- [Blog](https://dp.la/news)
- [LinkedIn](https://www.linkedin.com/company/digital-public-library-of-america)
- [Twitter](https://twitter.com/dpla)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/rate-limits/rate-limits.yml)
- [Plans](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/plans/plans.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/finops/finops.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/dpla/refs/heads/main/json-ld/context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
