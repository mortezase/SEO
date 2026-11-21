# Technical SEO

## Discovery and indexability

Trace representative URLs through DNS and HTTP behavior, redirects, final status, rendered HTML, robots directives, canonical tags, sitemap inclusion, internal links, and pagination or faceting rules. Distinguish crawl blocking from indexing directives.

Check for redirect chains and loops, soft 404s, inconsistent trailing slash or case rules, parameter duplication, orphan pages, conflicting canonicals, non-indexable sitemap URLs, and accidental environment exposure.

`robots.txt` controls crawling, not guaranteed indexing. `noindex` must be crawlable long enough to be observed. Do not recommend blocking resources required to render meaningful content.

## Rendering and JavaScript

Compare initial HTML with rendered output for titles, descriptions, headings, main content, links, canonicals, robots directives, and structured data. Essential content and navigation should not depend on fragile client-only execution when the stack can render them reliably.

## Architecture and migrations

Use stable, descriptive URLs and shallow, intentional internal paths. For migrations, create an old-to-new URL map, preserve valuable content and signals, use direct permanent redirects, update canonicals and internal links, generate clean sitemaps, retain redirects long term, and monitor coverage and traffic by page type.

## Performance and experience

Measure field data when available and lab data for diagnosis. Treat Core Web Vitals as distributions, not a single perfect score. Investigate LCP discovery and server time, INP interaction work, CLS dimension and font issues, unused JavaScript, image delivery, caching, and third-party costs. Do not sacrifice accessibility or primary functionality for synthetic scores.

## Technical deliverables

Include reproducible examples, affected templates or URL patterns, severity, expected outcome, implementation owner, and a verification query or test.
