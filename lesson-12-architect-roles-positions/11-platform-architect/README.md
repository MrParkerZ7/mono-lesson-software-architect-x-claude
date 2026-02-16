# Platform Architect

> **Navigation**: [Back to Lesson Overview](../README.md) | [Previous: Integration Architect](../10-integration-architect/README.md) | [Next: Systems Architect](../12-systems-architect/README.md)

---

## 11.1 Role Overview

The **Platform Architect** designs internal developer platforms, CI/CD pipelines, and developer tooling that enable development teams to be productive. They focus on developer experience (DevEx), creating self-service capabilities, and building the "golden paths" that teams use to build and deploy software.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                      PLATFORM ARCHITECT POSITION                         │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                        DEVELOPMENT TEAMS                                 │
│       ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐           │
│       │  Team A  │  │  Team B  │  │  Team C  │  │  Team D  │           │
│       └────┬─────┘  └────┬─────┘  └────┬─────┘  └────┬─────┘           │
│            │             │             │             │                   │
│            └─────────────┴──────┬──────┴─────────────┘                   │
│                                 │                                        │
│                                 ▼                                        │
│  ┌──────────────────────────────────────────────────────────────────┐   │
│  │                     PLATFORM ARCHITECT                           │   │
│  │                                                                  │   │
│  │   ┌───────────────────────────────────────────────────────────┐ │   │
│  │   │              INTERNAL DEVELOPER PLATFORM                  │ │   │
│  │   │                                                           │ │   │
│  │   │  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐     │ │   │
│  │   │  │ CI/CD   │  │ Service │  │  Infra  │  │Developer│     │ │   │
│  │   │  │Pipelines│  │  Mesh   │  │   as    │  │  Portal │     │ │   │
│  │   │  │         │  │         │  │  Code   │  │         │     │ │   │
│  │   │  └─────────┘  └─────────┘  └─────────┘  └─────────┘     │ │   │
│  │   │                                                           │ │   │
│  │   │  Golden Paths │ Self-Service │ Guardrails │ Templates    │ │   │
│  │   └───────────────────────────────────────────────────────────┘ │   │
│  │                                                                  │   │
│  └──────────────────────────────────────────────────────────────────┘   │
│                                 │                                        │
│                                 ▼                                        │
│                   ┌───────────────────────────┐                         │
│                   │   CLOUD INFRASTRUCTURE    │                         │
│                   └───────────────────────────┘                         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.2 Core Responsibilities

### Primary Responsibilities

| Responsibility | Description | Time Allocation |
|----------------|-------------|-----------------|
| **Platform Design** | Design internal developer platform architecture | 25% |
| **CI/CD Architecture** | Design build, test, and deployment pipelines | 20% |
| **Developer Experience** | Improve developer productivity and satisfaction | 20% |
| **Infrastructure Abstraction** | Create self-service infrastructure capabilities | 15% |
| **Standardization** | Define golden paths and best practices | 10% |
| **Platform Operations** | Ensure platform reliability and performance | 10% |

### Platform Engineering Domains

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    PLATFORM ENGINEERING DOMAINS                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  CI/CD & AUTOMATION                  INFRASTRUCTURE PLATFORM             │
│  ├── Pipeline Orchestration          ├── Container Orchestration (K8s)  │
│  ├── Build Systems                   ├── Infrastructure as Code         │
│  ├── Artifact Management             ├── Service Mesh                   │
│  ├── GitOps Workflows                ├── Secrets Management             │
│  └── Deployment Strategies           └── Cloud Resources                │
│                                                                          │
│  DEVELOPER EXPERIENCE                OBSERVABILITY PLATFORM              │
│  ├── Developer Portal                ├── Logging Infrastructure         │
│  ├── Service Catalog                 ├── Metrics & Monitoring           │
│  ├── Documentation Systems           ├── Distributed Tracing            │
│  ├── Local Development               ├── Alerting & Incidents           │
│  └── Self-Service Tools              └── Dashboards                     │
│                                                                          │
│  SECURITY & COMPLIANCE               INTERNAL TOOLING                    │
│  ├── Policy as Code                  ├── CLI Tools                      │
│  ├── Security Scanning               ├── SDKs & Libraries               │
│  ├── Compliance Automation           ├── Templates & Scaffolding        │
│  └── Identity Federation             └── Custom Controllers             │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.3 Day-to-Day Activities

