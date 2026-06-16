# Digital Public Library of America (dpla)

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
