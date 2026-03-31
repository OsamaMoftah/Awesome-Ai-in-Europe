# Contributing to Awesome Ai-infra Europe+

Thank you for helping build the best resource list for EU AI builders.

## Inclusion criteria

A resource belongs on this list if it meets **all** of the following:

1. **EU-relevant** — it is EU-hosted, EU-funded, EU-regulated, EU-focused, or specifically useful for developers operating under EU law (GDPR, EU AI Act, etc.).
2. **Active** — the project, service, or resource is currently maintained or accessible.
3. **Open or documented** — it either has an open license, or its terms/pricing are clearly published.
4. **Specific** — it does something concrete. "AI for Europe" blog posts with no resources are not included.

## Language for descriptions

Use "resources for" / "tools that help with" — **never** "ensures compliance" or "makes you GDPR-compliant." This list provides pointers to tools and resources; it does not give legal advice.

Correct: `Tool that helps document model risk assessments for EU AI Act requirements.`
Wrong: `Ensures your AI system is EU AI Act compliant.`

## Regulatory dates

If a description mentions an enforcement date or deadline, append:
`(verify current enforcement schedule before acting)`

## Scope fences — what we exclude

- **Commercial-only tools** where a comparable open-source option exists.
- **Non-EU resources** unless they are specifically designed for EU law or multi-jurisdictional use covering the EU.
- **Resources behind paywalls** without a meaningful free tier or open documentation.
- **Inactive projects** (last commit/update > 18 months with no archived status).
- **Self-promotional additions** — if you built the resource, note it clearly and expect extra scrutiny.

## How to submit

### Option A: Issue (for suggestions)

Use the [Add Resource issue template](.github/ISSUE_TEMPLATE/add-resource.md).

### Option B: Pull Request (preferred)

1. Fork the repo.
2. Add your entry to the correct file in `sections/`.
3. Follow the entry format: `- [Name](url) — one-line description.`
4. Add license/openness tag for datasets and models: `\`Apache 2.0\`` / `\`CC-BY-4.0\`` / `\`Open weights\``
5. Run link validation locally: `npx awesome_bot README.md --allow-redirect`
6. Fill out the PR checklist.

## Entry format

```markdown
- [Resource Name](https://example.com) — One-line description of what it does. `[tag]`
```

Tags to use where applicable:
- `[EU-hosted]` — infrastructure physically hosted in the EU
- `[GDPR-DPA]` — has a signed Data Processing Agreement
- `[Open-source]` — source code available
- `[Open weights]` — model weights available
- `[Free tier]` — free access available
- `[Academic]` — academic/research only

## Update cadence

Maintainer reviews PRs weekly. If your PR hasn't been reviewed in 7 days, ping with a comment.

## Code of conduct

Be constructive. Reviews may ask you to revise your description or move your entry to a different section — that's normal.