### Typical Week

```
┌─────────────────────────────────────────────────────────────────────────┐
│                   PLATFORM ARCHITECT WEEKLY SCHEDULE                     │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  MONDAY                                                                  │
│  ├── 09:00  Platform team standup                                      │
│  ├── 10:00  Developer experience feedback review                       │
│  ├── 14:00  CI/CD pipeline optimization                                │
│  └── 16:00  Platform roadmap planning                                  │
│                                                                          │
│  TUESDAY                                                                 │
│  ├── 09:00  Infrastructure design session                              │
│  ├── 11:00  Kubernetes cluster architecture                            │
│  ├── 14:00  Developer office hours                                     │
│  └── 16:00  GitOps workflow improvements                               │
│                                                                          │
│  WEDNESDAY                                                               │
│  ├── 09:00  Cross-team architecture sync                               │
│  ├── 11:00  Service mesh configuration                                 │
│  ├── 14:00  Security review (platform)                                 │
│  └── 16:00  Documentation and golden paths                             │
│                                                                          │
│  THURSDAY                                                                │
│  ├── 09:00  Platform reliability review                                │
│  ├── 11:00  Tool evaluation and POC                                    │
│  ├── 14:00  Developer onboarding improvement                           │
│  └── 16:00  IaC code review                                            │
│                                                                          │
│  FRIDAY                                                                  │
│  ├── 09:00  Weekly platform metrics review                             │
│  ├── 11:00  Team learning/exploration                                  │
│  ├── 14:00  Developer feedback sessions                                │
│  └── 16:00  Sprint planning                                            │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.4 Required Skills

### Technical Skills

| Skill Category | Required Proficiency | Examples |
|----------------|---------------------|----------|
| **Kubernetes** | Expert | K8s architecture, operators, CRDs |
| **CI/CD** | Expert | GitHub Actions, GitLab, Jenkins, Argo |
| **Infrastructure as Code** | Expert | Terraform, Pulumi, Crossplane |
| **Cloud Platforms** | Advanced | AWS, Azure, GCP |
| **Containers** | Expert | Docker, containerd |
| **Programming** | Advanced | Go, Python, Bash |
| **GitOps** | Advanced | ArgoCD, Flux |

### Platform Engineering Stack

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    PLATFORM ENGINEERING STACK                            │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  DEVELOPER INTERFACE                                                     │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Backstage │ Port │ Cortex │ Custom Portal                      │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  CI/CD LAYER                                                             │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  GitHub Actions │ GitLab CI │ Jenkins │ CircleCI │ Tekton       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  GITOPS & DEPLOYMENT                                                     │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  ArgoCD │ Flux │ Spinnaker │ Argo Rollouts                      │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  INFRASTRUCTURE                                                          │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Terraform │ Crossplane │ Pulumi │ CloudFormation               │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  CONTAINER ORCHESTRATION                                                 │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Kubernetes │ EKS │ AKS │ GKE │ OpenShift                       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  SERVICE MESH & NETWORKING                                               │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Istio │ Linkerd │ Cilium │ Kong │ Traefik                      │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  OBSERVABILITY                                                           │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Prometheus │ Grafana │ Jaeger │ Loki │ OpenTelemetry           │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.5 Key Deliverables

### Primary Artifacts

| Deliverable | Purpose | Audience |
|-------------|---------|----------|
| **Platform Architecture Document** | Overall platform design | All stakeholders |
| **Golden Path Templates** | Standardized project setup | Development teams |
| **CI/CD Pipeline Templates** | Reusable build/deploy configs | Developers |
| **Developer Portal** | Self-service interface | All developers |
| **Platform Runbooks** | Operational procedures | Platform team |
| **Developer Documentation** | How-to guides and tutorials | Developers |

### Internal Developer Platform (IDP) Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                INTERNAL DEVELOPER PLATFORM ARCHITECTURE                  │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│                         DEVELOPER PORTAL                                 │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐       │    │
│  │  │  Service  │ │ Templates │ │   Docs    │ │  Metrics  │       │    │
│  │  │  Catalog  │ │ & Scaffold│ │  & Guides │ │ Dashboard │       │    │
│  │  └───────────┘ └───────────┘ └───────────┘ └───────────┘       │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                  │                                       │
│                                  ▼                                       │
│                         PLATFORM API LAYER                               │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │  Self-Service APIs │ Resource Provisioning │ Pipeline Triggers   │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                  │                                       │
│           ┌──────────────────────┼──────────────────────┐               │
│           ▼                      ▼                      ▼               │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │    CI/CD        │  │  Infrastructure │  │  Observability  │         │
│  │   Pipelines     │  │   Provisioning  │  │    Platform     │         │
│  │                 │  │                 │  │                 │         │
│  │ • Build         │  │ • Kubernetes    │  │ • Logging       │         │
│  │ • Test          │  │ • Databases     │  │ • Metrics       │         │
│  │ • Security Scan │  │ • Queues        │  │ • Tracing       │         │
│  │ • Deploy        │  │ • Caches        │  │ • Alerting      │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                  │                                       │
│                                  ▼                                       │
│                    ┌───────────────────────────┐                        │
│                    │   CLOUD INFRASTRUCTURE    │                        │
│                    │    (AWS/Azure/GCP)        │                        │
│                    └───────────────────────────┘                        │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.6 Golden Paths

### What are Golden Paths?

Golden paths are opinionated, well-supported ways to accomplish common tasks. They represent the "best" way to do something in your organization.

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    GOLDEN PATH EXAMPLE                                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  TASK: "I need to deploy a new microservice"                            │
│                                                                          │
│  GOLDEN PATH:                                                            │
│  ┌─────────────────────────────────────────────────────────────────┐    │
│  │                                                                  │    │
│  │  1. Developer Portal                                            │    │
│  │     └─▶ Select "New Service" template                           │    │
│  │                                                                  │    │
│  │  2. Template Applied                                             │    │
│  │     ├── Repository created with structure                       │    │
│  │     ├── CI/CD pipeline configured                               │    │
│  │     ├── Kubernetes manifests generated                          │    │
│  │     ├── Monitoring dashboards created                           │    │
│  │     └── Documentation scaffolded                                │    │
│  │                                                                  │    │
│  │  3. Developer Writes Code                                        │    │
│  │     └─▶ Focus on business logic only                            │    │
│  │                                                                  │    │
│  │  4. git push                                                     │    │
│  │     ├── CI runs (build, test, scan)                             │    │
│  │     ├── ArgoCD syncs to staging                                 │    │
│  │     └── Promotion to prod via approval                          │    │
│  │                                                                  │    │
│  │  5. Service Running                                              │    │
│  │     ├── Auto-scaling configured                                 │    │
│  │     ├── Logs flowing to central system                          │    │
│  │     └── Metrics and alerts active                               │    │
│  │                                                                  │    │
│  └─────────────────────────────────────────────────────────────────┘    │
│                                                                          │
│  TIME TO PRODUCTION: Hours instead of days/weeks                        │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.7 Platform Metrics

### Key Platform Metrics (DevEx Metrics)

| Category | Metric | Target |
|----------|--------|--------|
| **Deployment Frequency** | Deploys per day | ↑ Higher is better |
| **Lead Time for Changes** | Commit to production | < 1 day |
| **Change Failure Rate** | % of deployments causing issues | < 5% |
| **MTTR** | Time to recover from failure | < 1 hour |
| **Developer Satisfaction** | NPS/survey scores | > 50 NPS |
| **Time to First Deploy** | New dev to first deploy | < 1 day |
| **Self-Service Ratio** | % of tasks done self-service | > 80% |

### DORA Metrics

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    DORA METRICS                                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  METRIC                    ELITE         HIGH          MEDIUM   LOW      │
│  ─────────────────────────────────────────────────────────────────────  │
│                                                                          │
│  Deployment Frequency      On-demand     Daily-Weekly  Monthly  Monthly+ │
│                            (multiple/    (once/week-                     │
│                             day)         once/month)                     │
│                                                                          │
│  Lead Time for Changes     < 1 hour      1 day - 1 wk  1-6 mo   > 6 mo   │
│                                                                          │
│  Change Failure Rate       0-15%         16-30%        31-45%   > 45%    │
│                                                                          │
│  Time to Restore Service   < 1 hour      < 1 day       1 day-   > 1 mo   │
│                                                         1 week           │
│                                                                          │
│  PLATFORM GOAL: Enable teams to achieve ELITE performance               │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 11.8 Career Path

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    PLATFORM ARCHITECT CAREER PATH                        │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                          │
│  ENTRY POINTS                                                            │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐          │
│  │    DevOps       │  │     SRE         │  │    Backend      │          │
│  │   Engineer      │  │   Engineer      │  │   Developer     │          │
│  │   (4+ years)    │  │   (4+ years)    │  │   (5+ years)    │          │
│  └────────┬────────┘  └────────┬────────┘  └────────┬────────┘          │
│           │                    │                    │                    │
│           └────────────────────┼────────────────────┘                    │
│                                ▼                                         │
│                    ┌───────────────────────┐                            │
│                    │       PLATFORM        │                            │
│                    │       ARCHITECT       │                            │
│                    │      (3-5 years)      │                            │
│                    └───────────┬───────────┘                            │
│                                │                                         │
│              ┌─────────────────┼─────────────────┐                      │
│              ▼                 ▼                 ▼                      │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐         │
│  │    VP of        │  │   Principal     │  │  Head of        │         │
│  │   Platform      │  │   Engineer      │  │  Developer Exp  │         │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘         │
│                                                                          │
└─────────────────────────────────────────────────────────────────────────┘
```

