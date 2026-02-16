# Software Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Application Architect](../02-handson-application-architect/README.md) | [Next: Solution Architect](../04-generalist-solution-architect/README.md)

---

## 3.1 Role Overview

The **Software Architect** focuses on the design of software systems with emphasis on code quality, maintainability, and long-term technical health. This role bridges the gap between high-level system design and hands-on implementation, making decisions about software structure, frameworks, and development practices that shape how teams build and evolve applications.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      SOFTWARE ARCHITECT POSITION                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                    ┌────────────────────────────────┐                   │
│                    │     SYSTEM REQUIREMENTS        │                   │
│                    │  (Performance, Scalability,    │                   │
│                    │   Maintainability, Security)   │                   │
│                    └──────────────┬─────────────────┘                   │
│                                   │                                      │
│                                   ▼                                      │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                    SOFTWARE ARCHITECT                            │   │
│  │                                                                  │   │
│  │   DESIGNS                          DECIDES                       │   │
│  │   ├── System Structure             ├── Technology Stack          │   │
│  │   ├── Component Boundaries         ├── Frameworks & Libraries    │   │
│  │   ├── Data Models                  ├── Coding Standards          │   │
│  │   ├── API Contracts                ├── Development Practices     │   │
│  │   └── Integration Patterns         └── Technical Debt Strategy   │   │
│  │                                                                  │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                   │                                      │
│               ┌───────────────────┼───────────────────┐                 │
│               ▼                   ▼                   ▼                 │
│       ┌─────────────┐     ┌─────────────┐     ┌─────────────┐          │
│       │    Dev      │     │    Dev      │     │    Dev      │          │
│       │   Team A    │     │   Team B    │     │   Team C    │          │
│       └─────────────┘     └─────────────┘     └─────────────┘          │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Software Design** | Create software architecture and system design | 30% |
| **Technical Standards** | Define coding practices and quality standards | 20% |
| **Technology Selection** | Choose frameworks, libraries, and tools | 15% |
| **Code Quality** | Review code and ensure architectural compliance | 15% |
| **Technical Debt Management** | Identify and plan remediation | 10% |
| **Developer Enablement** | Support teams with guidance and tooling | 10% |

### Software Architecture Concerns

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SOFTWARE ARCHITECTURE CONCERNS                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  STRUCTURAL CONCERNS                 QUALITY ATTRIBUTES                  │
│  ├── Module organization             ├── Maintainability               │
│  ├── Component decomposition         ├── Testability                   │
│  ├── Layer separation                ├── Extensibility                 │
│  ├── Dependency management           ├── Performance                   │
│  └── Package/namespace structure     ├── Reliability                   │
│                                      └── Security                       │
│                                                                          │
│  BEHAVIORAL CONCERNS                 EVOLUTIONARY CONCERNS              │
│  ├── Control flow                    ├── Technical debt                │
│  ├── Data flow                       ├── Refactoring strategy          │
│  ├── Error handling                  ├── Upgrade paths                 │
│  ├── State management                ├── Feature toggles               │
│  └── Concurrency patterns            └── Deprecation plans             │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   SOFTWARE ARCHITECT WEEKLY SCHEDULE                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Architecture team standup                                  │
│  ├── 10:00  Design review for new feature                              │
│  ├── 14:00  Code review session (focus on architecture)                │
│  └── 16:00  Technical debt assessment                                  │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Cross-team architecture sync                               │
│  ├── 11:00  Coding: Framework improvement                              │
│  ├── 14:00  Developer consultation (office hours)                      │
│  └── 16:00  Documentation updates                                      │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Design workshop: Microservices boundaries                  │
│  ├── 11:00  POC development                                            │
│  ├── 14:00  Quality metrics review                                     │
│  └── 16:00  Technology evaluation                                      │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Architecture decision meeting                              │
│  ├── 11:00  Refactoring planning session                               │
│  ├── 14:00  Code review and mentoring                                  │
│  └── 16:00  Standards documentation                                    │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly architecture review                                 │
│  ├── 11:00  Research and learning                                      │
│  ├── 14:00  Knowledge sharing session                                  │
│  └── 16:00  Planning for next sprint                                   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Software Design** | Expert | SOLID, DDD, clean architecture |
| **Programming** | Advanced | Multiple languages preferred |
| **Design Patterns** | Expert | GoF, enterprise patterns |
| **System Modeling** | Advanced | UML, C4, ArchiMate |
| **Testing Strategies** | Advanced | TDD, BDD, testing pyramid |
| **API Design** | Advanced | REST, GraphQL, gRPC |
| **Databases** | Advanced | Schema design, optimization |

