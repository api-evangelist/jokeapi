# JokeAPI

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

JokeAPI is a free, open source REST API that delivers consistently formatted jokes in JSON, XML, YAML, or plain text. It exposes seven joke categories (Any, Misc, Programming, Dark, Pun, Spooky, Christmas), six blacklist content flags (nsfw, religious, political, racist, sexist, explicit), and filters for language, joke type, ID range, contains-text search, amount, and safe-mode. No sign-up is required and CORS is enabled. The service is rate-limited at 120 requests per minute per IP (5 per minute on submissions) and is maintained by Sv443 under the MIT license. The canonical source lives on Sv443's own Git server, with this GitHub repo kept open for issues and the community wrapper-library index.

**Areas:** Jokes · Humor · Entertainment · Open Source · REST API · Public APIs

## JokeAPI on APIs.io

Everything profiled for JokeAPI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/jokeapi/](https://apis.io/providers/jokeapi/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [JokeAPI Jokes API](https://apis.io/apis/jokeapi/jokeapi-jokes-api/) — Operations for retrieving and submitting jokes.
- [JokeAPI Metadata API](https://apis.io/apis/jokeapi/jokeapi-metadata-api/) — Operations describing the API surface — categories, flags, formats, languages.
- [JokeAPI System API](https://apis.io/apis/jokeapi/jokeapi-system-api/) — Health and discovery endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Jokeapi Agentic Access](https://apis.io/agentic-access/jokeapi/jokeapi-agentic-access/)

#### JSON Schema (14)

The data models the API reads and writes.

- [CategoriesResponse](https://apis.io/schemas/jokeapi/jokeapi-categories-response/)
- [EndpointsResponse](https://apis.io/schemas/jokeapi/jokeapi-endpoints-response/)
- [FlagsResponse](https://apis.io/schemas/jokeapi/jokeapi-flags-response/)
- [FormatsResponse](https://apis.io/schemas/jokeapi/jokeapi-formats-response/)
- [InfoResponse](https://apis.io/schemas/jokeapi/jokeapi-info-response/)
- [JokeBatch](https://apis.io/schemas/jokeapi/jokeapi-joke-batch/)
- [JokeFlags](https://apis.io/schemas/jokeapi/jokeapi-joke-flags/)
- [JokeSubmission](https://apis.io/schemas/jokeapi/jokeapi-joke-submission/)
- [LangcodeResponse](https://apis.io/schemas/jokeapi/jokeapi-langcode-response/)
- [LanguagesResponse](https://apis.io/schemas/jokeapi/jokeapi-languages-response/)
- [PingResponse](https://apis.io/schemas/jokeapi/jokeapi-ping-response/)
- [SingleJoke](https://apis.io/schemas/jokeapi/jokeapi-single-joke/)
- [SubmissionResponse](https://apis.io/schemas/jokeapi/jokeapi-submission-response/)
- [TwopartJoke](https://apis.io/schemas/jokeapi/jokeapi-twopart-joke/)

#### JSON Structure (14)

Data models expressed in JSON Structure.

- [Jokeapi Categories Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-categories-response-structure/)
- [Jokeapi Endpoints Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-endpoints-response-structure/)
- [Jokeapi Flags Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-flags-response-structure/)
- [Jokeapi Formats Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-formats-response-structure/)
- [Jokeapi Info Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-info-response-structure/)
- [Jokeapi Joke Batch Structure](https://apis.io/json-structure/jokeapi/jokeapi-joke-batch-structure/)
- [Jokeapi Joke Flags Structure](https://apis.io/json-structure/jokeapi/jokeapi-joke-flags-structure/)
- [Jokeapi Joke Submission Structure](https://apis.io/json-structure/jokeapi/jokeapi-joke-submission-structure/)
- [Jokeapi Langcode Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-langcode-response-structure/)
- [Jokeapi Languages Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-languages-response-structure/)
- [Jokeapi Ping Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-ping-response-structure/)
- [Jokeapi Single Joke Structure](https://apis.io/json-structure/jokeapi/jokeapi-single-joke-structure/)
- [Jokeapi Submission Response Structure](https://apis.io/json-structure/jokeapi/jokeapi-submission-response-structure/)
- [Jokeapi Twopart Joke Structure](https://apis.io/json-structure/jokeapi/jokeapi-twopart-joke-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Jokeapi Context](https://apis.io/jsonld/jokeapi/jokeapi-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Jokeapi Vocabulary](https://apis.io/vocabularies/jokeapi/jokeapi-vocabulary/)

#### Examples (14)

Example requests and responses.

- [Jokeapi Categories Response Example](https://apis.io/examples/jokeapi/jokeapi-categories-response-example/)
- [Jokeapi Endpoints Response Example](https://apis.io/examples/jokeapi/jokeapi-endpoints-response-example/)
- [Jokeapi Flags Response Example](https://apis.io/examples/jokeapi/jokeapi-flags-response-example/)
- [Jokeapi Formats Response Example](https://apis.io/examples/jokeapi/jokeapi-formats-response-example/)
- [Jokeapi Info Response Example](https://apis.io/examples/jokeapi/jokeapi-info-response-example/)
- [Jokeapi Joke Batch Example](https://apis.io/examples/jokeapi/jokeapi-joke-batch-example/)
- [Jokeapi Joke Flags Example](https://apis.io/examples/jokeapi/jokeapi-joke-flags-example/)
- [Jokeapi Joke Submission Example](https://apis.io/examples/jokeapi/jokeapi-joke-submission-example/)
- [Jokeapi Langcode Response Example](https://apis.io/examples/jokeapi/jokeapi-langcode-response-example/)
- [Jokeapi Languages Response Example](https://apis.io/examples/jokeapi/jokeapi-languages-response-example/)
- [Jokeapi Ping Response Example](https://apis.io/examples/jokeapi/jokeapi-ping-response-example/)
- [Jokeapi Single Joke Example](https://apis.io/examples/jokeapi/jokeapi-single-joke-example/)
- [Jokeapi Submission Response Example](https://apis.io/examples/jokeapi/jokeapi-submission-response-example/)
- [Jokeapi Twopart Joke Example](https://apis.io/examples/jokeapi/jokeapi-twopart-joke-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [JokeAPI](https://apis.io/collections/jokeapi/open-jokeapi/)
- [Joke Jokes API](https://apis.io/collections/jokeapi/open-jokeapi-jokes-api/)
- [Joke Jokes Metadata API](https://apis.io/collections/jokeapi/open-jokeapi-metadata-api/)
- [Joke Jokes System API](https://apis.io/collections/jokeapi/open-jokeapi-system-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [JokeAPI — jsonschema rules](https://apis.io/rules/jokeapi/jokeapi-jsonschema-spectral-rules/)
- [JokeAPI API Rules](https://apis.io/rules/jokeapi/jokeapi-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Jokeapi Domain Security](https://apis.io/security/jokeapi/jokeapi-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Jokeapi Plans Pricing](https://apis.io/plans/jokeapi/jokeapi-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Jokeapi Rate Limits](https://apis.io/rate-limits/jokeapi/jokeapi-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Jokeapi Finops](https://apis.io/finops/jokeapi/jokeapi-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://jokeapi.dev/)
- [Documentation](https://jokeapi.dev/)
- [Blog](https://jokeapi.dev/blog/)
- [Status](https://status.sv443.net/)

## API Evangelist rating

**Kin Score 25.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 21.1 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 33.3 |
| Access clarity | 5.3 |

**Agent readiness 29.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/jokeapi/](https://apis.io/providers/jokeapi/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for JokeAPI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/jokeapi/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
