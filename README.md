# Aligned News (aligned-news)

Aligned News is an AI-native intelligence and news platform that synthesizes AI-powered briefings from 63 curated X lists tracking 100,000+ accounts across AI, technology, and science. The platform publishes Stories, Signals, Reports, and Bundles via web, REST API, and a downloadable MCP server for AI tools like Claude Code, Claude Desktop, Cursor, and Windsurf. The Free tier exposes headlines, signal badges, and report summaries; the Pro tier unlocks full content plus REST API and MCP access; Enterprise adds team access, priority support, and custom analysis.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/apis.yml)

**Source:** https://alignednews.com/

**Inbox issue:** [#902](https://github.com/api-evangelist/inbox/issues/902)

## Tags

- AI, News, Intelligence, MCP, Signals

## Timestamps

- **Created:** 2026-05-06
- **Modified:** 2026-05-06

## APIs

### Aligned News
Consumer-facing AI news intelligence platform delivering Stories, Signals, Reports, and Bundles synthesized from 63 curated X lists tracking 100,000+ accounts across AI, technology, and science.

**Human URL:** [https://alignednews.com/](https://alignednews.com/)

#### Tags

- AI, News, Intelligence

#### Properties

- [Documentation](https://alignednews.com/how-it-works)
- [Pricing](https://alignednews.com/pricing)
- [Sign Up](https://alignednews.com/getting-started)

### Aligned News REST API
Read-only REST API for Aligned News content. Lets developers and AI agents fetch Stories, Signals, Reports, Bundles, the section-grouped news feed, and run full-text search across all content. All endpoints require an API key passed as `Authorization: Bearer alnw_...` and are reserved for Pro subscribers.

**Human URL:** [https://alignednews.com/developers](https://alignednews.com/developers)

**Base URL:** `https://alignednews.com/v1`

#### Tags

- AI, News, Intelligence, REST, Signals, Search

#### Properties

- [Documentation](https://alignednews.com/developers)
- [Authentication](https://alignednews.com/account)
- [Pricing](https://alignednews.com/pricing)
- [OpenAPI](openapi/aligned-news-openapi.yml)
- [Plans](plans/aligned-news-plans-pricing.yml)
- [Rate Limits](rate-limits/aligned-news-rate-limits.yml)
- [FinOps](finops/aligned-news-finops.yml)

### Aligned News MCP Server
Reference Model Context Protocol server distributed as a single TypeScript file (`mcp-server.ts`) that proxies the Aligned News REST API to MCP-compatible AI tools like Claude Code, Claude Desktop, Cursor, and Windsurf. Exposes `search_news`, `get_stories`, `get_story`, `get_signals`, `get_signal`, `get_reports`, `get_report`, and `get_sections` tools, plus an `aligned://news-feed` resource. Authenticates with a user-provided `ALIGNED_API_KEY` (Bearer `alnw_...`).

**Human URL:** [https://alignednews.com/developers](https://alignednews.com/developers)

**Base URL:** `https://alignednews.com/v1`

#### Tags

- AI, MCP, Agents, Tooling

#### Properties

- [Documentation](https://alignednews.com/developers)
- [Source Code](https://alignednews.com/mcp-server.ts)
- [Authentication](https://alignednews.com/account)

## Common

- [Website](https://alignednews.com/)
- [How It Works](https://alignednews.com/how-it-works)
- [Getting Started](https://alignednews.com/getting-started)
- [Pricing](https://alignednews.com/pricing)
- [Developers](https://alignednews.com/developers)
- [Sign Up](https://alignednews.com/account)
- [Sitemap](https://alignednews.com/sitemap.xml)
- [Robots TXT](https://alignednews.com/robots.txt)
- [Research](https://alignednews.com/research)
- [Signals](https://alignednews.com/signals)
- [Reports](https://alignednews.com/reports)
- [Bundles](https://alignednews.com/bundles)
- [AI](https://alignednews.com/ai)
- [MCP Server](https://alignednews.com/mcp-server.ts)
- [GitHub Org](https://github.com/Aligned-news)

## Features

- AI-powered intelligence from 63 curated X lists
- Tracks 100,000+ accounts across AI, technology, and science
- Stories surface breaking AI news with full body content
- Signals provide early pattern detection with badges (bullish, caution, critical, signal, interview, vc, action)
- Reports deliver trend deep-dives and summaries
- Bundles group related stories around themes
- Section-organized news feed across all topics
- Full-text Search across stories, signals, and reports
- REST API gated behind Pro tier with Bearer alnw_ API keys
- Downloadable single-file MCP server for Claude Code, Claude Desktop, Cursor, and Windsurf
- Free tier exposes headlines, summaries, signal badges, and report summaries only
- Pro tier unlocks full content + API access
- Enterprise tier adds team access, priority support, and custom analysis
- Built on Fly.io (edge), Supabase (data), Clerk (auth and billing), Stripe (payments)

## OpenAPI

- [aligned-news-openapi.yml](openapi/aligned-news-openapi.yml)

## Examples

- [aligned-news-listStories-example.json](examples/aligned-news-listStories-example.json)
- [aligned-news-getStory-example.json](examples/aligned-news-getStory-example.json)
- [aligned-news-listSignals-example.json](examples/aligned-news-listSignals-example.json)
- [aligned-news-getSignal-example.json](examples/aligned-news-getSignal-example.json)
- [aligned-news-listReports-example.json](examples/aligned-news-listReports-example.json)
- [aligned-news-getReport-example.json](examples/aligned-news-getReport-example.json)
- [aligned-news-listBundles-example.json](examples/aligned-news-listBundles-example.json)
- [aligned-news-getBundle-example.json](examples/aligned-news-getBundle-example.json)
- [aligned-news-listSections-example.json](examples/aligned-news-listSections-example.json)
- [aligned-news-getNewsFeed-example.json](examples/aligned-news-getNewsFeed-example.json)
- [aligned-news-searchContent-example.json](examples/aligned-news-searchContent-example.json)

## JSON Schema

- [aligned-news-story-schema.json](json-schema/aligned-news-story-schema.json)
- [aligned-news-signal-schema.json](json-schema/aligned-news-signal-schema.json)
- [aligned-news-report-schema.json](json-schema/aligned-news-report-schema.json)
- [aligned-news-bundle-schema.json](json-schema/aligned-news-bundle-schema.json)
- [aligned-news-section-schema.json](json-schema/aligned-news-section-schema.json)

## JSON Structure

- [aligned-news-story-structure.json](json-structure/aligned-news-story-structure.json)
- [aligned-news-signal-structure.json](json-structure/aligned-news-signal-structure.json)
- [aligned-news-report-structure.json](json-structure/aligned-news-report-structure.json)
- [aligned-news-bundle-structure.json](json-structure/aligned-news-bundle-structure.json)
- [aligned-news-section-structure.json](json-structure/aligned-news-section-structure.json)

## JSON-LD Context

- [aligned-news-context.jsonld](json-ld/aligned-news-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Aligned News](capabilities/shared/aligned-news.yaml) — 11 operations across stories, signals, reports, bundles, sections, news-feed, and search

### Workflow Capabilities

| Workflow | Description | MCP Tools |
|----------|-------------|-----------|
| [AI News Intelligence](capabilities/ai-news-intelligence.yaml) | Unified AI news intelligence workflow exposing the Aligned News REST surface to AI agents, briefing tools, and research dashboards. | 11 |

## Vocabulary

- [aligned-news-vocabulary.yaml](vocabulary/aligned-news-vocabulary.yaml) — 7 resources, 1 workflow, 4 domains, 4 personas

## Rules

- [aligned-news-rules.yml](rules/aligned-news-rules.yml) — 8 Spectral rules enforcing Aligned News conventions

## Plans and Pricing

- [aligned-news-plans-pricing.yml](plans/aligned-news-plans-pricing.yml) — 3 plans (Free, Pro, Enterprise) using API Commons Plans 0.1. `reconciled: false` because public site does not embed price values; pricing rendered client-side via Clerk Billing.

## Rate Limits

- [aligned-news-rate-limits.yml](rate-limits/aligned-news-rate-limits.yml) — Subscription-gated access using API Commons Rate Limits 0.1. `reconciled: false`; per-tier per-minute limits not publicly documented.

## FinOps

- [aligned-news-finops.yml](finops/aligned-news-finops.yml) — Subscription-based FinOps model using FinOps Framework 1.0 / FOCUS 1.3. `reconciled: false`; flat-rate Pro and contact-sales Enterprise.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
