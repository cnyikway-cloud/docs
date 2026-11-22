# yikway/docs — Technical Documentation

Technical documentation for **Yikway**, an industrial PC manufacturer in Shenzhen, China.
Fanless box PCs, industrial motherboards, panel PCs and edge AI computers. CE/FCC/RoHS certified.

Live site: **https://docs.yikway.com**

## Structure

```
index.html          docs home
guides/             engineering guides (one question per page)
assets/style.css    shared stylesheet
robots.txt          allows AI crawlers (GPTBot, PerplexityBot, ClaudeBot, ...)
llms.txt            machine-readable index for AI assistants
sitemap.xml         submitted to Google Search Console / Bing
CNAME               custom domain docs.yikway.com
.nojekyll           serve files as-is (no Jekyll processing)
```

## How to add a guide

1. Copy any file in `guides/` and keep the structure: answer-first lede, tables, FAQ section, JSON-LD schema.
2. Add the entry to `index.html`, `sitemap.xml` and `llms.txt`.
3. Commit — GitHub Pages redeploys automatically.

## Related projects

Maintained by mason.peng at [Yikway](https://www.yikway.com/).
