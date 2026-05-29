# JokeAPI (jokeapi)

JokeAPI is a free, open source REST API that delivers consistently formatted jokes in JSON, XML, YAML, or plain text. It exposes seven joke categories (Any, Misc, Programming, Dark, Pun, Spooky, Christmas), six blacklist content flags (nsfw, religious, political, racist, sexist, explicit), and filters for language, joke type, ID range, contains-text search, amount, and safe-mode. No sign-up is required and CORS is enabled. The service is rate-limited at 120 requests per minute per IP (5 per minute on submissions) and is maintained by Sv443 under the MIT license. The canonical source lives on Sv443's own Git server, with this GitHub repo kept open for issues and the community wrapper-library index.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/jokeapi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=opensource-api-evangelist&utm_content=repo)

## Tags:

 - Jokes, Humor, Entertainment, Open Source, REST API, Games And Comics, Public APIs

## Type

- **x-type:** opensource
- **x-tier:** 3 (bulk-registered from public-apis, then enriched via the opensource pipeline)
- **license:** MIT
- **maintainer:** Sv443 ([github.com/Sv443](https://github.com/Sv443))

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### JokeAPI v2

The JokeAPI v2 REST surface — ten endpoints covering joke retrieval (`/joke/{category}`), submission (`/submit`), and metadata (`/categories`, `/flags`, `/formats`, `/languages`, `/langcode/{language}`, `/info`, `/endpoints`, `/ping`). Supports JSON, XML, YAML, and plain text response formats, six blacklist flags, seven joke categories, and six joke languages (English, German, Czech, Spanish, French, Portuguese).

**Human URL:** [https://jokeapi.dev/](https://jokeapi.dev/)

**Base URL:** `https://v2.jokeapi.dev`

#### Tags:

 - Jokes, Humor, REST API

#### Properties

- [OpenAPI](openapi/jokeapi-openapi.yml)
- [Documentation](https://jokeapi.dev/)
- [Documentation — Try It](https://jokeapi.dev/#try-it)
- [Source Code (canonical)](https://git.sv443.net/sv443/JokeAPI-v2)
- [Source Code Mirror (GitHub)](https://github.com/Sv443-Network/JokeAPI)
- [Changelog](https://github.com/Sv443-Network/JokeAPI/blob/main/changelog.md)
- [Status Page](https://status.sv443.net/)

#### Community SDKs / Wrappers

- [Node.js Wrapper](https://github.com/sahithyandev/sv443-joke-api-js-wrapper)
- [Python Wrapper](https://github.com/thenamesweretakenalready/Sv443s-JokeAPI-Python-Wrapper)
- [TypeScript Wrapper](https://github.com/bitstep-ie/jokeapi)
- [C# Wrapper](https://github.com/DanBuxton/JokeAPI-CS-Wrapper)
- [Dart Wrapper](https://github.com/MichaelDark/jokeapi)
- [Go Wrapper](https://github.com/Icelain/jokeapi)
- [Java Wrapper — Jokes4J](https://github.com/the-codeboy/Jokes4J)
- [Java Wrapper — JavaJokesAPI](https://github.com/EasyG0ing1/JavaJokesAPI)
- [Java Wrapper — jokeapi-java](https://github.com/khurozov/jokeapi-java)
- [Kotlin / Java / Android Wrapper](https://github.com/ethauvin/jokeapi)
- [Odin Wrapper](https://github.com/IllusionMan1212/jokeapi-odin)
- [PHP Wrapper](https://github.com/JustPush-io/php-jokeapi)
- [Rust Wrapper — joketeller](https://github.com/canarado/joketeller)

#### Naftiko Capabilities

- [JokeAPI — Jokes](capabilities/jokeapi-jokes.yaml)
- [JokeAPI — Metadata](capabilities/jokeapi-metadata.yaml)
- [JokeAPI — System](capabilities/jokeapi-system.yaml)

## Common Properties

- [Website](https://jokeapi.dev/)
- [Documentation](https://jokeapi.dev/)
- [GitHub](https://github.com/Sv443-Network/JokeAPI)
- [Source Code (canonical)](https://git.sv443.net/sv443/JokeAPI-v2)
- [License (MIT)](https://github.com/Sv443-Network/JokeAPI/blob/main/LICENSE.txt)
- [Discord](https://dc.sv443.net/)
- [Status Page](https://status.sv443.net/)
- [Sponsor](https://github.com/sponsors/Sv443)
- [public-apis listing](https://github.com/public-apis/public-apis)
- [Plans / Pricing](plans/jokeapi-plans-pricing.yml)
- [Rate Limits](rate-limits/jokeapi-rate-limits.yml)
- [Spectral Ruleset](rules/jokeapi-spectral-rules.yml)
- [Vocabulary](vocabulary/jokeapi-vocabulary.yml)

## Features

| Name | Description |
|------|-------------|
| Free and Open | No sign-up, no API key, MIT license, source open on git.sv443.net (mirrored on GitHub). |
| Multi-Format Responses | Same data available as JSON (default), XML, YAML, or plain text via `?format`. |
| Blacklist Flags | Filter out jokes flagged as nsfw, religious, political, racist, sexist, or explicit. |
| Safe Mode | A single `?safe-mode` switch excludes every joke that carries any flag and every joke in the Dark category. |
| Multi-Language Catalogue | Jokes available in English, German, Czech, Spanish, French, and Portuguese. |
| Bulk Retrieval | Pull up to 10 jokes per request via `?amount`. |
| ID and Contains Filters | Constrain results by joke ID, ID range, or full-text contains query. |
| CORS Enabled | Browser apps can call the API directly without a proxy. |
| Community Submissions | `POST /submit` lets the community contribute new jokes (separate 5-per-minute rate limit, moderator review). |

## Use Cases

| Name | Description |
|------|-------------|
| Chat Bots and Slack Apps | Drop a joke endpoint into a Discord, Slack, or Teams bot. |
| Developer Easter Eggs | 404 pages, CLI surprises, build-success notifications. |
| API Learning Sandbox | A safe, free target for OpenAPI tutorials, REST workshops, and SDK demos. |
| Web Component Demos | Quick payloads to populate joke cards, comedy widgets, and humour newsletters. |
| Content Moderation Training | Public dataset of jokes pre-classified with offensive-content flags, useful for moderation tooling tests. |

## Integrations

| Name |
|------|
| Node.js wrapper |
| Python wrapper |
| TypeScript wrapper |
| C# wrapper |
| Dart wrapper |
| Go wrapper |
| Java wrappers |
| Kotlin / Android wrapper |
| Odin wrapper |
| PHP wrapper |
| Rust wrapper |

## Solutions

| Name | Description |
|------|-------------|
| Daily Joke Feed | Cron a fetch every morning into a Slack channel, RSS feed, or static site build. |
| Comedy CMS | Combine `/joke/{category}` with `/submit` to power a community-driven joke board. |
| Safe-by-Default Embed | Use `?safe-mode` plus `?blacklistFlags` to deliver workplace-safe humour widgets. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [JokeAPI v2 OpenAPI](openapi/jokeapi-openapi.yml) — 10 operations, 15 component schemas

### JSON Schema

- [JokeAPI Single Joke](json-schema/jokeapi-single-joke-schema.json)
- [JokeAPI Twopart Joke](json-schema/jokeapi-twopart-joke-schema.json)
- [JokeAPI Joke Batch](json-schema/jokeapi-joke-batch-schema.json)
- [JokeAPI Joke Flags](json-schema/jokeapi-joke-flags-schema.json)
- [JokeAPI Joke Submission](json-schema/jokeapi-joke-submission-schema.json)
- [JokeAPI Submission Response](json-schema/jokeapi-submission-response-schema.json)
- [JokeAPI Categories Response](json-schema/jokeapi-categories-response-schema.json)
- [JokeAPI Flags Response](json-schema/jokeapi-flags-response-schema.json)
- [JokeAPI Formats Response](json-schema/jokeapi-formats-response-schema.json)
- [JokeAPI Languages Response](json-schema/jokeapi-languages-response-schema.json)
- [JokeAPI Langcode Response](json-schema/jokeapi-langcode-response-schema.json)
- [JokeAPI Info Response](json-schema/jokeapi-info-response-schema.json)
- [JokeAPI Endpoints Response](json-schema/jokeapi-endpoints-response-schema.json)
- [JokeAPI Ping Response](json-schema/jokeapi-ping-response-schema.json)

### JSON Structure

- 14 JSON Structure files mirroring the JSON Schemas above. See [`json-structure/`](json-structure/).

### JSON-LD

- [JokeAPI Context](json-ld/jokeapi-context.jsonld) — 47 properties + 14 type declarations, aligned with schema.org and dcterms

### Examples

- 14 example payloads, one per JSON Schema. See [`examples/`](examples/).

## Capabilities

Naftiko capabilities — self-contained per-tag definitions, each exposing both a REST adapter and an MCP adapter.

| Workflow | Operations | REST | MCP | Persona |
|----------|-----------|------|-----|---------|
| [JokeAPI — Jokes](capabilities/jokeapi-jokes.yaml) | 2 | port 8080 | port 9090 | Bot Author, Demo Developer |
| [JokeAPI — Metadata](capabilities/jokeapi-metadata.yaml) | 5 | port 8080 | port 9090 | Demo Developer, Integration Engineer |
| [JokeAPI — System](capabilities/jokeapi-system.yaml) | 3 | port 8080 | port 9090 | Operator, Monitoring |

## Vocabulary

- [JokeAPI Vocabulary](vocabulary/jokeapi-vocabulary.yml) — Unified taxonomy mapping 10 resources, 5 actions, 3 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Plans

- [JokeAPI Plans / Pricing](plans/jokeapi-plans-pricing.yml) — 2 plans (Free Public, Self-Hosted Open Source). API Commons Plans 0.1.

## Rate Limits

- [JokeAPI Rate Limits](rate-limits/jokeapi-rate-limits.yml) — 2 documented limits (120 req/min standard, 5 req/min on /submit), 5 policies. API Commons Rate Limits 0.1.

## Rules

- [JokeAPI Spectral Ruleset](rules/jokeapi-spectral-rules.yml) — 42 rules across 12 categories enforcing JokeAPI documentation conventions (title-case `JokeAPI`-prefixed summaries, kebab-case paths, camelCase parameters, JSON-first responses, error envelope shape, etc.).

## Notes

This entry was bulk-registered as part of a public-apis catalog sweep on 2026-05-28 and then fully enriched via the API Evangelist opensource pipeline on 2026-05-29 (OpenAPI generated from the live docs and the `/info` endpoint, schemas / structures / JSON-LD / examples / capabilities / vocabulary / plans / rate-limits all derived from that spec).

## Maintainers

- **Kin Lane** — kin@apievangelist.com
