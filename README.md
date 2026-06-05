# Cloudflare AI Gateway (cloudflare-ai-gateway)

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
