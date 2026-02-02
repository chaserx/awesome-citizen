# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an "awesome list" repository - a curated collection of civic engagement resources (voter registration, election data, government APIs, etc.). It contains no executable code; the entire project is markdown documentation.

## Repository Structure

- `README.md` - The main curated list of resources, organized by category (Elections, Federal branches, Whistleblowers)
- `CONTRIBUTING.md` - Guidelines for adding new resources
- `code-of-conduct.md` - Contributor Covenant Code of Conduct

## CI/CD

The repository uses a GitHub Actions workflow (`.github/workflows/ci.yml`) that runs weekly to check for broken links:

```bash
# The link checker runs automatically via lychee-action
# To manually trigger, use workflow_dispatch in GitHub Actions
```

If broken links are found, the workflow automatically creates a GitHub issue with the report.

## Contribution Guidelines

When adding new resources:
- Use format: `[Resource Name](link)` with a brief description
- Add links to the bottom of the relevant category
- Use AP-style title casing
- PRs must have descriptive titles (not "Update readme.md")
- One suggestion per PR

## AI-Assisted Contributions

See [AI_CONTRIBUTIONS.md](AI_CONTRIBUTIONS.md) for guidance on using AI tools when contributing.
