# LAP Coffee

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
