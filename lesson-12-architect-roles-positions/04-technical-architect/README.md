# Technical Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Application Architect](../03-application-architect/README.md) | [Next: Software Architect](../05-software-architect/README.md)

---

## 4.1 Role Overview

The **Technical Architect** is the most hands-on architect role, providing deep technical leadership within a team or project. They are expert practitioners who code alongside developers while guiding architectural decisions. Unlike broader architect roles, Technical Architects focus on specific technologies and implementation excellence.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      TECHNICAL ARCHITECT POSITION                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                         ┌──────────────────┐                            │
│                         │    SOLUTION      │                            │
│                         │    ARCHITECT     │                            │
│                         │  (High-Level)    │                            │
│                         └────────┬─────────┘                            │
│                                  │                                       │
│                                  ▼                                       │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                   TECHNICAL ARCHITECT                            │   │
│  │                                                                  │   │
│  │         ┌─────────────────────────────────────────┐             │   │
│  │         │         DEVELOPMENT TEAM                │             │   │
│  │         │                                         │             │   │
│  │         │  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐   │             │   │
│  │         │  │ Dev │  │ Dev │  │ Dev │  │ QA  │   │             │   │
│  │    TA ──┼─▶│  1  │  │  2  │  │  3  │  │     │   │             │   │
│  │  (Codes │  └─────┘  └─────┘  └─────┘  └─────┘   │             │   │
│  │   with  │                                         │             │   │
│  │   team) │  • Code Reviews    • Pair Programming  │             │   │
│  │         │  • Technical Spikes • Troubleshooting  │             │   │
│  │         │  • Best Practices  • Mentoring         │             │   │
│  │         └─────────────────────────────────────────┘             │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 4.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Hands-On Development** | Writing production code, POCs, spikes | 40% |
| **Code Reviews** | Reviewing PRs for quality and patterns | 15% |
| **Technical Guidance** | Helping developers solve complex problems | 15% |
| **Technical Decisions** | Making technology and implementation choices | 10% |
| **Mentoring** | Growing developer skills | 10% |
| **Documentation** | Technical specs and architecture docs | 10% |

### Deep Technical Focus

