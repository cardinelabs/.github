# Cardine Labs

**Dependable building blocks for data, automation and AI agents.**

We build tools that sit at the joints between systems, where small failures become expensive ones. Every tool we ship follows the same rules:

- **Predictable cost** — the limit you set is the limit you pay for.
- **Transparent runs** — every run reports what it did, what it skipped and why.
- **Measured quality** — benchmarked on real sites before release, numbers in the README.
- **Fast support** — issues answered within 48 hours.

## Apify Actors

| Actor | What it does |
|---|---|
| [MD Crawler RAG](https://apify.com/cardine-labs/md-crawler-rag) | Website to clean Markdown and heading-aware chunks for RAG. Hard page cap, incremental re-crawls. |
| [SEO Site Auditor](https://apify.com/cardine-labs/seo-site-auditor) | Technical SEO audit with priorities, 0-100 score and run-to-run diff. |
| [Shop Price Monitor](https://apify.com/cardine-labs/shop-price-monitor) | Price and stock changes from Shopify and WooCommerce stores, with webhooks. |
| [News Feed Monitor](https://apify.com/cardine-labs/news-feed-monitor) | Many RSS/Atom feeds, only new articles, duplicates across outlets merged. |
| [Tech Stack Detector](https://apify.com/cardine-labs/tech-stack-detector) | What a website runs on (CMS, e-commerce, analytics, hosting), with evidence. |

## MCP servers

| Server | What it does |
|---|---|
| [fs-sandbox-mcp](https://github.com/cardinelabs/fs-sandbox-mcp) | Filesystem MCP server with declarative policy, tamper-evident audit log, dry-run writes and undo. Regression tests for known path-confinement bug classes. `npx -y @cardinelabs/fs-sandbox-mcp` |

## Coming next
More MCP servers for AI agents and small self-hostable serverless tools.

Questions or ideas: open an issue on any Actor page.
