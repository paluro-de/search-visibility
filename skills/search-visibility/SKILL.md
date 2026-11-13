---
name: search-visibility
description: Audit or improve a website's technical SEO, organic search performance, and visibility in AI answers (AEO, GEO, AI SEO). Use for indexing and crawl issues, page metadata, international SEO, structured data, search migrations, or audits of brand mentions and citations in answer engines. App store listings and paid search have their own workflows.
---

# Search visibility

Start with the target site or repository, the audience and market, and the outcome the user wants. Identify the pages and search surfaces that matter. Read existing launch, migration, editorial, and crawler policies before proposing changes. Clarify only facts that affect the scope or could change which content becomes public or indexable.

Choose the relevant track. Use both for a broad audit. For a precise task, check the affected pages and the dependencies of the change.

## Technical and on-page SEO

1. Sample representative URLs by page template and locale. Include the homepage, high-value pages and any affected variants. Label the environment. Use the deployed response and rendered mobile page for a live audit. Treat repository evidence as proposed or configured behavior until verified on a running site.
2. For pages that should be discoverable, check final HTTP status and redirects, crawl rules, `noindex` and `X-Robots-Tag`, canonical targets, internal links, and sitemap inclusion. Compare the source response with the rendered page when JavaScript or templates can change what appears. Use URL Inspection or equivalent owner data when available to distinguish the published directives from a search engine's actual index and selected canonical. Keep public landing pages, staging environments, and private routes separate.
3. Align each priority page with a real search intent. Check its title, main heading, visible answer, useful internal links, and distinct value compared with competing or duplicate pages. Fix the underlying answer before editing a snippet. For multilingual sites, check each canonical and reciprocal `hreflang` cluster where relevant. For migrations, map priority old URLs to equivalent new pages and check redirects, internal links, canonicals and sitemaps together.
4. Add or correct structured data where the visible page supports it and the target search engine documents a relevant feature. Validate syntax and eligibility separately. For performance concerns, distinguish field metrics from local or lab measurements. Use [platform references](references/platforms.md) for current implementation and measurement details.

## AI answers, AEO and GEO

1. Verify that target pages can be found and read. Review search discovery, user-triggered retrieval and training policies separately using each provider's current documentation. Compare declared crawler rules with known server or CDN behavior when evidence is available. Changing crawler policy can affect an entire site, so establish the intended scope before editing it.
2. Build a short set of buyer or support questions people actually ask. Include a mix of unbranded needs, comparisons, and branded facts when relevant. Run the same prompts on each available target surface. Record the date, language, region, search mode, exact prompt, whether the brand was mentioned, whether it was recommended, cited URLs, and whether key facts were accurate. Repeat meaningful observations across runs and keep unavailable surfaces distinct from runs with no citation.
3. Trace each incorrect or missing fact to the best page to supply it. Improve visible product facts, pricing or availability details, useful comparisons, original evidence and clear attribution where they serve readers. Keep source material tied to claims and preserve dates, limitations and context. Treat machine-readable extras such as `llms.txt` as experiments with a defined audience and success measure. Check platform documentation before calling anything a requirement.

## Prioritize and verify

Lead with the issues that affect the most valuable eligible pages or questions. For each material finding, give the URL or template, observed evidence, recommended change, and how to verify it. Distinguish confirmed findings from hypotheses and report missing data. Make scoped, reviewable edits when asked. Check the affected URL or template before and after, including neighboring pages when a shared rule changes. Describe any validation that needs deployment or recrawling.

Compare equivalent time windows, locales and page groups when measuring results. Track indexing, search clicks or impressions, citation and answer accuracy, and business outcomes as separate measures. Record launches, seasonality and other changes that can explain a shift. Avoid claiming that a citation, markup change or prompt sample caused a traffic or conversion change without evidence.
