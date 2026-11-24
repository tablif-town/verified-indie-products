# Semlith

Local search over your code and documents for AI agents.

- **Site:** [semlith.com](https://semlith.com/)
- **Topic:** [AI and agents](../topics/ai-and-agents.md)
- **Ownership verified:** 2026-11-01

Coding agents make up quotes from PDFs and Office files they cannot open. Semlith is a free, open-source local index of your code and docs that Claude Code, Cursor and Codex search over MCP. In my test, made-up quotes went from 41 of 127 to 0.

## Quick answers

Each answer comes with the sentence it is based on, quoted from the product's own pages.

### Is there a cap on the number of search queries I can run?

No, search queries are unlimited and never metered across any plan.

> Queries are never metered.

### Does Semlith use generative AI models for search retrieval?

No, Semlith does not use any generative model in its retrieval path. Search results are generated strictly from code graph facts, keywords, and vectors.

> There is no generative model in the retrieval path, so the index cannot make anything up.

### How do I connect my AI tools to Semlith?

You can run semlith setup in your terminal to automatically register your local index with supported tools like Claude Code and Cursor.

> It registers Semlith in every client that has a registration command, and semlith setup --register-all also writes the config file for the rest.

### Can the free binary run with no network access at all?

Yes. Its --airgap mode refuses every outbound request, so indexing and search stay on your machine.

> --airgap refuses every outbound request

### What happens on Semlith Cloud if I go over my plan's cap?

Your agents keep answering. You get an email and a banner, and the cap is raised by hand after a conversation.

> Over a cap, agents keep answering. We mail you, show a banner, and raise it by hand after a conversation.

## What it does not do

- It doesn't edit, push, or delete your source code files.

  > Read only — it never pushes, edits or deletes.

- It doesn't use generative AI models to construct retrieval search results.

  > There is no generative model in the retrieval path, so the index cannot make anything up.

## Longer reads

- [How to see what a pull request breaks in other repos](https://answers.delivery/semlith/pull-request-impact-analysis-across-repositories)
- [How to search across multiple git repositories with Claude](https://answers.delivery/semlith/search-across-multiple-git-repositories-with-claude)

---

Part of [Verified indie products](../README.md) · [office in Tablif Town](https://tablif.com/town/bc0796c4-a095-4f2e-aaa6-02103d107c90)