```
┌─────────────────────────────────────────────────────────────────────────┐
│                  TECHNICAL ARCHITECT FOCUS AREAS                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  IMPLEMENTATION EXCELLENCE                                               │
│  ├── Write complex, critical code components                            │
│  ├── Establish coding patterns and conventions                          │
│  ├── Create reusable frameworks and libraries                           │
│  ├── Solve the hardest technical problems                               │
│  └── Optimize performance bottlenecks                                   │
│                                                                          │
│  TECHNOLOGY MASTERY                                                      │
│  ├── Deep expertise in specific tech stack                              │
│  ├── Evaluate new tools and frameworks                                  │
│  ├── Implement proof-of-concepts                                        │
│  ├── Debug complex system issues                                        │
│  └── Understand internals of key technologies                           │
│                                                                          │
│  TEAM ENABLEMENT                                                         │
│  ├── Pair program with developers                                       │
│  ├── Review all significant code changes                                │
│  ├── Conduct technical training sessions                                │
│  ├── Document best practices and patterns                               │
│  └── Unblock team on technical challenges                               │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 4.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                  TECHNICAL ARCHITECT WEEKLY SCHEDULE                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Daily standup                                               │
│  ├── 09:30  Sprint planning - technical input                           │
│  ├── 11:00  Coding: Feature implementation                              │
│  ├── 14:00  Code review session (batch PR reviews)                      │
│  └── 16:00  Technical spike: New caching approach                       │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Daily standup                                               │
│  ├── 09:30  Pair programming with junior developer                      │
│  ├── 11:30  Architecture sync with Solution Architect                   │
│  ├── 14:00  Coding: Continue feature implementation                     │
│  └── 16:00  Debug production issue investigation                        │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Daily standup                                               │
│  ├── 09:30  Coding: Complex component development                       │
│  ├── 12:00  Lunch & Learn session (host)                                │
│  ├── 14:00  Code review and mentoring                                   │
│  └── 16:00  Technical documentation updates                             │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Daily standup                                               │
│  ├── 09:30  Performance optimization work                               │
│  ├── 14:00  Technical design review                                     │
│  └── 15:30  Tool/framework evaluation                                   │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Daily standup                                               │
│  ├── 09:30  Sprint review / demo                                        │
│  ├── 11:00  Retrospective                                               │
│  ├── 14:00  Technical debt planning                                     │
│  └── 15:30  Learning and experimentation                                │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Time Distribution

| Activity | Percentage |
|----------|------------|
| Coding (production, spikes, POCs) | 40-50% |
| Code Reviews | 15-20% |
| Meetings (standups, planning, reviews) | 15% |
| Mentoring & Pair Programming | 10-15% |
| Documentation | 5-10% |
| Research & Learning | 5% |

---

## 4.4 Required Skills

### Technical Skills (Deep Expertise Required)

| Skill Category | Required Proficiency | Notes |
|----------------|---------------------|-------|
| **Primary Language** | Expert | Mastery of language internals |
| **Framework Stack** | Expert | Deep knowledge of the framework |
| **System Design** | Advanced | Distributed systems patterns |
| **Databases** | Advanced | Query optimization, indexing |
| **Testing** | Expert | TDD, testing strategies |
| **DevOps** | Advanced | CI/CD, containers, debugging |
| **Security** | Intermediate | Secure coding practices |
| **Performance** | Expert | Profiling, optimization |

### Technical Depth vs Breadth

```
┌─────────────────────────────────────────────────────────────────────────┐
│            TECHNICAL ARCHITECT SKILLS PROFILE (T-Shaped)                │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  BREADTH (Understanding across domains)                                  │
│  ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━   │
│  Cloud │ DevOps │ Security │ Data │ Frontend │ Mobile │ Architecture    │
│  ──────┴────────┴──────────┴──────┴──────────┴────────┴───────────      │
│                           │                                              │
│                           │                                              │
│                           │  DEPTH                                       │
│                           │  (Primary expertise)                         │
│                           │                                              │
│                           │  ┌─────────────────┐                        │
│                           │  │ Primary Stack   │                        │
│                           │  │ (e.g., Java +   │                        │
│                           │  │ Spring Boot +   │                        │
│                           │  │ PostgreSQL +    │                        │
│                           │  │ Kubernetes)     │                        │
│                           │  │                 │                        │
│                           │  │ • Language      │                        │
│                           │  │   Internals     │                        │
│                           │  │ • Framework     │                        │
│                           │  │   Deep Dive     │                        │
│                           │  │ • Performance   │                        │
│                           │  │   Tuning        │                        │
│                           │  │ • Best          │                        │
│                           │  │   Practices     │                        │
│                           └──┴─────────────────┘                        │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Soft Skills

| Skill | Importance | Application |
|-------|------------|-------------|
| Teaching/Mentoring | Critical | Elevating team capabilities |
| Problem Solving | Critical | Debugging complex issues |
| Communication | High | Explaining technical concepts |
| Patience | High | Working with varying skill levels |
| Collaboration | High | Pair programming, team work |

---

## 4.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Production Code** | Core application functionality | Team, production |
| **Technical Spikes** | Validate approaches, POCs | Team, architects |
| **Code Review Feedback** | Quality assurance, mentoring | Developers |
| **Technical Specs** | Detailed implementation guides | Development team |
| **Runbooks** | Operational procedures | Operations, on-call |
| **Technical Presentations** | Knowledge sharing | Team, organization |

### Code Quality Ownership

