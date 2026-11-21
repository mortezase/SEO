---
name: seo
description: Audit, plan, implement, or measure evidence-based SEO for websites and codebases, including technical SEO, keywords, content, structured data, local/international/ecommerce SEO, links, and GEO/AEO. Use for organic-search or AI-search visibility work; do not invent rankings, traffic, search volume, or competitor data.
---

# SEO

Improve discoverability in search engines and answer engines using evidence, user value, and technically correct implementation. Separate observed facts from assumptions and recommendations.

## Establish the assignment

Identify the site, business model, audience, markets, languages, conversion goals, technical stack, and available evidence. Confirm whether the work is an audit, strategy, implementation, investigation, content deliverable, or measurement plan.

Use supplied analytics, Search Console, crawler exports, keyword data, backlink data, and business context when available. Never fabricate volumes, difficulty, traffic, rankings, backlinks, citations, competitors, or performance results. Label estimates and proxies.

## Route to the required guidance

- For crawling, indexing, rendering, canonicals, performance, sitemaps, robots, redirects, or migrations, read [references/technical-seo.md](references/technical-seo.md).
- For keyword research, intent, information architecture, content briefs, on-page optimization, or content quality, read [references/keywords-and-content.md](references/keywords-and-content.md).
- For JSON-LD and rich-result eligibility, read [references/structured-data.md](references/structured-data.md).
- For local, international, or ecommerce work, read [references/specialized-seo.md](references/specialized-seo.md).
- For internal links, backlinks, digital PR, or authority analysis, read [references/authority-and-links.md](references/authority-and-links.md).
- For AI Overviews, answer engines, citations, entities, `llms.txt`, or crawler readiness, read [references/geo-and-aeo.md](references/geo-and-aeo.md).
- For analytics, Search Console, experiments, forecasting, prioritization, or reporting, read [references/measurement-and-reporting.md](references/measurement-and-reporting.md).
- Before completing a substantial audit or implementation, read [references/quality-gates.md](references/quality-gates.md).

## Work from evidence

Prefer primary sources and direct measurements: rendered pages, HTTP responses, crawl data, source code, Google Search Central documentation, schema.org, performance tooling, first-party analytics, and verified platform exports. Third-party metrics are directional and must retain their source and date.

For each finding, record:

1. evidence and affected scope
2. user and search impact
3. likely cause
4. recommended change
5. priority, effort, dependencies, and validation method

Do not treat every checklist item as a defect. Prioritize issues that block discovery, indexing, comprehension, trust, usability, or conversion.

## Implement safely

Inspect the framework and existing conventions before editing. Prefer reusable fixes at templates, components, content models, or configuration layers. Preserve valid canonicals, redirects, metadata, structured data, analytics, and localization behavior.

Do not deploy, submit URLs, disavow links, change production settings, or modify external accounts unless the user requests that action and the environment authorizes it.

## Finish with validation

Re-crawl or re-render affected pages when possible. Verify response codes, indexability, canonical targets, metadata, structured data, internal links, sitemap and robots behavior, responsive rendering, and performance-sensitive changes. Report verified results, remaining risks, unavailable data, and the next measurement point.
