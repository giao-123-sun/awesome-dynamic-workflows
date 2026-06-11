# Contributing to Awesome Dynamic Workflows

We welcome contributions! This list follows the awesome-list presentation conventions.

## How to Add an Entry

1. Open a pull request adding the entry to the appropriate category and subcategory in README.md.
2. Ensure the entry follows the standard item format:
   - **[Project Name](URL)** — Short description. `License` `starN` `Language`
3. Include the following inline metadata in backtick tags:
   - License (e.g., MIT, Apache-2.0, AGPL-3.0)
   - Star count using the `starN` convention (e.g., `star1.5k`, `star35`)
   - Primary implementation language (e.g., Python, Go, TypeScript, Rust)
4. If adding a new category or subcategory, provide a justification in the PR.
5. Update `data/projects.json` if the project is a tool, framework, or library.
6. Ensure the entry includes a reason for inclusion — call out the specific dynamic workflow pattern.

## Quality Standards

- **Relevance**: The project must relate to dynamic workflows for AI agents, not static pipeline automation or single-agent chatbots.
- **Open Source**: Prioritize actively maintained projects with clear open-source licenses. Proprietary tools may be listed if they significantly advance the ecosystem.
- **Maturity**: Evidence of real use (GitHub stars, production deployment, peer-reviewed publications) is a plus but not required for promising research.
- **Documentation**: The project should have a README or equivalent that explains the dynamic workflow pattern.
- **Anti-patterns**: Do not add simple task queues, single-agent chatbots, proprietary SaaS-only products, abandoned projects, or static workflows without runtime adaptation.

## Formatting Guidelines

- **Item line**: Use the standard format with backtick metadata tags at the end.
- **Descriptions**: Keep under 120 characters. Start with the pattern, end with the value proposition.
- **Star counts**: Use `star` prefix with `k` for thousands (e.g., `star1.5k`, `star34k`). Use raw numbers for under 1000 (e.g., `star35`, `star634`).
- **Internal links**: Use relative paths (e.g., `data/industry-use-cases.md`).
- **Subcategories**: Place entries in the most specific subcategory. If none fits, add to the parent category with a justification.

## Review Process

- Maintainers review PRs for fit, quality, formatting, and accuracy.
- They may request changes, source verification, or clarification.
- Once approved, the entry is merged. PRs that do not follow the format or quality standards may be closed without merge.

## Code of Conduct

Be respectful and constructive. This is a community resource.
