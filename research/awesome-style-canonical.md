# Awesome List Presentation Patterns: Canonical Lists Study

## Source Lists Studied

- **sindresorhus/awesome** — https://github.com/sindresorhus/awesome
- **awesome-selfhosted/awesome-selfhosted** — https://github.com/awesome-selfhosted/awesome-selfhosted
- **vinta/awesome-python** — https://github.com/vinta/awesome-python
- **avelino/awesome-go** — https://github.com/avelino/awesome-go

---

## 1. Title & Logo

- sindresorhus/awesome: Centered SVG logo + title in div; personal branding + sponsor callout.
- awesome-selfhosted: Simple H1 heading with badge row.
- vinta/awesome-python: Plain heading with link to companion website.
- avelino/awesome-go: Logo right-aligned + title + extensive badge row.

Pattern: Use centered or right-aligned logo only if strong visual identity. Clean H1 otherwise.
Apply: Simple H1 with optional badge row.

---

## 2. Badges

- sindresorhus/awesome: Awesome badge only.
- awesome-selfhosted: Awesome badge + CI status (dead links, unmaintained) + Liberapay badge.
- vinta/awesome-python: No badges in README.
- avelino/awesome-go: Build status, Awesome badge, Slack, Netlify, Track Awesome, Last Commit.

Pattern: Always include Awesome badge. Add CI/status badges. Funding badge optional.
Apply: Awesome badge + CI status + Track Awesome List badge.

---

## 3. Introduction / Description

- sindresorhus/awesome: Short description + links to sub-pages.
- awesome-selfhosted: Paragraph defining self-hosting + links to HTML version and non-free page.
- vinta/awesome-python: Single sentence + link to website.
- avelino/awesome-go: One-liner + contribution call.

Pattern: One or two paragraphs explaining the list scope. Include links to additional resources.
Apply: "A curated list of dynamic workflow frameworks, tools, research, and applications."

---

## 4. Table of Contents

- sindresorhus/awesome: Flat list of category headings.
- awesome-selfhosted: Flat list with sub-categories indented. Uses details/summary collapse for huge list.
- vinta/awesome-python: Grouped by super-category with sub-headings.
- avelino/awesome-go: Collapsible details/summary for enormous TOC; nested sub-categories.

Pattern: Flat ToC for smaller lists, collapsible or grouped for larger lists.
Apply: Use collapsible details ToC with top-level categories and sub-categories if list grows beyond 10 categories.

---

## 5. Category Ordering

- sindresorhus/awesome: Topical logical grouping (Platforms, Programming Languages...).
- awesome-selfhosted: Alphabetical within categories.
- vinta/awesome-python: Thematic groups, alphabetical within each group.
- avelino/awesome-go: Alphabetical within categories.

Pattern: Group by domain/topic. Alphabetical within category avoids bias.
Apply: Thematic groups: Frameworks, Tools & SDKs, Research & Papers, Case Studies, Community. Alphabetize within each group.

---

## 6. Item Formatting

### sindresorhus/awesome (base style):
- [Name](https://github.com/user/repo#readme) - Description.
One link per item, short description after dash, sub-items indented.

### awesome-selfhosted:
- [Name](URL) - Description. ([Source Code](URL)) License Platform/Docker
Rich metadata: name, description, source code link, license, platform tag.

### vinta/awesome-python:
- [name](https://github.com/user/repo) - Short description.
Groups under sub-headings. License and platform not always included.

### avelino/awesome-go:
- [Name](https://github.com/user/repo) - Description. License
Links directly to GitHub, often includes license only.

Pattern: Minimum: [Name](link) - Description. For software/services, add license and platform/deployment info.
Apply: - [Name](GitHub link) - One-line description. License Language/Platform

---

## 7. Contribution Rules

- sindresorhus/awesome: Separate contributing.md with detailed rules and quality gate.
- awesome-selfhosted: In-source contributing section with explicit requirements.
- vinta/awesome-python: Links to CONTRIBUTING.md.
- avelino/awesome-go: In-source contribution call + CONTRIBUTING.md.

Pattern: Have a CONTRIBUTING.md with clear quality thresholds: open source, actively maintained, has README, meets awesome standard.
Apply: Items must be open source (or freely available research), actively maintained, required fields: Name, URL, description, license, category. PR must follow format exactly.

---

## 8. Quality Thresholds

- sindresorhus/awesome: No unmaintained projects; must have clear README; maintainer judgement.
- awesome-selfhosted: Automated CI for dead links and unmaintained projects. Non-free software in separate page.
- vinta/awesome-python: Maintainer selects best-in-class.
- avelino/awesome-go: Automated tests and CI; community PR review.

Pattern: Use CI to auto-check links and last-commit date. Reject projects with no updates in 1+ year unless stable. Separate non-free/proprietary.
Apply: GitHub Action for dead links and freshness check. Must have README. Must be related to dynamic workflows / agent orchestration.

---

## 9. Footer & License

- sindresorhus/awesome: Sponsor section, Ukraine banner, license (CC0-1.0).
- awesome-selfhosted: License section for list itself.
- vinta/awesome-python: No separate footer.
- avelino/awesome-go: Resources section, contribution, license (CC0-1.0).

Pattern: End with resources section, contribution call, and license for the list.
Apply: Resources section, contribution call with link to CONTRIBUTING.md, license MIT or CC0.

---

## 10. Summary of Reusable Patterns for awesome-dynamic-workflows

1. Start small with existing research artifacts. Create initial README with categories: Frameworks, Research Papers, Tooling, Case Studies.
2. Add a "What is a dynamic workflow?" section for context.
3. Use collapsible ToC if list grows.
4. Add automated CI early to prevent link rot.
5. Include a "Non-Free" section for commercial products.
6. Format items consistently: [Name](URL) - Description. License Language/Platform
7. Reference canonical lists for updates: sindresorhus/awesome, awesome-selfhosted, vinta/awesome-python, avelino/awesome-go.

---

## GitHub URLs to Source Lists

- https://github.com/sindresorhus/awesome
- https://github.com/awesome-selfhosted/awesome-selfhosted
- https://github.com/vinta/awesome-python
- https://github.com/avelino/awesome-go
