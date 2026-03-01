# Knowledge Base Architecture Overview

**Last updated:** 2025-01 · **Owner:** Documentation Systems Lead

---

## Purpose

This document defines the structural design of the organization's knowledge base — how content is organized, what sections exist, and the principles guiding those decisions.

---

## Design Principles

### 1. User-Centered Structure
Content is organized around user needs and tasks, not internal org charts or product architecture. A user looking for "how to reset my password" should not need to know which team owns authentication.

### 2. Single Source of Truth
Each piece of information lives in exactly one place. Cross-linking is encouraged; duplication is not. Duplicate content creates maintenance burden and erodes trust.

### 3. Progressive Disclosure
Content is layered — overviews first, detail on demand. Every section has an entry point that serves a first-time reader, with links to deeper content for those who need it.

### 4. Findability Over Completeness
A KB that contains everything but is impossible to navigate is useless. Structure and navigation are treated as first-class concerns, not afterthoughts.

---

## Top-Level Structure

The knowledge base is organized into five top-level sections:

```
Knowledge Base
├── Getting Started
│   ├── Product Overview
│   ├── Account Setup
│   └── Quick Start Guides
├── How-To Guides
│   ├── [Feature Area 1]
│   ├── [Feature Area 2]
│   └── [Feature Area N]
├── Reference
│   ├── API Documentation
│   ├── Glossary
│   └── Configuration Reference
├── Troubleshooting
│   ├── Common Issues
│   ├── Error Messages
│   └── Known Issues & Workarounds
└── Release Notes
    ├── Current Release
    └── Archive
```

---

## Section Definitions

### Getting Started
First-contact content for new users and evaluators. Prioritizes speed to value over comprehensiveness. Articles here should be short, visual where possible, and task-oriented.

**Goal:** Get a new user to their first successful outcome in under 15 minutes.

### How-To Guides
Task-based documentation organized by feature area. Each article answers the question "How do I [specific task]?" Articles should be self-contained, with links to Reference content where deeper context is needed.

**Goal:** Help an existing user accomplish a specific task.

### Reference
Comprehensive, precise, technical documentation. Users come here to look something up, not to learn. Content should be complete, accurate, and consistently formatted.

**Goal:** Answer "What exactly does [this thing] do/mean/accept?"

### Troubleshooting
Symptom-first documentation. Organized around what the user sees (error messages, unexpected behavior) rather than what caused it. Each article should lead to a resolution or a clear escalation path.

**Goal:** Help a user resolve an issue as quickly as possible.

### Release Notes
Chronological record of product changes. See the [Content Lifecycle](./content-lifecycle.md) document for the release notes publication process.

---

## Navigation Design

- **Search** is the primary navigation path for most users. All article titles and metadata must be written with search in mind.
- **Breadcrumbs** appear on every article, showing the full path from the top-level section.
- **Related articles** appear at the bottom of every article, surfacing 3–5 contextually relevant links.
- **Section landing pages** provide a curated index of the most commonly accessed articles in each section, rather than an exhaustive list.

---

## Related Documents

- [Taxonomy & Tagging Standards](./taxonomy-and-tagging.md)
- [Content Lifecycle](./content-lifecycle.md)
- [Governance Policy](./governance-policy.md)
