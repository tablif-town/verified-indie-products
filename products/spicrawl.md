# Spicrawl

- **Site:** [spicrawl.com](https://spicrawl.com/)
- **Topic:** [Developer](../topics/developer.md)
- **Ownership verified:** 2026-11-03

## Quick answers

Each answer comes with the sentence it is based on, quoted from the product's own pages.

### What happens when an account uses all of its monthly credits?

When monthly credits run out, requests fail with a 402 status code. The error response tells you your account's next monthly credit reset date.

> When your credits run out, requests fail with a 402 error that tells you the reset date.

### Does Spicrawl use OAuth to authenticate MCP clients?

No, Spicrawl does not use OAuth for MCP server connections. You authenticate by passing your API key as a Bearer token header.

> OAuth: none (API key only)

### What output formats can Spicrawl return for a fetched URL?

Spicrawl can return web page content as Markdown, JSON, HTML, text, PDF, or screenshots. You specify your desired format in the request payload.

> One API for Markdown, JSON, HTML, text, PDF and screenshots.

### Can Spicrawl crawl a whole website for me?

No. It does not follow links or discover pages, so you send it the exact URLs you want.

> No crawling. Spicrawl does not follow links or find pages. Give the agent the URLs.

### Does the MCP server use OAuth?

No. You connect over Streamable HTTP and send your API key as a Bearer header.

> There is no OAuth.

## Longer reads

- [How to convert web page HTML to markdown for AI models](https://answers.delivery/spicrawl/convert-web-page-html-to-markdown-for-llm)
- [How to scrape a page that loads its content with JavaScript](https://answers.delivery/spicrawl/scrape-javascript-rendered-page-with-an-api)

---

Part of [Verified indie products](../README.md) · [office in Tablif Town](https://tablif.com/town/62843118-3a27-4db3-9658-aade5cdb6ad5)
