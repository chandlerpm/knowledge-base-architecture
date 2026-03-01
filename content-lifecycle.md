# Content Lifecycle

**Last updated:** 2025-01 · **Owner:** Documentation Systems Lead

---

## Purpose

This document defines how knowledge base content is created, reviewed, maintained, and retired. A content lifecycle policy ensures the KB stays accurate, trustworthy, and free of outdated information.

---

## Lifecycle Stages

```
Proposed → In Progress → In Review → Published → Needs Review → Deprecated
```

| Stage | Description |
|---|---|
| **Proposed** | Content gap identified; article stub created with owner assigned |
| **In Progress** | Author is actively drafting |
| **In Review** | Draft complete; undergoing SME and editorial review |
| **Published** | Live and visible to users |
| **Needs Review** | Published article has reached its review date or been flagged |
| **Deprecated** | No longer accurate; removed from navigation, redirected or deleted |

---

## Creating New Content

### Step 1 — Identify the Gap
Content needs are identified through:
- Support ticket analysis (recurring questions with no KB answer)
- Product release notes (new features requiring documentation)
- User feedback on existing articles
- Team requests

### Step 2 — Create a Stub
Before writing, create a stub article with:
- Title (following naming conventions)
- Assigned owner
- Target publish date
- Section/topic classification
- Tags

### Step 3 — Draft
Author writes the article following the [style guide](#style-standards) and [article template](#article-template).

### Step 4 — Review
All new articles go through two review stages:

| Review Type | Reviewer | Focus |
|---|---|---|
| **SME Review** | Subject matter expert | Technical accuracy |
| **Editorial Review** | Documentation Systems Lead | Style, structure, taxonomy |

### Step 5 — Publish
Once both reviews are approved, the author publishes the article and updates its status to **Published**.

---

## Review Cadence

All published articles have a review date. Default review cadences:

| Content Type | Review Cadence |
|---|---|
| Getting Started / Onboarding | Every 6 months |
| How-To Guides | Every 6 months |
| Reference | Every 3 months or with each major release |
| Troubleshooting | Every 6 months |
| Release Notes | No review required (historical record) |

When an article reaches its review date, it is automatically flagged as **Needs Review** in the KB admin panel and assigned to its owner.

---

## Maintaining Existing Content

### Minor Updates
Factual corrections, link fixes, and minor wording changes may be made directly by the article owner without a full review cycle. Changes should be noted in the article's changelog.

### Major Updates
Structural changes, procedure changes, or updates affecting accuracy require an SME review before republishing.

### Product Release Updates
The Documentation Systems Lead maintains a release notes checklist tied to each product release. All articles affected by a release are identified and updated before or on the release date.

---

## Deprecation

An article should be deprecated when:
- The feature or process it describes no longer exists
- It has been superseded by a more current article
- It cannot be brought up to date (e.g., the SME has left and knowledge is unavailable)

### Deprecation Process

1. Owner flags article as **Deprecated**
2. Set up a redirect to the most relevant current article (or to the section landing page if no direct replacement exists)
3. Remove the article from all navigation and section indexes
4. Retain the article in archive for 90 days before permanent deletion

> **Never delete a published article without first setting up a redirect.** Broken links erode user trust and affect search indexing.

---

## Article Template

```markdown
# [Article Title]

**Last updated:** YYYY-MM · **Owner:** [Name or Role] · **Reading time:** ~X minutes

---

## Overview
[1–2 sentence summary of what this article covers and who it's for]

---

## [Main Section]

[Content]

---

## Related Articles
- [Article title](./link)
- [Article title](./link)
```

---

## Style Standards

- Write in second person ("you") for instructional content
- Use active voice
- Keep sentences under 25 words where possible
- Use numbered lists for sequential steps, bullet lists for non-sequential items
- Include a screenshot or diagram for any UI-based procedure with more than 3 steps
- Every article must have a "Last updated" date visible to users

---

## Related Documents

- [KB Architecture Overview](./kb-architecture-overview.md)
- [Taxonomy & Tagging Standards](./taxonomy-and-tagging.md)
- [Governance Policy](./governance-policy.md)
