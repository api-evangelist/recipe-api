# Recipe API (recipe-api)

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

Recipe API is a B2B recipe and nutrition API providing structured recipes with comprehensive, USDA-backed nutrition data — 32 nutrients per recipe, structured preparation steps, and per-100g nutrition on individual ingredients. Beyond browsing and filtering an existing catalog by category, cuisine, dietary flag and macro, it will generate a new recipe with nutrition on demand, and generate food photography from a recipe. It positions itself as a lighter-weight alternative for developers who want clean recipe data without much setup, and publishes both an llms.txt and an official MCP server so that AI clients can use it directly. Self-serve from a free evaluation tier through to a paid scale tier, with a documented keyless quick-start call so a developer can try the API before signing up.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/recipe-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/recipe-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Recipes
- Food
- Nutrition
- Ingredients
- Data
- Generative AI
- MCP
- Agents

## Timestamps

- **Created:** 2026-08-03
- **Modified:** 2026-08-03

## APIs

### Recipe API Discovery API

Requires API key. No credit cost. Browse categories, cuisines, and dietary options.

- **Human URL:** [https://recipe-api.com/docs](https://recipe-api.com/docs)
- **Base URL:** `https://recipe-api.com`

#### Tags

- Discovery

#### Properties

- [OpenAPI](openapi/recipe-api-discovery-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recipe-api-discovery-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recipe-api-discovery-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://recipe-api.com/openapi.json)
- [Documentation](https://recipe-api.com/docs)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Pricing](https://recipe-api.com/pricing)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Authentication](authentication/recipe-api-authentication.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Llms Text](https://recipe-api.com/llms.txt)

### Recipe API Image Generation API

The Image Generation API from Recipe API — 1 operation(s) for image generation.

- **Human URL:** [https://recipe-api.com/docs](https://recipe-api.com/docs)
- **Base URL:** `https://recipe-api.com`

#### Tags

- Image Generation

#### Properties

- [OpenAPI](openapi/recipe-api-image-generation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recipe-api-image-generation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recipe-api-image-generation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://recipe-api.com/openapi.json)
- [Documentation](https://recipe-api.com/docs)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Pricing](https://recipe-api.com/pricing)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Authentication](authentication/recipe-api-authentication.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Llms Text](https://recipe-api.com/llms.txt)

### Recipe API Ingredients API

Search ingredients free. Per-100g USDA nutrition by ID costs 1 credit.

- **Human URL:** [https://recipe-api.com/docs](https://recipe-api.com/docs)
- **Base URL:** `https://recipe-api.com`

#### Tags

- Ingredients

#### Properties

- [OpenAPI](openapi/recipe-api-ingredients-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recipe-api-ingredients-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recipe-api-ingredients-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://recipe-api.com/openapi.json)
- [Documentation](https://recipe-api.com/docs)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Pricing](https://recipe-api.com/pricing)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Authentication](authentication/recipe-api-authentication.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Llms Text](https://recipe-api.com/llms.txt)

### Recipe API Public API

No authentication required. Try `/api/v1/dinner` for a complete recipe example.

- **Human URL:** [https://recipe-api.com/docs](https://recipe-api.com/docs)
- **Base URL:** `https://recipe-api.com`

#### Tags

- Public

#### Properties

- [OpenAPI](openapi/recipe-api-public-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recipe-api-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recipe-api-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://recipe-api.com/openapi.json)
- [Documentation](https://recipe-api.com/docs)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Pricing](https://recipe-api.com/pricing)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Authentication](authentication/recipe-api-authentication.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Llms Text](https://recipe-api.com/llms.txt)

### Recipe API Recipes API

Browse recipes free. Full recipe detail costs 1 credit. Sample data shown inline.

- **Human URL:** [https://recipe-api.com/docs](https://recipe-api.com/docs)
- **Base URL:** `https://recipe-api.com`

#### Tags

- Recipes

#### Properties

- [OpenAPI](openapi/recipe-api-recipes-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/recipe-api-recipes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/recipe-api-recipes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://recipe-api.com/openapi.json)
- [Documentation](https://recipe-api.com/docs)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Pricing](https://recipe-api.com/pricing)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Authentication](authentication/recipe-api-authentication.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Llms Text](https://recipe-api.com/llms.txt)

## Common Properties

- [Website](https://recipe-api.com)
- [Documentation](https://recipe-api.com/docs)
- [Pricing](https://recipe-api.com/pricing)
- [Signup](https://recipe-api.com/signup)
- [Login](https://recipe-api.com/login)
- [Terms of Service](https://recipe-api.com/terms)
- [Privacy Policy](https://recipe-api.com/privacy)
- [Llms Text](https://recipe-api.com/llms.txt)
- [M C P Server](mcp/recipe-api-mcp.yml)
- [Plans](plans/recipe-api-plans.yml)
- [Rate Limits](rate-limits/recipe-api-rate-limits.yml)
- [Authentication](authentication/recipe-api-authentication.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
