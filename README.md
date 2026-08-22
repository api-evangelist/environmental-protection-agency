# Environmental Protection Agency (environmental-protection-agency)

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

The U.S. Environmental Protection Agency (EPA) provides multiple public data APIs covering environmental records, air quality monitoring, UV forecasts, and internal data holdings. These services enable State and local governments, federal agencies, researchers, and the public to access environmental data about air, water, and land.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/environmental-protection-agency/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/environmental-protection-agency/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Environment
- Federal Government
- Air Quality
- Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-28

## APIs

### EPA Envirofacts Data Service API

Envirofacts provides a single point of access to U.S. EPA environmental data contained in U.S. EPA databases. The RESTful Data Service API returns output in JSON, CSV, Excel, HTML, JSONP, Parquet, PDF, or XML formats and supports queries across any Envirofacts table.

- **Human URL:** [https://www.epa.gov/enviro/envirofacts-data-service-api](https://www.epa.gov/enviro/envirofacts-data-service-api)
- **Base URL:** `https://data.epa.gov/efservice/`

#### Tags

- Environment
- Open Data

#### Properties

- [Documentation](https://www.epa.gov/enviro/envirofacts-data-service-api)
- [Web  Services](https://www.epa.gov/enviro/web-services)
- [Postman Collection](collections/environmental-protection-agency.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/environmental-protection-agency.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EPA Air Quality System API

The EPA Air Quality System (AQS) API provides programmatic access to ambient air pollution data collected by the EPA, state, local, and tribal air pollution control agencies, including hourly sample data, daily/quarterly/annual summaries, monitor information, and quality assurance data. JSON response format with API key authentication.

- **Human URL:** [https://aqs.epa.gov/aqsweb/documents/data_api.html](https://aqs.epa.gov/aqsweb/documents/data_api.html)
- **Base URL:** `https://aqs.epa.gov/data/api`

#### Tags

- Environment
- Air Quality

#### Properties

- [Documentation](https://aqs.epa.gov/aqsweb/documents/data_api.html)
- [Sign Up](https://aqs.epa.gov/data/api/signup)
- [Postman Collection](collections/environmental-protection-agency.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/environmental-protection-agency.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EPA UV Index API

The EPA UV Index API provides hourly and daily ultraviolet radiation forecasts by ZIP code or city/state. Output is available in XML, JSON, Excel, and CSV formats.

- **Human URL:** [https://www.epa.gov/enviro/web-services](https://www.epa.gov/enviro/web-services)
- **Base URL:** `https://data.epa.gov/efservice/getEnvirofactsUVHOURLY/`

#### Tags

- Environment
- UV Index

#### Properties

- [Documentation](https://www.epa.gov/enviro/web-services)
- [Postman Collection](collections/environmental-protection-agency.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/environmental-protection-agency.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EPA ECHO Compliance and Enforcement API

Enforcement and Compliance History Online (ECHO) provides public access to compliance and enforcement information for EPA-regulated facilities nationwide. The ECHO web services API supports facility searches, compliance reports, and enforcement case lookups.

- **Human URL:** [https://echo.epa.gov/tools/web-services](https://echo.epa.gov/tools/web-services)
- **Base URL:** `https://echodata.epa.gov/echo/`

#### Tags

- Environment
- Compliance
- Enforcement

#### Properties

- [Documentation](https://echo.epa.gov/tools/web-services)
- [Postman Collection](collections/environmental-protection-agency.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/environmental-protection-agency.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/usepa)
- [LinkedIn](https://www.linkedin.com/company/us-epa)
- [Website](https://www.epa.gov/)
- [Developer  Central](https://www.epa.gov/developers)
- [Web  Services](https://www.epa.gov/enviro/web-services)
- [Open  Data](https://www.data.gov/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
