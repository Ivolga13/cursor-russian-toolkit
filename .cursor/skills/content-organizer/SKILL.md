---
name: content-organizer
description: Organize and structure notes, create table of contents, and maintain consistent documentation format. Use when organizing content, creating summaries, or structuring learning materials.
---

# Content Organizer

Helps organize notes, create structure, and maintain consistent formatting across your learning materials.

## When to Use

- Organizing messy or unstructured notes
- Creating table of contents for documents
- Structuring learning progress and summaries
- Maintaining consistent document formats
- Creating indexes and cross-references

## Organization Tasks

### 1. Document Structure

Ensure every learning document has:

```markdown
# Clear Title

## What I Learned
[Key concepts and insights]

## Important Details
[Specific information to remember]

## Questions
[Things to explore further]

## Next Steps
[Action items and follow-up tasks]
```

### 2. Content Categorization

Group related information:
- **Concepts**: Fundamental ideas and definitions
- **Procedures**: Step-by-step processes
- **Examples**: Concrete illustrations
- **Resources**: Links, references, and tools

### 3. Table of Contents Generation

For longer documents, create navigation:

```markdown
## Table of Contents
- [Overview](#overview)
- [Key Concepts](#key-concepts)
- [Practical Examples](#practical-examples)
- [Resources](#resources)
```

### 4. Cross-Reference Creation

Link related content:
- Reference other notes: `See also: [Cursor Basics](cursor-basics.md)`
- Link to specific sections: `More details in [Advanced Features](#advanced-features)`
- Create glossary references: `*Skills* (see glossary)`

## Organization Patterns

### Daily Learning Notes
```markdown
# Learning Progress - [Date]

## Today's Focus
What I planned to learn

## Key Discoveries
- Discovery 1 with brief explanation
- Discovery 2 with brief explanation

## Challenges
What was difficult and how I solved it

## Tomorrow's Plan
What to focus on next
```

### Topic Deep-Dive
```markdown
# [Topic Name] - Complete Guide

## Overview
Brief introduction and why this matters

## Core Concepts
### Concept 1
Definition and explanation

### Concept 2
Definition and explanation

## Practical Application
How to use this knowledge

## Common Pitfalls
What to watch out for

## Related Topics
Links to connected concepts
```

### Resource Collection
```markdown
# [Topic] Resources

## Essential Reading
- [Link 1](url) - Brief description
- [Link 2](url) - Brief description

## Tools and Software
- **Tool Name**: What it does, when to use it
- **Tool Name**: What it does, when to use it

## Practice Exercises
1. Exercise description with difficulty level
2. Exercise description with difficulty level
```

## Quality Checklist

Before finalizing organized content:

- [ ] Clear, descriptive headings
- [ ] Logical information flow
- [ ] Consistent formatting throughout
- [ ] All links work correctly
- [ ] No orphaned or duplicate information
- [ ] Easy to scan and navigate
- [ ] Action items clearly identified

## File Organization Tips

### Naming Convention
- Use descriptive, searchable names
- Include dates when relevant
- Group related files in folders

### Folder Structure
```
learning-notes/
├── fundamentals/
│   ├── cursor-basics.md
│   └── markdown-guide.md
├── weekly-reviews/
│   ├── week-1-summary.md
│   └── week-2-summary.md
└── projects/
    └── knowledge-base-setup.md
```

### Cross-File References
- Maintain a master index
- Update links when moving files
- Use relative paths for portability