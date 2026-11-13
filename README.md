# Search Visibility

Search Visibility is an agent skill for improving how a website is found in organic search and represented in AI answers. It combines technical and on-page SEO with answer engine optimization (AEO), generative engine optimization (GEO), and AI SEO.

Use it to diagnose indexing problems, review metadata and structured data, check a site migration, or measure when AI answers mention, recommend, or cite your brand. It helps you document the evidence, prioritize changes, and verify results. The skill is written in Markdown and includes references to official platform documentation.

## Install

Copy the [skill folder](skills/search-visibility) into your agent's personal skills directory. Keep the folder intact so that `search-visibility/SKILL.md` and its `references` folder are available together. Start a new session after installing.

| Agent | Personal skills directory | Invoke |
| --- | --- | --- |
| Codex | `~/.codex/skills/` | `$search-visibility` |
| Claude Code | `~/.claude/skills/` | `/search-visibility` |
| Google Antigravity | `~/.gemini/config/skills/` | `/search-visibility` |

For a project install, use `.agents/skills/` for Codex and Antigravity or `.claude/skills/` for Claude Code.

## Try it

> Use Search Visibility to audit our public product and pricing pages. Check whether they can be crawled and indexed, then establish a baseline for what available AI search tools say about the product. Cite your evidence and prioritize fixes that we can verify after deployment.