```
┌─────────────────────────────────────────────────────────────────────────┐
│               TECHNICAL ARCHITECT CODE RESPONSIBILITIES                  │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  WRITES                           REVIEWS                                │
│  ├── Critical path code           ├── All significant PRs               │
│  ├── Complex algorithms           ├── Security-sensitive code           │
│  ├── Framework extensions         ├── Performance-critical code         │
│  ├── Integration layers           ├── New patterns/approaches           │
│  ├── Performance-critical         └── Architecture compliance           │
│  │   components                                                          │
│  └── Shared libraries                                                    │
│                                                                          │
│  ESTABLISHES                      ENFORCES                               │
│  ├── Coding standards             ├── Code review checklist             │
│  ├── Project structure            ├── Testing requirements              │
│  ├── Testing patterns             ├── Documentation standards           │
│  ├── Error handling               ├── Performance criteria              │
│  │   conventions                  └── Security guidelines               │
│  └── Logging standards                                                   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 4.6 Technical Leadership Activities

### Pair Programming

Pair programming is a key activity for Technical Architects:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    PAIR PROGRAMMING SCENARIOS                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  SCENARIO: Complex Feature Implementation                                │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  TA (Navigator)              Developer (Driver)                 │    │
│  │  ├── Guides overall approach  ├── Writes the code               │    │
│  │  ├── Catches issues early     ├── Explains thinking            │    │
│  │  ├── Suggests patterns        ├── Asks questions               │    │
│  │  └── Teaches as you go        └── Implements suggestions       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  SCENARIO: Bug Investigation                                             │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  TA (Driver)                 Developer (Navigator)              │    │
│  │  ├── Demonstrates debugging   ├── Observes techniques          │    │
│  │  ├── Uses advanced tools      ├── Takes notes                  │    │
│  │  ├── Explains thought process ├── Asks clarifying questions    │    │
│  │  └── Shows root cause analysis└── Learns debugging patterns    │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  SCENARIO: Code Review Discussion                                        │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  TA                          Developer                          │    │
│  │  ├── Explains concerns        ├── Presents approach            │    │
│  │  ├── Suggests alternatives    ├── Discusses trade-offs         │    │
│  │  ├── Shows examples           ├── Implements improvements      │    │
│  │  └── Approves with feedback   └── Learns better patterns       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Technical Spikes

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    TECHNICAL SPIKE PROCESS                               │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  1. IDENTIFY UNCERTAINTY                                                 │
│     └── "Can we achieve sub-100ms response times with this approach?"  │
│                                                                          │
│  2. TIME-BOX                                                             │
│     └── Allocate 1-2 days maximum                                       │
│                                                                          │
│  3. DEFINE SUCCESS CRITERIA                                              │
│     ├── What questions need to be answered?                             │
│     └── What is the minimum viable prototype?                           │
│                                                                          │
│  4. IMPLEMENT                                                            │
│     ├── Build throwaway code (not production quality)                   │
│     ├── Focus on answering the key questions                            │
│     └── Document findings as you go                                     │
│                                                                          │
│  5. REPORT FINDINGS                                                      │
│     ├── Document: Did it work? What are the trade-offs?                │
│     ├── Present to team/stakeholders                                    │
│     └── Recommend approach based on findings                            │
│                                                                          │
│  6. DECIDE                                                               │
│     └── Team decides whether to proceed with approach                   │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 4.7 Problem-Solving Scenarios

### Scenario 1: Production Performance Issue

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    PRODUCTION ISSUE RESPONSE                             │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  SITUATION: API response times increased from 100ms to 2000ms           │
│                                                                          │
│  TECHNICAL ARCHITECT ACTIONS:                                            │
│                                                                          │
│  1. TRIAGE (15 min)                                                      │
│     ├── Check metrics dashboards                                        │
│     ├── Review recent deployments                                       │
│     ├── Check infrastructure status                                     │
│     └── Assess severity and impact                                      │
│                                                                          │
│  2. DIAGNOSE (1-2 hours)                                                 │
│     ├── Enable detailed logging                                         │
│     ├── Run APM profiler                                                │
│     ├── Analyze slow query logs                                         │
│     ├── Check connection pool status                                    │
│     └── Review recent code changes                                      │
│                                                                          │
│  3. ROOT CAUSE IDENTIFIED                                                │
│     └── New feature added N+1 query pattern                             │
│                                                                          │
│  4. FIX                                                                  │
│     ├── Implement eager loading                                         │
│     ├── Add query optimization                                          │
│     ├── Deploy hotfix                                                   │
│     └── Verify resolution                                               │
│                                                                          │
│  5. POST-MORTEM                                                          │
│     ├── Document incident                                               │
│     ├── Add query performance tests                                     │
│     └── Update code review checklist                                    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Scenario 2: Technology Evaluation

**Situation**: Team wants to adopt a new message queue (Kafka vs RabbitMQ vs AWS SQS).

**Technical Architect Actions**:
1. Define evaluation criteria (throughput, ordering, cost, complexity)
2. Build POCs for top 2 candidates
3. Benchmark under realistic conditions
4. Document pros/cons and recommendations
5. Present findings to team
6. Guide implementation of chosen solution

---

## 4.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    TECHNICAL ARCHITECT CAREER PATH                       │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐                               │
│  │    Senior       │  │   Tech Lead     │                               │
│  │   Developer     │  │                 │                               │
│  │   (5+ years)    │  │   (2+ years)    │                               │
│  └────────┬────────┘  └────────┬────────┘                               │
│           │                    │                                         │
│           └──────────┬─────────┘                                         │
│                      ▼                                                   │
│             ┌─────────────────┐                                         │
│             │    TECHNICAL    │                                         │
│             │    ARCHITECT    │                                         │
│             │   (3-5 years)   │                                         │
│             └────────┬────────┘                                         │
│                      │                                                   │
│       ┌──────────────┼──────────────┐                                   │
│       ▼              ▼              ▼                                   │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐                              │
│  │Application│ │Principal │  │Engineering│                              │
│  │ Architect│  │ Engineer │  │  Manager  │                              │
│  └──────────┘  └──────────┘  └──────────┘                              │
│                      │                                                   │
│                      ▼                                                   │
│             ┌─────────────────┐                                         │
│             │    Solution     │                                         │
│             │    Architect    │                                         │
│             └─────────────────┘                                         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Staying Technical vs. Moving Up

Many Technical Architects prefer to **stay technical**:

| Path | Focus | Trade-offs |
|------|-------|-----------|
| **Stay as TA** | Continue deep technical work | May have limited career progression |
| **Principal Engineer** | Broader technical influence | More meetings, less coding |
| **Engineering Manager** | People leadership | Significantly less coding |
| **Solution Architect** | Broader scope | Less depth, more breadth |

---

## 4.9 Tools & Technologies

### Development Tools

| Category | Examples |
|----------|----------|
| **IDEs** | IntelliJ, VS Code, Visual Studio |
| **Debugging** | Chrome DevTools, IDE debuggers, strace/dtrace |
| **Profiling** | JProfiler, dotTrace, py-spy, flamegraphs |
| **Load Testing** | JMeter, k6, Gatling, Locust |
| **Monitoring** | Grafana, Datadog, New Relic |

### Code Quality Tools

| Category | Examples |
|----------|----------|
| **Static Analysis** | SonarQube, ESLint, RuboCop |
| **Security Scanning** | Snyk, OWASP ZAP, Bandit |
| **Code Coverage** | JaCoCo, Istanbul, Coverage.py |
| **Dependency Check** | OWASP Dependency Check, npm audit |

---

## 4.10 Comparison with Other Roles

| Aspect | Technical Architect | Application Architect | Software Architect |
|--------|-------------------|----------------------|-------------------|
| **Coding Time** | 40-50% | 25-35% | 30-40% |
| **Scope** | Team/Component | Application | System |
| **Depth** | Very Deep | Deep | Medium-Deep |
| **Focus** | Implementation | Structure | Design |
| **Primary Skill** | Technology mastery | Pattern application | System thinking |

---

## Key Takeaways

- Technical Architects are the **most hands-on** architect role
- **Deep expertise** in specific technologies is required
- The role combines **coding with leadership** - not one or the other
- **Mentoring and pair programming** are key activities
- Success is measured by **team velocity and code quality**
- This role suits those who want to **stay close to code** throughout their career
- Technical credibility comes from **actively writing code**

---

## Practical Exercises

1. **Code Review Exercise**: Take a complex pull request and perform a thorough review focusing on patterns, performance, and maintainability.

2. **Technical Spike**: Choose a technology you're evaluating and build a time-boxed POC. Document your findings.

3. **Debugging Challenge**: Given a performance issue, demonstrate systematic debugging techniques to find the root cause.

4. **Teaching Session**: Prepare and deliver a 30-minute technical session on a topic you know well.

---

## Further Reading

- [The Staff Engineer's Path by Tanya Reilly](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/)
- [High Performance Browser Networking by Ilya Grigorik](https://hpbn.co/)
- [Systems Performance by Brendan Gregg](https://www.brendangregg.com/systems-performance-2nd-edition-book.html)
- [Release It! by Michael Nygard](https://pragprog.com/titles/mnee2/release-it-second-edition/)