### Certifications

| Certification | Provider | Relevance |
|---------------|----------|-----------|
| Certified Kubernetes Administrator (CKA) | CNCF | Essential |
| Certified Kubernetes Security (CKS) | CNCF | High |
| Terraform Associate | HashiCorp | High |
| AWS/Azure DevOps Certifications | Cloud Providers | High |
| GitOps Certified | Codefresh/GitOps | Medium |

---

## 11.9 Sample Scenarios

### Scenario 1: Platform Migration

**Situation**: Organization is moving from Jenkins to a modern GitOps-based platform.

**Platform Architect Actions**:
1. Design target platform architecture (ArgoCD + GitHub Actions)
2. Create migration strategy with minimal disruption
3. Build new pipeline templates matching existing capabilities
4. Design GitOps repository structure
5. Create developer migration guides
6. Implement parallel running during transition
7. Train teams on new workflows
8. Decommission legacy system

### Scenario 2: Developer Portal Implementation

**Situation**: Company wants to implement Backstage as their developer portal.

**Platform Architect Actions**:
1. Design Backstage architecture and plugins
2. Define service catalog schema
3. Create templates for common project types
4. Integrate with existing CI/CD and cloud
5. Design documentation publishing workflow
6. Implement TechDocs for existing services
7. Create adoption and rollout plan
8. Measure developer experience improvement

