# LAP Coffee

LAP Coffee ("Life Among People") is a Berlin-founded specialty coffee retail chain operated by
Micro Retail Technologies MRT GmbH. It opened its first store in Berlin Mitte in August 2023 and
now runs a network of small, high-throughput neighbourhood cafes across Berlin, with locations and
openings in Cologne, Frankfurt, Munich and Hamburg. LAP serves locally roasted specialty coffee at
everyday prices and runs a consumer mobile app (LAP: Everyday Coffee) for pre-ordering, in-store
pickup, stamps and rewards, gifting and referrals.

Backed by: hv-capital

## API surface

**None.** As of the 2026-07-19 enrichment pass LAP Coffee publishes no public API, developer portal,
API reference, SDK, CLI, MCP server or OpenAPI. Verified negatives:

- No `/.well-known/` discovery documents on `www.lap.coffee` or `order.lap.coffee` (all 404) —
  see [`well-known/lap-coffee-well-known.yml`](well-known/lap-coffee-well-known.yml).
- No `/llms.txt`, no `/openapi.json`.
- No GitHub organization (`lapcoffee`, `lap-coffee` both 404).
- No first-party packages on npm or PyPI.
- No published vulnerability-disclosure program or trust center.

`order.lap.coffee/<code>` is a per-store deep-link/attribution service that 302s to the App Store
listing — it is not an API.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Profile | [`apis.yml`](apis.yml) | searched |
| Domain security | [`security/lap-coffee-domain-security.yml`](security/lap-coffee-domain-security.yml) | probed |
| Well-known probe | [`well-known/lap-coffee-well-known.yml`](well-known/lap-coffee-well-known.yml) | probed |
| llms.txt | [`llms/lap-coffee-llms.txt`](llms/lap-coffee-llms.txt) | generated |
