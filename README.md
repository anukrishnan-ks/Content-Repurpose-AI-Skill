# Content Repurposer

A Claude skill that turns one blog post, article or transcript into ready-to-post
versions for LinkedIn, Instagram (caption + carousel) and X (post + thread).

## Install (Claude Code)

```bash
claude plugin marketplace add YOUR-GITHUB-USERNAME/content-repurposer-marketplace
claude plugin install content-repurposer@content-repurposer-marketplace
```

Or inside a Claude Code session:

```
/plugin marketplace add YOUR-GITHUB-USERNAME/content-repurposer-marketplace
/plugin install content-repurposer@content-repurposer-marketplace
```

## Use

Paste an article and say "Repurpose this for social media", or run
`/content-repurposer:content-repurposer`.

## Update

Bump `version` in `plugins/content-repurposer/.claude-plugin/plugin.json` and push.

## Other AI tools

The instructions live in
`plugins/content-repurposer/skills/content-repurposer/SKILL.md`. Paste them into a
ChatGPT Custom GPT, a Gemini Gem, or any tool that reads SKILL.md files.