---

## 11.10 Comparison with Other Roles

| Aspect | Platform Architect | Cloud Architect | DevOps Engineer |
|--------|-------------------|-----------------|-----------------|
| **Focus** | Developer experience | Cloud infrastructure | Automation & delivery |
| **Primary User** | Developers | Applications | Operations |
| **Scope** | Platform as product | Cloud services | Pipelines & tools |
| **Coding** | High (Go, Python) | Medium (IaC) | High (Scripts, IaC) |
| **Kubernetes** | Expert | Advanced | Advanced |

---

## Key Takeaways

- Platform Architects **treat the platform as a product** for developers
- **Developer experience (DevEx)** is the primary success metric
- **Golden paths** reduce cognitive load and enforce best practices
- **Self-service** capabilities empower teams and reduce bottlenecks
- Must balance **standardization with flexibility**
- Role requires **deep technical skills** plus empathy for developers

---

## Practical Exercises

1. **Golden Path Design**: Design a golden path for deploying a new microservice, from template to production.

2. **Platform Assessment**: Evaluate an existing platform using DORA metrics and propose improvements.

3. **Developer Portal**: Design the information architecture for a developer portal including service catalog, templates, and documentation.

4. **CI/CD Optimization**: Analyze a slow CI/CD pipeline and propose optimizations to reduce build time by 50%.

---

## Further Reading

- [Team Topologies by Skelton & Pais](https://teamtopologies.com/book)
- [Platform Engineering on Kubernetes (O'Reilly)](https://www.oreilly.com/library/view/platform-engineering-on/9781617299322/)
- [The DevOps Handbook](https://itrevolution.com/the-devops-handbook/)
- [Backstage Documentation](https://backstage.io/docs/overview/what-is-backstage)
