# Frontend Evidence Architecture Audit

Use this reference during a full SEO + GEO audit when the website is a product, service, platform, ecommerce, manufacturing, education, regulated, or local-service site with a meaningful buyer journey.

This framework was distilled from public patterns observed across Promptwatch, Semrush, Profound, Peec AI, Ahrefs, SE Ranking, AirOps, Writesonic, Conductor, and AthenaHQ. The patterns are evidence, not mandatory templates.

## Core Question

Can a search engine, AI system, analyst, and buyer all:

1. find the page,
2. understand the entity and offer,
3. extract a direct answer,
4. verify the claim,
5. compare options,
6. understand fit and limits,
7. take the correct next action?

## Relationship To The Six Audit Layers

| Audit layer | Frontend evidence question |
|---|---|
| Technical SEO | Is the content crawlable, indexable, fast enough, canonical, mobile-friendly, and accurately represented by metadata/schema? |
| On-page SEO | Does each important page resolve one stable buyer decision with sufficient depth and internal links? |
| GEO Readiness | Are direct answers, self-contained passages, facts, tables, definitions, fit, limits, and visible FAQs extractable? |
| Trust / EEAT / Entity | Do claims map to cases, reviews, original data, credentials, policies, authors, company facts, or third-party proof? |
| Off-site Mentions | Do external profiles, media, reviews, communities, partners, and directories repeat the same entity and claim set? |
| Platform Fit | Can ChatGPT, Perplexity, Gemini, Google AI, Copilot, and other relevant surfaces retrieve and use the right assets? |

## Twelve Site Layers

Mark each layer `strong`, `weak`, `fragmented`, `missing`, or `not applicable`.

1. Entity home: homepage, about, contact, stable company facts.
2. Product/category: products, services, capabilities, collections.
3. Audience/use case: role, industry, application, scenario.
4. Workflow/integration: setup, compatibility, integrations, delivery process.
5. Pricing/value: price, package, quote logic, TCO, value explanation.
6. Comparison/alternatives: versus, alternatives, shortlist, build-vs-buy.
7. Risk/trust: security, compliance, quality, warranty, return, legal, safety.
8. Proof: cases, reviews, references, certifications, examples, samples.
9. Research/data: original datasets, benchmarks, methods, calculators, reports.
10. Education: academy, glossary, guides, webinars, buyer education.
11. Support/docs: documentation, API, help center, onboarding, service support.
12. Conversion: trial, demo, quote, booking, consultation, purchase, contact.

Do not penalize a site for missing an optional layer when it does not fit the business model.

## Homepage Checks

- The first viewport states the literal category or offer.
- The primary buyer and outcome are understandable in five seconds.
- The actual product, service result, facility, product object, campus, practitioner, or other real subject is visible.
- Feature language maps to buyer decisions instead of internal module names.
- Major claims link to proof.
- Pricing/procurement, comparisons, trust, cases, docs/support, and conversion are discoverable.
- Mobile preserves the same decision path without hidden or overflowing content.
- One primary CTA is clear; secondary CTA has lower commitment.

## Decision Page Checks

For product, service, pricing, comparison, solution, integration, trust, and proof pages:

- one primary buyer decision,
- direct answer near the beginning,
- product/service facts,
- evidence and sources,
- comparison where relevant,
- best fit and not-fit conditions,
- implementation or delivery path,
- FAQ derived from real buyer questions,
- related internal links,
- appropriate conversion action,
- owner and freshness trigger.

## Claim-To-Proof Checks

For every material claim, record:

- exact claim,
- approved wording,
- visible source URL or document,
- scope and exceptions,
- last verified date,
- owner,
- whether third-party validation exists.

Flag:

- unsupported superlatives,
- customer counts that disagree across pages,
- pricing that differs across landing pages and docs,
- product facts that conflict with schema or llms.txt,
- case metrics without baseline, period, method, or caveat,
- certifications or logos without verification links.

## Frontend Pattern Library

Use patterns selectively:

- Promptwatch: connected product, data, comparison, docs, free-tool, and case-study evidence system.
- Semrush: free checker and existing-product ecosystem.
- Profound: interactive agent/report and enterprise research authority.
- Peec AI: simple positioning, public pricing, analytics focus, and strong case research.
- Ahrefs: data-scale proof, zero-setup preview, academy, and cross-channel index.
- SE Ranking: low-friction trial and exportable competitor checker.
- AirOps: detailed operational case studies and human-reviewed execution workflows.
- Writesonic: prioritized content, citation, and technical action center.
- Conductor: enterprise system of record, governance, and full SEO/AEO lifecycle.
- AthenaHQ: action-first presentation, free audit, answer hub, and review proof.

Before recommending a pattern, confirm that:

1. the target buyer asks the corresponding question,
2. the business can maintain the asset,
3. the pattern supports trust, conversion, or a stable commercial decision,
4. an existing page cannot solve the gap more efficiently,
5. the recommendation will not create thin or duplicate pages.

## Directional Score

This score measures site readiness, not predicted AI ranking.

| Dimension | Points |
|---|---:|
| Category and entity clarity | 10 |
| Buyer-decision coverage | 15 |
| Evidence and trust | 15 |
| Answer extractability | 10 |
| Architecture and discoverability | 10 |
| Conversion continuity | 10 |
| Technical and crawler delivery | 10 |
| Role, region, and localization fit | 5 |
| Operations and freshness | 5 |
| UX, accessibility, and responsive clarity | 10 |

Interpretation:

- `90-100`: evidence architecture is a competitive asset.
- `75-89`: strong foundation with material decision gaps.
- `60-74`: content exists, but evidence or journey is fragmented.
- `<60`: not yet reliable as a buyer-decision source.

## Output Table

| Site layer | Status | Buyer question | Observed URLs | Evidence quality | Main gap | Priority | Recommended page/module | Verification |
|---|---|---|---|---|---|---|---|---|

Every material recommendation should name the page or module to change. Avoid generic advice such as “add more content”, “improve EEAT”, or “use schema”.
