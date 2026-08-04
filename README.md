# JokeAPI (jokeapi)

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

JokeAPI is a free, open source REST API that delivers consistently formatted jokes in JSON, XML, YAML, or plain text. It exposes seven joke categories (Any, Misc, Programming, Dark, Pun, Spooky, Christmas), six blacklist content flags (nsfw, religious, political, racist, sexist, explicit), and filters for language, joke type, ID range, contains-text search, amount, and safe-mode. No sign-up is required and CORS is enabled. The service is rate-limited at 120 requests per minute per IP (5 per minute on submissions) and is maintained by Sv443 under the MIT license. The canonical source lives on Sv443's own Git server, with this GitHub repo kept open for issues and the community wrapper-library index.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Jokes
- Humor
- Entertainment
- Open Source
- REST API
- Games And Comics
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### JokeAPI v2

The JokeAPI v2 REST surface — ten endpoints covering joke retrieval (`/joke/{category}`), submission (`/submit`), and metadata (`/categories`, `/flags`, `/formats`, `/languages`, `/langcode/{language}`, `/info`, `/endpoints`, `/ping`). Supports JSON, XML, YAML, and plain text response formats, six blacklist flags, seven joke categories, and six joke languages (English, German, Czech, Spanish, French, Portuguese).

- **Human URL:** [https://jokeapi.dev/](https://jokeapi.dev/)
- **Base URL:** `https://v2.jokeapi.dev`

#### Tags

- Jokes
- Humor
- REST API

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/openapi/jokeapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://jokeapi.dev/)
- [Documentation](https://jokeapi.dev/#try-it)
- [Source Code](https://git.sv443.net/sv443/JokeAPI-v2)
- [Source Code Mirror](https://github.com/Sv443-Network/JokeAPI)
- [Changelog](https://github.com/Sv443-Network/JokeAPI/blob/main/changelog.md)
- [Status Page](https://status.sv443.net/)
- [SDK](https://github.com/sahithyandev/sv443-joke-api-js-wrapper)
- [SDK](https://github.com/thenamesweretakenalready/Sv443s-JokeAPI-Python-Wrapper)
- [SDK](https://github.com/bitstep-ie/jokeapi)
- [SDK](https://github.com/DanBuxton/JokeAPI-CS-Wrapper)
- [SDK](https://github.com/MichaelDark/jokeapi)
- [SDK](https://github.com/Icelain/jokeapi)
- [SDK](https://github.com/the-codeboy/Jokes4J)
- [SDK](https://github.com/EasyG0ing1/JavaJokesAPI)
- [SDK](https://github.com/khurozov/jokeapi-java)
- [SDK](https://github.com/ethauvin/jokeapi)
- [SDK](https://github.com/IllusionMan1212/jokeapi-odin)
- [SDK](https://github.com/JustPush-io/php-jokeapi)
- [SDK](https://github.com/canarado/joketeller)
- [Postman Collection](collections/jokeapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jokeapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://jokeapi.dev/)
- [Documentation](https://jokeapi.dev/)
- [Git Hub](https://github.com/Sv443-Network/JokeAPI)
- [Source Code](https://git.sv443.net/sv443/JokeAPI-v2)
- [License](https://github.com/Sv443-Network/JokeAPI/blob/main/LICENSE.txt)
- [Discord](https://dc.sv443.net/)
- [Status Page](https://status.sv443.net/)
- [Sponsor](https://github.com/sponsors/Sv443)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/openapi/jokeapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/json-schema/jokeapi-single-joke-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/json-ld/jokeapi-context.jsonld)
- [Plans](plans/jokeapi-plans-pricing.yml)
- [Rate Limits](rate-limits/jokeapi-rate-limits.yml)
- [Spectral Ruleset](rules/jokeapi-spectral-rules.yml)
- [Vocabulary](vocabulary/jokeapi-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
