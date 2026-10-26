# Cloudflare AI Gateway (cloudflare-ai-gateway)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cloudflare-ai-gateway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudflare-ai-gateway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI Gateway
- LLM
- Observability
- Caching
- Rate Limiting
- Workers AI
- Cloudflare

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Cloudflare AI Gateway Proxy

The AI Gateway proxy endpoint accepts requests in each provider's native API format and forwards them through Cloudflare's edge with analytics, caching, retries, rate limiting, fallback, and guardrails applied. URL pattern is https://gateway.ai.cloudflare.com/v1/{account_id}/{gateway_id}/{provider}. Authentication uses a Cloudflare API token with AI Gateway Read/Edit and Workers AI Read permissions; provider credentials can be sent as headers (BYOK) or stored via Unified Billing.

- **Human URL:** [https://developers.cloudflare.com/ai-gateway/](https://developers.cloudflare.com/ai-gateway/)
- **Base URL:** `https://gateway.ai.cloudflare.com`

#### Tags

- LLM Proxy
- REST API
- Multi-Provider

#### Properties

- [Documentation](https://developers.cloudflare.com/ai-gateway/)
- [Getting Started](https://developers.cloudflare.com/ai-gateway/get-started/)
- [API Reference](https://developers.cloudflare.com/ai-gateway/usage/providers/)
- [Authentication](https://developers.cloudflare.com/ai-gateway/get-started/)
- [Postman Collection](collections/cloudflare-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudflare-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudflare AI Gateway Unified REST API

Unified REST API launched May 21, 2026 that lets developers call any supported model through a single endpoint instead of formatting requests for each provider individually. Sits alongside the provider-native proxy mode and uses the same gateway routing, caching, observability, and guardrails.

- **Human URL:** [https://developers.cloudflare.com/ai-gateway/](https://developers.cloudflare.com/ai-gateway/)
- **Base URL:** `https://gateway.ai.cloudflare.com`

#### Tags

- Unified API
- LLM
- Multi-Provider

#### Properties

- [Documentation](https://developers.cloudflare.com/ai-gateway/)
- [API Reference](https://developers.cloudflare.com/ai-gateway/usage/providers/)
- [Postman Collection](collections/cloudflare-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudflare-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudflare AI Gateway Management API

The Cloudflare API surface for managing AI Gateway resources — creating gateways, listing them, retrieving request logs, and configuring caching, rate limiting, and authentication. Exposed under the standard Cloudflare REST API at api.cloudflare.com.

- **Human URL:** [https://developers.cloudflare.com/api/resources/ai_gateway/](https://developers.cloudflare.com/api/resources/ai_gateway/)
- **Base URL:** `https://api.cloudflare.com`

#### Tags

- Management API
- REST API
- Configuration

#### Properties

- [Documentation](https://developers.cloudflare.com/api/resources/ai_gateway/)
- [API Reference](https://developers.cloudflare.com/api/resources/ai_gateway/)
- [Postman Collection](collections/cloudflare-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudflare-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AI Gateway MCP Server

Cloudflare-hosted remote MCP server that exposes AI Gateway control-plane operations to MCP-compatible AI agents.

- **Human URL:** [https://ai-gateway.mcp.cloudflare.com/mcp](https://ai-gateway.mcp.cloudflare.com/mcp)

#### Tags

- MCP
- Agentic AI

#### Properties

- [M C P Server](https://ai-gateway.mcp.cloudflare.com/mcp)
- [Postman Collection](collections/cloudflare-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloudflare-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developers.cloudflare.com/ai-gateway/)
- [Documentation](https://developers.cloudflare.com/ai-gateway/)
- [Getting Started](https://developers.cloudflare.com/ai-gateway/get-started/)
- [API Reference](https://developers.cloudflare.com/ai-gateway/usage/providers/)
- [Authentication](https://developers.cloudflare.com/fundamentals/api/get-started/create-token/)
- [Changelog](https://developers.cloudflare.com/changelog/)
- [Blog](https://blog.cloudflare.com/)
- [Sign Up](https://dash.cloudflare.com/sign-up)
- [Console](https://dash.cloudflare.com/)
- [Pricing](https://www.cloudflare.com/plans/)
- [SDK](https://github.com/cloudflare/cloudflare-typescript)
- [SDK](https://github.com/cloudflare/cloudflare-python)
- [SDK](https://github.com/cloudflare/cloudflare-go)
- [C L I](https://developers.cloudflare.com/workers/wrangler/)
- [M C P Server](https://ai-gateway.mcp.cloudflare.com/mcp)
- [GitHub Organization](https://github.com/cloudflare)
- [Status Page](https://www.cloudflarestatus.com/)
- [Support](https://support.cloudflare.com/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://developers.cloudflare.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
