# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an educational curriculum repository for Software Architects. It contains 13 structured lessons (00-12) covering architecture principles, cloud platforms, security, DevOps, soft skills, and architect career paths. This is NOT a software application - it's a knowledge base with markdown documentation and visual diagrams.

## Repository Structure

```
lesson-XX-topic-name/
├── README.md                    # Lesson overview, objectives, sub-lesson links
├── XX.0-lesson-overview.drawio  # Main lesson overview diagram (optional)
├── 01-sub-topic/
│   ├── README.md               # Sub-lesson content
│   ├── XX.1-diagram-name.drawio # DrawIO diagram source (numbered)
│   └── XX.1-diagram-name.png   # PNG export of diagram
├── 02-sub-topic/
│   ├── README.md
│   ├── XX.2-diagram-name.drawio
│   └── XX.2-diagram-name.png
└── ...
```

## Lesson Topics

- **00**: Software Architect Overview (role, responsibilities, positioning)
- **01**: Software Design & Architecture (patterns, styles, SOLID, API design)
- **02**: Event-Driven Architecture (message brokers, streaming, async patterns)
- **03**: Cloud Platforms & Services (AWS, Azure, GCP, cloud-native)
- **04**: Identity & Access Management (OAuth2, RBAC, zero trust)
- **05**: DevOps & Platform Engineering (CI/CD, IaC, Kubernetes, GitOps)
- **06**: Security (secure coding, secrets management, compliance)
- **07**: Networking (load balancing, service mesh, API gateway)
- **08**: Databases & Storage (relational, NoSQL, CAP theorem, caching)
- **09**: Observability & Monitoring (logging, metrics, distributed tracing)
- **10**: Soft Skills (communication, leadership, decision-making)
- **11**: Architecture Fundamentals (principles, trade-offs, documentation)
- **12**: Architect Roles & Positions (16 roles: hands-on, generalist, specialist, leadership)

## Working with Diagrams

### Naming Convention
- Diagrams follow the pattern: `[lesson].[sub-lesson]-descriptive-name.drawio`
- Examples: `1.1-creational-patterns-overview.drawio`, `12.5-domain-architect.drawio`
- Lesson overview diagrams use `.0` suffix: `12.0-architect-roles-overview.drawio`

### File Requirements
- All diagrams use DrawIO format (`.drawio` XML files)
- Each diagram must have a corresponding PNG export for viewing
- When modifying diagrams, update both the `.drawio` source and regenerate the `.png` export

### Styling Standards
- Enable shadows on shapes (`shadow=1`)
- Use curved arrows where appropriate (`curved=1`)
- Add flow animation to directional arrows (`flowAnimation=1`)
- Use consistent color schemes within each lesson
- Include title and descriptive labels in diagrams

## Content Conventions

- Sub-lessons are numbered sequentially (01-, 02-, etc.)
- Each README follows a consistent structure: overview, detailed content, practical exercises, further reading
- Lesson READMEs include file structure tables linking to all sub-lessons and diagrams

## Git Workflow

Commits in this repository include Claude as co-author:
```
Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>
```
