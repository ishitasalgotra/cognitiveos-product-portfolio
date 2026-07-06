# 🗺️ User Journey & MVP Prioritization

## Objective

Understand how users interact with Cognitive OS from the moment they identify a need to successfully retrieving knowledge.

This journey helped identify friction points and prioritize the MVP features.

---

# User Journey

## Persona

**Aarav Sharma**

Computer Science Student

---

## Journey

| Stage | User Action | User Goal | Pain Point | Cognitive OS Solution |
|--------|-------------|-----------|------------|-----------------------|
| Discover | Needs study notes for an exam | Find relevant notes | Notes scattered across apps | Centralized dashboard |
| Organize | Creates and tags notes | Keep information structured | Difficult to organize information | Notes + Tags |
| Search | Searches for a concept | Retrieve information quickly | Cannot remember exact keywords | AI Semantic Search |
| Explore | Opens related notes | Understand connected ideas | No visualization of relationships | Knowledge Graph |
| Learn | Revises content | Study efficiently | Time wasted searching | Fast knowledge retrieval |

---

# Journey Flow

```text
Need Information
        │
        ▼
Open Cognitive OS
        │
        ▼
Dashboard
        │
        ▼
Search by Concept
        │
        ▼
Semantic Search
        │
        ▼
Open Relevant Note
        │
        ▼
Explore Knowledge Graph
        │
        ▼
Continue Learning
```

---

# Pain Points Identified

- Information stored across multiple platforms.
- Difficult to remember exact keywords.
- No easy way to connect related ideas.
- Time lost searching for old notes.
- Large note collections become difficult to manage.

---

# Product Opportunities

These pain points led to the following MVP features:

- AI Semantic Search
- Knowledge Graph
- Dashboard
- Note Organization
- Tags
- Secure Authentication

---

# MVP Prioritization

The RICE framework was used to prioritize features.

**RICE = Reach × Impact × Confidence ÷ Effort**

| Feature | Reach | Impact | Confidence | Effort | Priority |
|----------|------:|-------:|-----------:|--------:|---------|
| Notes CRUD | High | High | High | Low | ⭐⭐⭐⭐⭐ |
| JWT Authentication | High | High | High | Low | ⭐⭐⭐⭐⭐ |
| Dashboard | High | High | High | Low | ⭐⭐⭐⭐⭐ |
| Semantic Search | High | Very High | Medium | Medium | ⭐⭐⭐⭐⭐ |
| Tags | Medium | Medium | High | Low | ⭐⭐⭐⭐ |
| Knowledge Graph | Medium | Very High | Medium | High | ⭐⭐⭐⭐ |
| AI Chat | Low | High | Low | High | ⭐⭐ |
| Voice Notes | Low | Medium | Low | High | ⭐ |
| Team Collaboration | Low | Medium | Medium | Very High | ⭐ |

---

# MVP Scope

## Included

- User Authentication
- Dashboard
- Notes
- AI Semantic Search
- Tags
- Knowledge Graph

---

## Deferred

- AI Chat Assistant
- Voice Notes
- Team Collaboration
- Mobile Application
- OCR
- Real-time Collaboration

---

# Key Takeaways

The MVP focuses on solving the most critical user problem:

> **Help users quickly organize and retrieve knowledge without relying on exact keywords.**

Features that directly support this goal were prioritized for the initial release, while advanced capabilities were deferred until after validating user adoption.
