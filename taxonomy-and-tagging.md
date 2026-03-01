# Taxonomy & Tagging Standards

**Last updated:** 2025-01 · **Owner:** Documentation Systems Lead

---

## Purpose

This document defines the category hierarchy, tagging system, and naming conventions for the knowledge base. Consistent taxonomy is what makes content findable at scale.

---

## Category Hierarchy

Categories follow a two-level hierarchy: **Section → Topic.**

A third level (subtopic) may be used sparingly for high-volume sections, but deep nesting is discouraged — it creates navigation friction and indicates a content strategy problem, not a taxonomy solution.

### Example Hierarchy

```
How-To Guides (Section)
└── User Management (Topic)
    ├── Inviting team members
    ├── Changing user roles
    ├── Removing users
    └── Managing SSO
```

### Rules

- Every article belongs to exactly one Section/Topic combination
- Topics should contain a minimum of 3 articles; if fewer exist, consider merging the topic or expanding coverage
- Topic names are noun phrases (e.g., "User Management"), not verbs or questions
- Section names never change without a documented migration plan

---

## Tagging Standards

Tags supplement the category hierarchy by enabling cross-cutting discovery. They are not a substitute for good structure.

### Tag Types

| Tag Type | Purpose | Example |
|---|---|---|
| **Feature** | Links content to a specific product feature | `feature:billing`, `feature:api` |
| **Audience** | Identifies the intended reader | `audience:admin`, `audience:developer` |
| **Content type** | Describes the format of the article | `type:tutorial`, `type:reference` |
| **Platform** | Indicates platform-specific content | `platform:web`, `platform:mobile` |

### Tagging Rules

- Every article must have at least one **Feature** tag and one **Content type** tag
- **Audience** tags are required for articles written for a specific role (admin, developer, end user)
- Maximum 6 tags per article — if more are needed, the article may be trying to cover too much
- Tags use lowercase with colons as namespace separators (`feature:billing`, not `Feature: Billing` or `billing`)
- New tags must be approved by the Documentation Systems Lead before use — ad hoc tags create taxonomy drift

### Approved Tag List

Maintained in the KB admin panel under **Settings → Tags**. Do not create tags not on the approved list.

---

## Naming Conventions

### Article Titles

- Use sentence case: "How to invite team members" not "How To Invite Team Members"
- Start How-To articles with a verb: "Configure SSO," "Add a billing contact," "Reset your password"
- Start Reference articles with the subject: "Billing settings reference," "API rate limits"
- Start Troubleshooting articles with the symptom: "Error: 'User not found'," "Dashboard not loading"
- Maximum 60 characters for search display optimization

### URLs / Slugs

- Lowercase, hyphen-separated, no special characters
- Match the article title where possible: "how-to-invite-team-members"
- Never change a published URL without setting up a redirect

### File Names (for docs-as-code workflows)

- Format: `[section]-[topic]-[title].md`
- Example: `how-to-user-management-invite-team-members.md`
- Use hyphens, not underscores or spaces

---

## Glossary Standards

The Glossary lives in the Reference section and defines all product-specific terminology used across the KB.

- Every term used in a specialized way must have a Glossary entry
- First use of a Glossary term in any article should link to its Glossary entry
- Glossary entries follow the format: **Term** — definition in plain language, 1–3 sentences

---

## Related Documents

- [KB Architecture Overview](./kb-architecture-overview.md)
- [Content Lifecycle](./content-lifecycle.md)
- [Governance Policy](./governance-policy.md)
