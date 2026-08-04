# FoodData Central (fooddata)

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

USDA FoodData Central is a comprehensive food composition database and REST API providing nutritional data for over 600,000 foods. The service covers multiple distinct data types including Foundation Foods, SR Legacy, Survey Foods (FNDDS), Branded Foods, and Experimental Foods. All data is released under CC0 1.0 Universal (public domain) and the API is free to use with a data.gov API key. FoodData Central is operated by the USDA Agricultural Research Service (ARS) and receives twice-annual updates for Foundation Foods and monthly updates for Branded Foods.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fooddata/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fooddata/refs/heads/main/apis.yml)

## Tags

- Food
- Nutrition
- USDA
- Government
- Health
- Diet
- Nutrients
- Public Domain

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### FoodData Central API

REST API providing access to nutrient composition data for 600,000+ foods across Foundation Foods, SR Legacy, Survey Foods (FNDDS), Branded Foods, and Experimental Foods databases. Supports individual food lookup by FDC ID, batch retrieval of up to 20 foods, paginated food listing with filtering and sorting, and keyword search with brand filtering. Authentication requires a free data.gov API key. Standard rate limit is 1,000 requests per hour per IP address.

- **Human URL:** [https://fdc.nal.usda.gov/api-guide](https://fdc.nal.usda.gov/api-guide)
- **Base URL:** `https://api.nal.usda.gov/fdc/v1`

#### Tags

- Nutrition
- Food
- Nutrients
- Diet
- Branded Foods
- Foundation Foods
- FNDDS

#### Properties

- [Documentation](https://fdc.nal.usda.gov/api-guide)
- [OpenAPI](https://api.nal.usda.gov/fdc/v1/json-spec?api_key=DEMO_KEY) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://api.nal.usda.gov/fdc/v1/yaml-spec?api_key=DEMO_KEY) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Signup](https://fdc.nal.usda.gov/api-key-signup)

## Common Properties

- [Website](https://fdc.nal.usda.gov/)
- [Documentation](https://fdc.nal.usda.gov/api-guide)
- [Portal](https://fdc.nal.usda.gov/)
- [Signup](https://fdc.nal.usda.gov/api-key-signup)
- [About](https://fdc.nal.usda.gov/about-us)
- [Contact](https://fdc.nal.usda.gov/contact)
- [F A Q](https://fdc.nal.usda.gov/faq)
- [Data Download](https://fdc.nal.usda.gov/download-datasets)
- [Changelog](https://fdc.nal.usda.gov/log)
- [X (Twitter)](https://twitter.com/usda_ars)
- [Plans](plans/fooddata-plans-pricing.yml)
- [Rate Limits](rate-limits/fooddata-rate-limits.yml)
- [Fin Ops](finops/fooddata-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
