# Cloudflare AI Gateway

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

Cloudflare AI Gateway is a managed LLM proxy that sits in front of 23+ AI providers (OpenAI, Anthropic, Google AI Studio, Google Vertex AI, Amazon Bedrock, Azure OpenAI, Workers AI, Mistral, Cohere, Groq, DeepSeek, Cerebras, xAI, Perplexity, Replicate, HuggingFace, OpenRouter, ElevenLabs, Deepgram, Cartesia, Ideogram, Fal AI, Baseten, Parallel) and provides analytics, request and error logging, response caching, rate limiting, request retries, model fallback, guardrails, and evaluations. A unified REST API launched May 21, 2026 lets developers call any model through a single endpoint. The gateway integrates with Workers AI, the Secrets Store, and Cloudflare CASB's Claude Compliance API support. This is a standalone product profile; the broader Cloudflare provider profile lives at github.com/api-evangelist/cloudflare.

**Areas:** AI Gateway · LLM · Observability · Caching · Rate Limiting · Workers AI · Cloudflare

## Cloudflare AI Gateway on APIs.io

Everything profiled for Cloudflare AI Gateway is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudflare-ai-gateway/](https://apis.io/providers/cloudflare-ai-gateway/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Cloudflare AI Gateway Proxy](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-proxy/) — The AI Gateway proxy endpoint accepts requests in each provider's native API format and forwards them through Cloudflare's edge with analytics, caching,…
- [Cloudflare AI Gateway Unified REST API](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-unified-api/) — Unified REST API launched May 21, 2026 that lets developers call any supported model through a single endpoint instead of formatting requests for each…
- [Cloudflare AI Gateway Management API](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-management-api/) — The Cloudflare API surface for managing AI Gateway resources — creating gateways, listing them, retrieving request logs, and configuring caching, rate…
- [AI Gateway MCP Server](https://apis.io/apis/cloudflare-ai-gateway/ai-gateway-mcp/) — Cloudflare-hosted remote MCP server that exposes AI Gateway control-plane operations to MCP-compatible AI agents.
- [Cloudflare AI Gateway Gateways API](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-gateways-api/) — The Gateways API from Cloudflare AI Gateway — 2 operation(s) for gateways.
- [Cloudflare AI Gateway Logs API](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-logs-api/) — The Logs API from Cloudflare AI Gateway — 1 operation(s) for logs.
- [Cloudflare AI Gateway Proxy API](https://apis.io/apis/cloudflare-ai-gateway/cloudflare-ai-gateway-proxy-api/) — The Proxy API from Cloudflare AI Gateway — 2 operation(s) for proxy.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [mcp](https://apis.io/servers/cloudflare-ai-gateway/mcp/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cloudflare Ai Gateway Agentic Access](https://apis.io/agentic-access/cloudflare-ai-gateway/cloudflare-ai-gateway-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Cloudflare AI Gateway API](https://apis.io/collections/cloudflare-ai-gateway/open-cloudflare-ai-gateway/)
- [Cloudflare AI Gateway Gateways API](https://apis.io/collections/cloudflare-ai-gateway/open-cloudflare-ai-gateway-gateways-api/)
- [Cloudflare AI Gateway Gateways Logs API](https://apis.io/collections/cloudflare-ai-gateway/open-cloudflare-ai-gateway-logs-api/)
- [Cloudflare AI Gateway Gateways Proxy API](https://apis.io/collections/cloudflare-ai-gateway/open-cloudflare-ai-gateway-proxy-api/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudflare Ai Gateway Authentication](https://apis.io/security/cloudflare-ai-gateway/cloudflare-ai-gateway-authentication/)
- [Cloudflare Ai Gateway Domain Security](https://apis.io/security/cloudflare-ai-gateway/cloudflare-ai-gateway-domain-security/)
- [Cloudflare Ai Gateway Vulnerability Disclosure](https://apis.io/security/cloudflare-ai-gateway/cloudflare-ai-gateway-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudflare Ai Gateway Plans Pricing](https://apis.io/plans/cloudflare-ai-gateway/cloudflare-ai-gateway-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudflare Ai Gateway Rate Limits](https://apis.io/rate-limits/cloudflare-ai-gateway/cloudflare-ai-gateway-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudflare Ai Gateway Finops](https://apis.io/finops/cloudflare-ai-gateway/cloudflare-ai-gateway-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cloudflare.com/)
- [Documentation](https://developers.cloudflare.com/ai-gateway/)
- [Getting started](https://developers.cloudflare.com/ai-gateway/get-started/)
- [API reference](https://developers.cloudflare.com/ai-gateway/usage/providers/)
- [Pricing](https://www.cloudflare.com/plans/)
- [Support](https://support.cloudflare.com/)
- [Changelog](https://developers.cloudflare.com/changelog/)
- [Blog](https://blog.cloudflare.com/)
- [GitHub](https://github.com/cloudflare)
- [Status](https://www.cloudflarestatus.com/)

## API Evangelist rating

**Kin Score 49.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 30.0 |
| Contract governance | 0.0 |
| Operational transparency | 50.0 |
| Developer ergonomics | 88.1 |
| Access clarity | 55.3 |

**Agent readiness 42.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 16.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudflare-ai-gateway/](https://apis.io/providers/cloudflare-ai-gateway/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloudflare AI Gateway: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudflare-ai-gateway/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
