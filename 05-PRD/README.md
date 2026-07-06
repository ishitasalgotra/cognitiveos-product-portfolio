# 📄 Product Requirements Document (PRD)

# Cognitive OS

**Version:** 1.0

**Product Manager:** Ishita Salgotra

**Status:** MVP

**Last Updated:** July 2026

---

# Executive Summary

Cognitive OS is an AI-powered personal knowledge management platform that helps students and researchers organize, retrieve, and connect knowledge intelligently. The platform combines semantic search, note organization, tagging, and knowledge graph visualization into a unified workspace, enabling users to retrieve information using concepts instead of exact keywords.

The MVP focuses on solving the problem of fragmented knowledge by providing a centralized and intelligent knowledge management experience.

---

# Problem Statement

Students and researchers consume information from lectures, PDFs, articles, books, websites, and personal notes.

This information is usually scattered across multiple applications.

As the amount of information increases:

- Finding previous notes becomes difficult.
- Keyword search becomes unreliable.
- Users forget where information was stored.
- Relationships between ideas are difficult to visualize.

As a result, users spend more time searching than learning.

---

# Goal

Build an AI-powered knowledge platform that allows users to:

- Organize notes
- Retrieve information using semantic search
- Connect ideas visually
- Improve long-term knowledge retention

---

# Success Criteria

The MVP will be considered successful if users can:

- Find notes significantly faster than traditional keyword search.
- Build interconnected knowledge using graphs.
- Organize information within a single workspace.

---

# Target Users

## Primary

- College Students
- Researchers

## Secondary

- Professionals
- Lifelong Learners

---

# User Pain Points

| Problem | Impact |
|----------|---------|
| Notes scattered | Information loss |
| Keyword search | Difficult retrieval |
| Too many folders | Poor organization |
| No visualization | Hard to connect ideas |
| Multiple applications | Context switching |

---

# Proposed Solution

Cognitive OS combines

- AI Semantic Search
- Knowledge Graph
- Dashboard
- Note Management
- Tag Organization
- JWT Authentication

into one intelligent workspace.

---

# MVP Features

## User Authentication

Users can securely create accounts and log in.

Priority: High

---

## Dashboard

Personalized workspace showing recent notes and quick actions.

Priority: High

---

## Notes

Create

Edit

Delete

Search

Priority: High

---

## Semantic Search

Users search using concepts rather than keywords.

Priority: High

---

## Knowledge Graph

Visual representation of relationships between notes.

Priority: High

---

## Tags

Categorize notes for easier organization.

Priority: Medium

---

# User Stories

### Authentication

As a student,

I want to securely log in,

So that my notes remain private.

---

### Notes

As a student,

I want to create notes,

So I can organize my learning.

---

### Semantic Search

As a researcher,

I want to search by concept,

So I don't need to remember exact keywords.

---

### Knowledge Graph

As a researcher,

I want to visualize relationships,

So I can discover hidden connections.

---

### Tags

As a user,

I want to organize notes using tags,

So I can retrieve related information quickly.

---

# Functional Requirements

### Authentication

- User Signup
- Login
- JWT Authentication

---

### Notes

- Create
- Read
- Update
- Delete

---

### Search

- Semantic Search
- Keyword Search
- Tag Search

---

### Dashboard

- Recent Notes
- Quick Search
- Statistics

---

### Knowledge Graph

- Interactive visualization
- Connected notes
- Zoom and pan

---

# Non-functional Requirements

- Secure authentication
- Fast search response
- Responsive UI
- Mobile-friendly
- Scalable backend

---

# Out of Scope (MVP)

The following features are intentionally excluded:

- Team Collaboration
- AI Note Generation
- Voice Notes
- OCR
- Mobile App
- Real-time Editing

---

# Success Metrics

## North Star Metric

Knowledge Retrieval Success Rate

---

## Supporting Metrics

- Daily Active Users
- Weekly Active Users
- Note Creation Rate
- Search Success Rate
- Average Session Duration
- User Retention
- Knowledge Graph Usage

---

# Risks

| Risk | Mitigation |
|------|------------|
| Poor search quality | Improve embeddings |
| Low adoption | Conduct user interviews |
| Slow graph rendering | Optimize graph loading |
| User confusion | Simplify onboarding |

---

# Release Plan

## Sprint 1

- Authentication
- Dashboard
- Notes

---

## Sprint 2

- Semantic Search
- Tags

---

## Sprint 3

- Knowledge Graph
- Dashboard Improvements

---

# Future Enhancements

- AI Chat Assistant
- AI-generated Summaries
- PDF Import
- Voice Notes
- Flashcards
- Mobile App
- Team Collaboration
- Chrome Extension

---

# Open Questions

- Should AI summaries be part of the free plan?
- Should users share knowledge graphs?
- Should OCR be included in the next release?
- Which feature should be prioritized after MVP?
