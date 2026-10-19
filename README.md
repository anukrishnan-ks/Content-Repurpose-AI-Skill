# Content Repurposer

A Claude skill that turns one blog post, article or transcript into ready-to-post
versions for LinkedIn, Instagram (caption + carousel) and X (post + thread).

## Install (Claude Code)

```bash
claude plugin marketplace add anukrishnan-ks/content-repurposer-marketplace
claude plugin install content-repurposer@content-repurposer-marketplace
```

Or inside a Claude Code session:

```
/plugin marketplace add anukrishnan-ks/content-repurposer-marketplace
/plugin install content-repurposer@content-repurposer-marketplace
```

## Use

Paste an article **or a link to one** and say "Repurpose this for social media", or run
`/content-repurposer:content-repurposer`.

## Update

Bump `version` in `plugins/content-repurposer/.claude-plugin/plugin.json` and push.

## Other AI tools

The instructions live in
`plugins/content-repurposer/skills/content-repurposer/SKILL.md`. Paste them into a
ChatGPT Custom GPT, a Gemini Gem, or any tool that reads SKILL.md files.

## Test locally

From `plugins/content-repurposer/`:

```bash
claude plugin validate .                         # check files and format
claude --plugin-dir .                            # try it by hand in a session
claude plugin eval . --judge-model sonnet --allow-tools WebFetch   # run the automatic tests in evals/
```
