# Sylvia API (sylvia-api)

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

Sylvia API is a third-party Reddit data API that serves Reddit content as JSON — posts, comments with full recursive threads, subreddit and user surfaces, and a live comment feed. Thirty-six operations across twelve tags cover the read surface plus account self-service — key management, response templates, usage history and billing. Authentication is an API key. It occupies the gap left by Pushshift, giving researchers and developers queryable Reddit history without going through OAuth on the first-party API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sylvia-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sylvia-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Reddit
- Social
- Data
- Search
- Comments
- Research
- Content
- Datasets

## Timestamps

- **Created:** 2026-08-04
- **Modified:** 2026-08-04

## APIs

### Sylvia API Comments API

The Comments API from Sylvia API — 2 operation(s) for comments.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Comments

#### Properties

- [OpenAPI](openapi/sylvia-api-comments-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-comments-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-comments-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Datasets API

The Datasets API from Sylvia API — 1 operation(s) for datasets.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Datasets

#### Properties

- [OpenAPI](openapi/sylvia-api-datasets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-datasets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-datasets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Live API

The Live API from Sylvia API — 1 operation(s) for live.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Live

#### Properties

- [OpenAPI](openapi/sylvia-api-live-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-live-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-live-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Posts API

The Posts API from Sylvia API — 2 operation(s) for posts.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Posts

#### Properties

- [OpenAPI](openapi/sylvia-api-posts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-posts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-posts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Subreddits API

The Subreddits API from Sylvia API — 2 operation(s) for subreddits.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Subreddits

#### Properties

- [OpenAPI](openapi/sylvia-api-subreddits-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-subreddits-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-subreddits-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Usage API

The Usage API from Sylvia API — 1 operation(s) for usage.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Usage

#### Properties

- [OpenAPI](openapi/sylvia-api-usage-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-usage-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-usage-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

### Sylvia API Users API

The Users API from Sylvia API — 3 operation(s) for users.

- **Human URL:** [https://sylvia-api.com/](https://sylvia-api.com/)
- **Base URL:** `https://api.sylvia-api.com/v1`

#### Tags

- Users

#### Properties

- [OpenAPI](openapi/sylvia-api-users-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sylvia-api-users-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sylvia-api-users-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://sylvia-api.com/openapi.json)
- [Website](https://sylvia-api.com/)
- [Authentication](authentication/sylvia-api-authentication.yml)
- [Llms Text](https://sylvia-api.com/llms.txt)

## Common Properties

- [Website](https://sylvia-api.com/)
- [Llms Text](https://sylvia-api.com/llms.txt)
- [Authentication](authentication/sylvia-api-authentication.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
