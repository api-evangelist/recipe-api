# Recipe API

B2B recipe and nutrition API — structured recipes with USDA-backed nutrition data, ingredient
nutrition per 100g, on-demand recipe generation, and food photography generation.

- **Website:** https://recipe-api.com
- **Documentation:** https://recipe-api.com/docs
- **Pricing:** https://recipe-api.com/pricing
- **OpenAPI:** https://recipe-api.com/openapi.json — provider-published, harvested verbatim
- **llms.txt:** https://recipe-api.com/llms.txt
- **MCP server:** https://recipe-api.com/mcp

Part of the [API Evangelist](https://apievangelist.com) network. Profiled 2026-08-03 after the
provider wrote in; every surface recorded here was fetched and confirmed before the profile was
written — see `X-Discovery` in `apis.yml`.

## Artifacts

| Artifact | Path |
| --- | --- |
| OpenAPI (provider-published) | `openapi/recipe-api-openapi.json` |
| llms.txt | `llms/recipe-api-llms.txt` |
| MCP server | `mcp/recipe-api-mcp.yml` |
| Authentication | `authentication/recipe-api-authentication.yml` |
| Plans | `plans/recipe-api-plans.yml` |
| Rate limits | `rate-limits/recipe-api-rate-limits.yml` |

## Notes

- The API publishes a **keyless quick-start** call (`GET /api/v1/dinner`), so a developer or an
  agent can make a real request before signing up.
- The MCP endpoint at `/api/mcp` answers **401** rather than 404 — it exists and is key-gated, so
  the tool list could not be enumerated anonymously.
- The OpenAPI carries no `operationId` values, which is the clearest single improvement available
  to it.
