# Knowledge Base Governance Policy

**Last updated:** 2025-01 · **Owner:** Documentation Systems Lead · **Version:** 1.0

---

## Purpose

This policy defines the ownership model, roles, quality standards, and editorial guidelines that govern the knowledge base. Good governance makes a KB trustworthy — and a trustworthy KB gets used.

---

## Governance Principles

1. **Every article has one owner.** Shared ownership means no ownership. If multiple teams contribute to an article, one team is designated the owner.
2. **The Documentation Systems Lead is the final decision-maker** on structure, taxonomy, and editorial standards. Content accuracy decisions belong to SMEs.
3. **Process should be as light as possible** while still ensuring quality. Bureaucracy that slows contribution kills the KB.
4. **Users are the ultimate judges.** Feedback mechanisms and usage data inform governance decisions more than internal opinion.

---

## Roles & Responsibilities

### Documentation Systems Lead
- Owns the overall architecture, taxonomy, and governance framework
- Conducts editorial review on all new articles
- Manages the approved tag list and category hierarchy
- Monitors KB health metrics and reports quarterly
- Resolves disputes about structure, taxonomy, or standards

### Content Owners
- One assigned owner per article (individual, not team)
- Responsible for accuracy, timeliness, and review cadence compliance
- Initiates SME review when content changes
- Responds to user feedback on their articles within 5 business days

### Subject Matter Experts (SMEs)
- Provide technical accuracy review on articles in their domain
- Available for consultation during content creation
- Notified of articles in their domain that are flagged for review

### Contributors
- Anyone may propose new content or flag inaccuracies
- Contributors without owner status submit changes via pull request (docs-as-code) or via the feedback form
- Contributions go through normal review before publishing

---

## Quality Standards

All published articles must meet the following standards before going live:

### Accuracy
- [ ] All procedures have been tested and verified by the SME
- [ ] Screenshots and examples reflect the current product state
- [ ] No references to deprecated features without clear notation

### Completeness
- [ ] Article covers its stated scope fully
- [ ] Related articles are linked
- [ ] Prerequisites are stated where applicable

### Clarity
- [ ] Written in plain language appropriate for the target audience
- [ ] No unexplained jargon or acronyms (or all terms are linked to Glossary)
- [ ] Steps are numbered and actionable

### Metadata
- [ ] Owner assigned
- [ ] Review date set
- [ ] Section/topic classification correct
- [ ] Tags applied per [Taxonomy & Tagging Standards](./taxonomy-and-tagging.md)

---

## Editorial Guidelines

### Voice & Tone
- **Second person** ("you") for instructional content; third person for reference content
- **Active voice** throughout
- **Direct and plain** — write for clarity, not to impress
- **Neutral and professional** — not casual, not robotic

### Formatting
- Use headers (H2, H3) to break up content — never skip levels
- Use numbered lists for sequential steps
- Use bullet lists for non-sequential items (maximum 7 bullets before considering a table or restructure)
- Use tables for comparative or reference information
- Bold key terms and UI elements (e.g., click **Save**)
- Use code formatting for all code snippets, commands, and system values

### What Not to Do
- Don't write marketing copy in the KB — users are here to solve problems, not be sold to
- Don't bury the lead — state what the article does in the first two sentences
- Don't use "simply," "just," "easy," or "obviously" — these words are condescending when a user is stuck
- Don't publish incomplete articles — a stub with a "coming soon" message is worse than no article

---

## Feedback & Continuous Improvement

Every article includes a feedback mechanism ("Was this article helpful?"). Feedback is reviewed monthly by the Documentation Systems Lead.

### Feedback Response Protocol

| Feedback Type | Response Time | Action |
|---|---|---|
| Article flagged as inaccurate | 2 business days | Owner investigates and updates or escalates to SME |
| Article flagged as incomplete | 5 business days | Owner reviews and expands or creates linked article |
| Article rated unhelpful (no comment) | Monthly review | Owner reviews usage data and considers rewrite |
| Suggestion submitted | 10 business days | Owner acknowledges and determines if action is needed |

---

## KB Health Metrics

The Documentation Systems Lead reports quarterly on:

- Total articles by status (Published, Needs Review, Deprecated)
- % of articles with overdue reviews
- Average feedback rating by section
- Top 10 articles by page views
- Top 10 search queries with no results (content gap indicator)
- Articles flagged for inaccuracy in the quarter

---

## Policy Review

This governance policy is reviewed annually by the Documentation Systems Lead and updated as the KB evolves.

---

## Related Documents

- [KB Architecture Overview](./kb-architecture-overview.md)
- [Taxonomy & Tagging Standards](./taxonomy-and-tagging.md)
- [Content Lifecycle](./content-lifecycle.md)
