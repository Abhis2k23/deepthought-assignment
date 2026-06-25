# Research Prompts and Notes

## Tools Used

- Web search for company discovery
- Company websites for product/location/certification evidence
- Screener for listed-company revenue and public market context
- AI assistant for structuring the CSV, applying the scoring rubric, and identifying false positives

No scraping script was used for this draft. The process was manual screening plus direct website checks.

## Main Research Prompts Used

1. Find Ahmedabad performance-chemicals manufacturers in dyes, pigments, resins, textile auxiliaries and water-treatment chemicals.
2. For each company, verify whether it is a producer and whether its operations are in the Ahmedabad cluster.
3. Score each company using DeepThought's E1/E2 and C3-C8 Federer scoring rubric.
4. Flag auto-disqualifiers: revenue above Rs.500Cr, subsidiary/acquired ownership, no Ahmedabad operational presence, stale/no website, or service/trading model.
5. Create concise personalization hooks based on specific evidence rather than generic claims.

## Quality Rule Followed

When a company looked relevant but evidence was weak, I marked it as `Backup` or `Do not use` instead of pretending it was a strong fit. This matches the assignment's emphasis on evidence discipline and ICP judgment.
