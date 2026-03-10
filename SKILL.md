---
name: seo-geo-audit-skill
description: Run a unified SEO and GEO audit for a website, page, or domain. Use when the user asks for a full SEO audit, GEO audit, AI visibility review, EEAT review, entity audit, authority audit, or wants one prioritized report that combines technical findings, content quality, trust signals, and AI citation readiness.
metadata:
  author: GEO-SEO
  version: "1.0.4"
  homepage: https://github.com/GEO-SEO/seo-geo-audit
  primaryEnv: SERPAPI_API_KEY
  requires:
    env:
      - SERPAPI_API_KEY
    bins:
      - python3
---

# SEO GEO Audit Skill

Use this skill to produce one audit that covers both search performance and AI visibility.

## Overview

Use this skill when you need one audit that combines technical SEO, content quality, trust, entity clarity, and AI visibility into a single prioritized output.

## Best For

- brands and SaaS teams that need one shared audit across SEO and GEO
- founders or operators who want a management-ready summary, not a pile of raw issues
- agencies that need a repeatable audit structure across multiple clients
- SEO teams that want to connect technical debt, content quality, and AI visibility in one workflow

## Start With

```text
Run a full SEO and GEO audit for https://example.com
```

```text
Audit this homepage in boss mode: https://example.com
```

```text
Give me an operator-style SEO GEO audit with P0, P1, and P2 actions
```

## External Access And Minimum Credentials

This audit can run with direct page access only, but some environments may also use optional search or crawl integrations.

- `SERPAPI_API_KEY`: optional for broader search visibility checks or search-result enrichment
- `python3`: optional helper tooling in environments that pair this skill with local audit scripts

If no external API is configured:

- continue with direct page and site observations
- state clearly what was observed versus what was not verified
- do not imply access to search-console, private crawl logs, or third-party datasets unless the user provided them

## Access Policy

This audit can run without private integrations.

- search-result enrichment is optional, not required
- local helper tooling is optional, not required
- do not claim access to Search Console, analytics, server logs, private crawlers, or proprietary datasets unless the user explicitly provides them
- when data is missing, mark it as `Not verified` and continue from observable evidence

This skill is designed for three common use cases:

- `Homepage audit`: quick diagnosis for a single URL
- `Site audit`: broader review across key templates and pages
- `Domain visibility audit`: strategic review including entity and authority signals

## What This Skill Covers

1. Technical SEO
   - crawlability
   - indexability
   - performance and rendering
   - security and trust headers
   - schema and metadata
   - mobile and accessibility risks

2. On-page SEO
   - title, meta description, headers
   - search intent alignment
   - content depth and structure
   - internal linking
   - media optimization

3. GEO and AI visibility
   - answer-first formatting
   - extractability and quotability
   - semantic clarity
   - AI crawler access signals
   - machine-readable brand and content signals

4. Trust, entity, and authority
   - author and editorial transparency
   - about, contact, and policy signals
   - organization identity consistency
   - entity disambiguation
   - third-party credibility and authority indicators

## Workflow

1. Define the scope.
   - single page
   - limited site crawl
   - domain-level strategic review

2. Start with the observable baseline.
   Collect factual findings from live pages, crawl data, page source, rendered output, and any available audit tooling.

   Recommended crawl presets:
   - single page: one-page diagnostic mode
   - fast site pass: capped multi-page sample for template-level review
   - broader site audit: larger sample for structural review
   - deeper review: larger crawl cap with heavier performance/rendering analysis

   Important: this workflow is page-capped rather than fixed-depth. It follows valid internal links until the configured page cap is reached.

3. Separate evidence from judgment.
   Label each item as:
   - `Observed`
   - `Assessment`
   - `Not verified`

4. Review the site in layers.
   - technical layer
   - on-page/content layer
   - GEO layer
   - entity/authority layer

5. Prioritize actions.
   - `P0`: blockers, trust failures, indexing failures, major performance issues
   - `P1`: meaningful ranking and citation improvements
   - `P2`: optimization and scale work

6. Present the result in the right audience mode.
   - `Boss mode`
   - `Operator mode`
   - `Specialist mode`

## Output Rules

- If the user writes in Chinese, answer in Chinese unless asked otherwise.
- Always begin with a short executive summary.
- Keep technical facts and strategic recommendations distinct.
- Do not invent data for backlinks, Search Console, server logs, or AI citation share.
- Mark unavailable inputs as `Not verified`.

## Audience Modes

### Boss mode

Use when the user asks for `老板版`, executive summary, or management briefing.

- short
- business impact first
- minimal jargon
- no long issue dumps

Read `references/output-template-zh-boss.md` before writing.

### Operator mode

Use when the user wants a practical roadmap.

- balanced detail
- clear priorities
- implementation-oriented language

Read `references/output-template.md` before writing.

### Specialist mode

Use when the user wants deep analysis.

- include assumptions
- include validation gaps
- include section-level scoring logic

Read `references/scoring-framework.md` before writing.

## Minimum Deliverable

Every audit should include:

- scope
- overall technical view
- content and GEO view
- entity and authority view
- top priorities
- missing data and validation notes

## References

- `references/scoring-framework.md`
- `references/output-template.md`
- `references/output-template-zh-boss.md`
