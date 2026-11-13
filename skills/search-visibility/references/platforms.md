# Platform references

Use the official documentation for the surface under review. Check current details before recommending a provider-specific directive, markup type, or reporting feature.

## Search and content

- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide) for crawlable site structure, content and links.
- [Google indexing controls](https://developers.google.com/search/docs/crawling-indexing/block-indexing) for how `noindex` is discovered. Google must be able to crawl a URL to read its `noindex` directive. Use authentication for material that should be private.
- [Google canonicalization](https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls) for aligning redirects, canonical tags and sitemap URLs. Inspect the selected canonical when owner data is available.
- [Google localized versions](https://developers.google.com/search/docs/specialty/international/localized-versions) for reciprocal and self-referencing locale annotations.
- [Google structured data policies](https://developers.google.com/search/docs/appearance/structured-data/sd-policies) for content fidelity and eligibility. A successful syntax check does not establish that a rich result will appear.
- [Google Search Console URL Inspection](https://support.google.com/webmasters/answer/9012289) to interpret live tests and indexed data.

## AI visibility and crawler controls

- [Google AI features and your website](https://developers.google.com/search/docs/appearance/ai-features) and [Google's generative AI search guide](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide). Existing eligibility and SEO practices apply to AI Overviews and AI Mode. These features have no special `llms.txt` or markup requirement. Follow the current reporting documentation when interpreting Search Console metrics.
- [OpenAI crawler documentation](https://developers.openai.com/api/docs/bots) for OAI-SearchBot, GPTBot and ChatGPT-User. These serve different purposes and have distinct controls.
- [Anthropic crawler documentation](https://support.anthropic.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler) for Claude-SearchBot, ClaudeBot and Claude-User.
- [Perplexity crawler documentation](https://docs.perplexity.ai/docs/resources/perplexity-crawlers) for search crawling and user-triggered retrieval. Check controls for each separately.
- [Bing AI Performance](https://blogs.bing.com/webmaster/2026/2/Introducing-AI-Performance-in-Bing-Webmaster-Tools-Public-Preview/) for citation and cited URL reporting on covered Microsoft and partner surfaces. Citation counts measure references to pages. Compare them separately from referrals and conversions.

For a visibility baseline, one observation can use these columns:

| Surface and search mode | Date, region, language | Exact prompt | Brand mentioned | Brand recommended | Cited URLs | Factual accuracy | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |

For a technical issue, record the URL, observed response or index evidence, intended state, and exact recheck. For example, a localized page with a cross-language canonical needs validation of the canonical and locale annotations after deployment, plus an owner-tool check after recrawl.