### Software Design Principles Mastery

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    CORE DESIGN PRINCIPLES                                │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  SOLID PRINCIPLES                                                        │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │ S │ Single Responsibility    │ One reason to change            │    │
│  │ O │ Open/Closed              │ Open for extension, closed mod  │    │
│  │ L │ Liskov Substitution      │ Subtypes must be substitutable  │    │
│  │ I │ Interface Segregation    │ Many specific interfaces        │    │
│  │ D │ Dependency Inversion     │ Depend on abstractions          │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  OTHER KEY PRINCIPLES                                                    │
│  ├── DRY (Don't Repeat Yourself)                                        │
│  ├── KISS (Keep It Simple, Stupid)                                      │
│  ├── YAGNI (You Ain't Gonna Need It)                                    │
│  ├── Separation of Concerns                                              │
│  ├── Composition over Inheritance                                       │
│  ├── Law of Demeter                                                     │
│  └── Fail Fast / Fail Loudly                                            │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Software Architecture Document** | Overall software design | All stakeholders |
| **Component Diagrams** | System structure visualization | Developers |
| **API Specifications** | Interface contracts | Teams, consumers |
| **Coding Standards Guide** | Quality guidelines | Development teams |
| **Technical Debt Backlog** | Prioritized improvements | Product, engineering |
| **Architecture Decision Records** | Decision documentation | Future maintainers |

### Example: Module Design Document

```markdown
# User Service Module Design

## Overview
The User Service handles user account management, authentication,
and profile operations.

## Responsibilities
- User registration and account creation
- User authentication and session management
- Profile management
- User preferences
- Account deletion (GDPR compliance)

## Dependencies
- External: Identity Provider (OAuth), Email Service
- Internal: Notification Service, Audit Service

## API Surface
- POST /users - Create user
- GET /users/{id} - Get user profile
- PUT /users/{id} - Update profile
- DELETE /users/{id} - Delete account

## Data Model
```
User
├── id: UUID
├── email: String (unique)
├── profile: Profile
├── preferences: Preferences
├── createdAt: Timestamp
└── updatedAt: Timestamp
```

## Quality Requirements
- Response time: < 100ms (p95)
- Availability: 99.9%
- Test coverage: > 80%

## Technical Decisions
- ADR-001: Use JWT for session tokens
- ADR-002: Event-driven profile updates
```

---

## 5.6 Software Architecture Styles

### Architectural Style Selection

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   ARCHITECTURE STYLE DECISION GUIDE                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONOLITHIC                                                              │
│  ├── Single deployable unit                                             │
│  ├── Best for: Small teams, simple domains, rapid MVP                   │
│  └── Considerations: Can evolve to modular monolith                     │
│                                                                          │
│  MODULAR MONOLITH                                                        │
│  ├── Single deployment, clear module boundaries                         │
│  ├── Best for: Medium complexity, team growth planned                   │
│  └── Considerations: Stepping stone to microservices                    │
│                                                                          │
│  MICROSERVICES                                                           │
│  ├── Independent deployable services                                    │
│  ├── Best for: Large teams, complex domains, scale needs                │
│  └── Considerations: Operational complexity, distributed systems        │
│                                                                          │
│  EVENT-DRIVEN                                                            │
│  ├── Async communication via events                                     │
│  ├── Best for: Loose coupling, reactive systems                         │
│  └── Considerations: Eventual consistency, debugging complexity         │
│                                                                          │
│  SERVERLESS                                                              │
│  ├── Function-based, managed infrastructure                             │
│  ├── Best for: Variable load, event processing                          │
│  └── Considerations: Cold starts, vendor lock-in                        │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Domain-Driven Design Integration

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DDD STRATEGIC PATTERNS                                │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │                      BOUNDED CONTEXTS                            │    │
│  │                                                                  │    │
│  │   ┌─────────────┐       ┌─────────────┐       ┌─────────────┐   │    │
│  │   │   Orders    │       │   Shipping  │       │   Billing   │   │    │
│  │   │   Context   │◄─────▶│   Context   │◄─────▶│   Context   │   │    │
│  │   │             │       │             │       │             │   │    │
│  │   │ • Order     │       │ • Shipment  │       │ • Invoice   │   │    │
│  │   │ • LineItem  │       │ • Tracking  │       │ • Payment   │   │    │
│  │   │ • Cart      │       │ • Carrier   │       │ • Refund    │   │    │
│  │   └─────────────┘       └─────────────┘       └─────────────┘   │    │
│  │                                                                  │    │
│  │   Context Map: Shows relationships between bounded contexts      │    │
│  │   Integration: ACL, Open Host Service, Published Language       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  TACTICAL PATTERNS                                                       │
│  ├── Entities (identity-based)                                          │
│  ├── Value Objects (attribute-based)                                    │
│  ├── Aggregates (consistency boundaries)                                │
│  ├── Domain Services (stateless operations)                             │
│  ├── Domain Events (significant occurrences)                            │
│  └── Repositories (persistence abstraction)                             │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.7 Technical Debt Management

### Technical Debt Categories

| Category | Examples | Priority |
|----------|----------|----------|
| **Code Debt** | Duplicated code, poor naming, complex methods | Medium |
| **Design Debt** | Violated patterns, tight coupling | High |
| **Test Debt** | Missing tests, flaky tests | High |
| **Documentation Debt** | Outdated docs, missing docs | Low-Medium |
| **Dependency Debt** | Outdated libraries, security vulnerabilities | High |
| **Infrastructure Debt** | Manual processes, missing automation | Medium |

### Technical Debt Quadrant

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    TECHNICAL DEBT QUADRANT                               │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                          DELIBERATE                                      │
│                              │                                           │
│      ┌──────────────────────┼──────────────────────┐                    │
│      │                      │                      │                    │
│      │   PRUDENT            │   PRUDENT            │                    │
│      │   DELIBERATE         │   INADVERTENT        │                    │
│      │                      │                      │                    │
│      │   "We know this is   │   "Now we know how   │                    │
│      │   debt but we must   │   we should have     │                    │
│      │   ship now"          │   done it"           │                    │
│      │                      │                      │                    │
│  ────┼──────────────────────┼──────────────────────┼────  PRUDENT      │
│      │                      │                      │                    │
│      │   RECKLESS           │   RECKLESS           │                    │
│      │   DELIBERATE         │   INADVERTENT        │                    │
│      │                      │                      │                    │
│      │   "We don't have     │   "What's            │                    │
│      │   time for design"   │   layering?"         │                    │
│      │                      │                      │                    │
│      └──────────────────────┼──────────────────────┘                    │
│                              │                                           │
│                          INADVERTENT                                     │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    SOFTWARE ARCHITECT CAREER PATH                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │    Senior       │  │   Tech Lead     │  │  Application    │          │
│  │   Developer     │  │                 │  │  Architect      │          │
│  │   (5+ years)    │  │   (3+ years)    │  │  (2+ years)     │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │       SOFTWARE        │                            │
│                    │       ARCHITECT       │                            │
│                    │      (3-5 years)      │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │    Solution     │  │   Principal     │  │    Domain       │         │
│  │    Architect    │  │   Architect     │  │   Architect     │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 5.9 Sample Scenarios

### Scenario 1: System Decomposition

**Situation**: A growing monolith is becoming difficult to maintain. The team wants guidance on how to break it apart.

**Software Architect Actions**:
1. Analyze the monolith's domain model and identify bounded contexts
2. Map code dependencies and identify high-coupling areas
3. Define module boundaries using DDD principles
4. Create strangler fig migration strategy
5. Design API contracts between future services
6. Establish event-driven patterns for decoupling
7. Plan incremental extraction starting with lowest-risk modules

### Scenario 2: Framework Migration

**Situation**: The application uses an outdated framework (e.g., Angular.js to Angular) that needs upgrading.

**Software Architect Actions**:
1. Assess current codebase and migration scope
2. Design migration strategy (big bang vs. incremental)
3. Create adapter patterns for gradual migration
4. Define coding standards for new framework
5. Plan for feature parity during migration
6. Establish testing strategy during transition
7. Create timeline with team capacity considerations

---

## 5.10 Comparison with Other Roles

| Aspect | Software Architect | Application Architect | Technical Architect |
|--------|-------------------|----------------------|-------------------|
| **Scope** | Software systems | Single application | Team/technology |
| **Focus** | Design & quality | Structure & patterns | Implementation |
| **Coding** | 30-40% | 30-40% | 50%+ |
| **Abstraction** | Higher | Medium | Lower |
| **Team Span** | Multiple teams | Single team | Single team |

---

## Key Takeaways

- Software Architects **shape how software is built and evolved**
- Focus on **maintainability and technical health** over the long term
- **Design patterns and principles** are core competencies
- Manage **technical debt** strategically as part of the role
- Must balance **ideal design with practical constraints**
- Success measured by **software quality and team productivity**

---

## Practical Exercises

1. **Design Exercise**: Create a software architecture for a social media platform. Define bounded contexts, components, and integration patterns.

2. **Refactoring Plan**: Given a tightly-coupled codebase, create a refactoring plan that incrementally improves the design.

3. **ADR Writing**: Write an Architecture Decision Record for choosing between SQL and NoSQL for a specific use case.

4. **Code Review**: Review a codebase for SOLID principle violations and document recommendations.

---

## Further Reading

- [Clean Architecture by Robert C. Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
- [Building Evolutionary Architectures by Ford, Parsons, Kua](https://www.oreilly.com/library/view/building-evolutionary-architectures/9781492097532/)
- [Domain-Driven Design by Eric Evans](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)
- [Software Architecture: The Hard Parts by Ford, Richards, Sadalage, Dehghani](https://www.oreilly.com/library/view/software-architecture-the/9781492086888/)
