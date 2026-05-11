# Contributing to Awesome NUMA

Thanks for helping improve this NUMA resource list. This repository is a
curated Markdown index, so contributions should keep the list accurate,
readable, and useful for people building NUMA-aware software.

## Setup

1. Fork the repository and clone your fork.
2. Create a branch for your change:

   ```bash
   git checkout -b docs/update-numa-resource
   ```

3. Edit `README.md` or supporting documentation.
4. Preview the Markdown locally before opening a pull request.

No build step is required for normal documentation updates.

## What to Contribute

Good contributions include:

- NUMA libraries, bindings, profilers, allocators, schedulers, and benchmarks.
- Corrections for stale project names, moved repositories, or broken links.
- Shorter, clearer descriptions for existing entries.
- New sections when a topic has multiple high-quality resources.

Avoid adding:

- Affiliate links, promotional copy, or duplicated entries.
- Projects that are unrelated to NUMA-aware development.
- Links that do not resolve or point only to abandoned placeholder pages.

## Entry Style

Use the existing list format:

```markdown
- [Project Name](https://example.com/project) - Short, factual description
```

Keep descriptions concise and neutral. Mention the language, platform, or
special NUMA capability when it helps readers choose between tools.

## Validation

Before opening a pull request, run these checks where possible:

```bash
git diff --check
```

Also manually verify that any new or changed links open successfully. For
larger link updates, `curl -I <url>` is enough to confirm that the target
responds.

## Pull Request Guidelines

When opening a pull request:

- Explain what changed and why.
- List any links you added, removed, or fixed.
- Note how you checked the Markdown or links.
- Keep unrelated formatting changes out of the same PR.

Small, focused pull requests are easier to review and merge.
