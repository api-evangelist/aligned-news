# Aligned News (aligned-news)

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

Aligned News is an AI-native intelligence and news platform that synthesizes AI-powered briefings from 63 curated X lists tracking 100,000+ accounts in AI, tech, and science, and publishes Stories, Signals, Reports, and Bundles via web, REST API, and a downloadable MCP server for AI tools like Claude, Cursor, and Windsurf.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- News
- Intelligence
- MCP
- Signals

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-19

## APIs


#### Tags

- AI
- News
- Intelligence

#### Properties

- [Documentation](https://alignednews.com/how-it-works)
- [Pricing](https://alignednews.com/pricing)
- [Sign Up](https://alignednews.com/getting-started)
- [Postman Collection](collections/aligned-news.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aligned-news.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aligned News REST API

Read-only REST API for Aligned News content. Lets developers and AI agents fetch Stories, Signals, Reports, Bundles, the section-grouped news feed, and run full-text search across all content. All endpoints require an API key passed as Authorization Bearer alnw_... and are reserved for Pro subscribers.

- **Human URL:** [https://alignednews.com/developers](https://alignednews.com/developers)
- **Base URL:** `https://alignednews.com/v1`

#### Tags

- AI
- News
- Intelligence
- REST
- Signals
- Search

#### Properties

- [Documentation](https://alignednews.com/developers)
- [Authentication](https://alignednews.com/account)
- [Pricing](https://alignednews.com/pricing)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/openapi/aligned-news-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/plans/aligned-news-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/rate-limits/aligned-news-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/finops/aligned-news-finops.yml)
- [Postman Collection](collections/aligned-news.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aligned-news.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aligned News MCP Server

Reference Model Context Protocol server distributed as a single TypeScript file (mcp-server.ts) that proxies the Aligned News REST API to MCP-compatible AI tools like Claude Code, Claude Desktop, Cursor, and Windsurf. Exposes search_news, get_stories, get_story, get_signals, get_signal, get_reports, get_report, and get_sections tools, plus an aligned://news-feed resource. Authenticates with a user-provided ALIGNED_API_KEY (Bearer alnw_...).

- **Human URL:** [https://alignednews.com/developers](https://alignednews.com/developers)
- **Base URL:** `https://alignednews.com/v1`

#### Tags

- AI
- MCP
- Agents
- Tooling

#### Properties

- [Documentation](https://alignednews.com/developers)
- [Source  Code](https://alignednews.com/mcp-server.ts)
- [Authentication](https://alignednews.com/account)
- [Postman Collection](collections/aligned-news.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aligned-news.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://alignednews.com/)
- [How  It  Works](https://alignednews.com/how-it-works)
- [Getting Started](https://alignednews.com/getting-started)
- [Pricing](https://alignednews.com/pricing)
- [Developers](https://alignednews.com/developers)
- [Sign Up](https://alignednews.com/account)
- [Sitemap](https://alignednews.com/sitemap.xml)
- [Robots  T X T](https://alignednews.com/robots.txt)
- [Research](https://alignednews.com/research)
- [Signals](https://alignednews.com/signals)
- [Reports](https://alignednews.com/reports)
- [Bundles](https://alignednews.com/bundles)
- [A I](https://alignednews.com/ai)
- [M C P  Server](https://alignednews.com/mcp-server.ts)
- [Git Hub  Org](https://github.com/Aligned-news)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**FN:** Aligned News
**URL:** https://alignednews.com/
